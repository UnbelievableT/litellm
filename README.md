# LiteLLM pull request 41919 dashboard screenshots

Captured in Chrome from the LiteLLM Models + Endpoints page at `http://127.0.0.1:44186/models-and-endpoints?tab=add`. Both revisions used the same local admin session fixture and empty deployment, credential and team data. Provider definitions and the model cost catalogue came from each revision. The dashboard page, model form and provider picker were rendered from that revision. The fixture used local data and no operational API keys. Screenshots are cropped, with red outlines on the controls under review.

- [Before](before.png) — base `02b4292e200c6d2c8789340451fa66a0766aaf08`. Typing `TopxAI` returns “No providers found”.
- [After](after.png) — candidate `ea09b1fe8181a98a37f9227b588cc0c194b8aa4d`. The same search returns TopxAI with its provider icon.
- [Selected models](selected-models.png) — selecting TopxAI lists `topxai/gpt-6.2-sol` and `topxai/gpt-6.2-astra`, with `https://api.topxai.xyz/v1` as the API Base placeholder. No model was submitted.
