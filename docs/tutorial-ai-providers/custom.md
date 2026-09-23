---
sidebar_position: 17
---

# Custom

This option allows you to choose a provider. All you need to connect is the API key and the provider's Custom Link (completion endpoint).

## Connect your Provider account
- Go to VSCode and choose `Custom` as `Provider`
- Click on `Connect` or `Set connection`
- Paste API Key here, and click on `Connect`:

<table>
  <tr>
    <td align="center">
      <img width="300" height="150" src="https://github.com/user-attachments/assets/1aba82cb-407d-415e-9e4a-e2aa87ce1c05" />
    </td>
    <td align="center">
      <img width="300" height="150" src="https://github.com/user-attachments/assets/7bd4716d-59e4-46a4-99f7-c4796030e7cf" />
    </td>
  </tr>
</table>

  
:::caution Remove Key
If you want to remove your API Key from CodeGPT, click on the provider box and click on `Disconnect`.

<p align="center">
      <img width="300" height="150" src="https://github.com/user-attachments/assets/780f7909-9688-49a8-95ca-b33a23772f6c" />
</p>

:::

## Example: IO Intelligence (io.net)

To connect [IO Intelligence](https://io.net) as a Custom provider:

- `Model`: an available model id, for example `meta-llama/Llama-3.3-70B-Instruct` (see the [model list](https://api.intelligence.io.solutions/api/v1/models))
- `API Key`: your IO Intelligence API key, from [io.net](https://io.net)
- `Custom Link` (completion endpoint): `https://api.intelligence.io.solutions/api/v1/chat/completions`

:::note Completion endpoint
For OpenAI-compatible providers, the Custom Link is the provider's completion endpoint. IO Intelligence serves the OpenAI-compatible Chat Completions API.
:::
