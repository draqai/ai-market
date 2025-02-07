# This is the Market Virtual Store Directory for YOI AI

![Comingh Soon](https://github.com/user-attachments/assets/8637566f-1a6b-4809-a829-263441a5ba08)


## How to Submit an Agent

If you wish to add an Agent to the list, simply add a file under the `agents` folder using the `templates/agent.json`, provide a brief description, and submit a PR to the `main` branch.

### Detailed Submission Guidelines

1. Fork this repository.

2. Make a copy of the `templates/agent.json` file.

3. Fill in the appropriate Agent configuration information.

4. Move it to the `src\agents` folder.

5. Submit the PR, wait for review, and upon merging, the `public/agents/index.json` file will be automatically rebuilt.

- The `created` field will be automatically added, please ensure the uniqueness of `agentId`.

## Format JSON

To run the `format` script locally, you need to configure the following environment variables:

| Environment Variable | Type     | Example              |
| -------------------- | -------- | -------------------- |
| `OPENAI_API_KEY`     | Required | `sk-xxxxxx...xxxxxx` |
| `OPENAI_PROXY_URL`   | Optional | `-`                  |
