* Go to [groq.com](https://groq.com)
* Click the **DEV CONSOLE** buttcon
* Click the **Login with GitHub** button
* Follow the onboarding steps to create your account
* In the Dev Console click the **Playground** link at the upper right.
* This is similar to the playground in GitHub Models
* Click on the **Dashboard** link at the upper right
* Click on the **API Keys** link at the upper right
* Click the **Create API Key** button
  * Enter a name to the API key
  * Click the **Submit** button
  * Copy the API key **before** closing the dialog.  You won't be able to retrieve it later.
  * Store the API key as a secret for your fork of the workshop repository on GitHub (see [Exercise 03-02]([https://github.com](https://github.com/douglasstarnes/memmsdays25-genai4free/blob/main/03-github-models/walkthrough_03_02.md)) for details)
* In `04-groq` create a new file named `chat.py`.
* Copy and paste the contents of `03-github-models/chat.py`
* Set the `token` to the env var for `GROQ_API_KEY`
* Replace the `base_url` value with `https://api.groq.com/openai/v1`
* In the line that calls the `create` method, set the `model` keyword argument to `llama-3.3-70b-versatile`
