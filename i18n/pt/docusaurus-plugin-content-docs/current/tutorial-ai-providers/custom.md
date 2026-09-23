---
sidebar_position: 17
---

# Custom

Esta opção permite que você escolha um provedor. Tudo o que você precisa para se conectar é a chave da API e o Link Personalizado do provedor, comumente o link de registro.

## Conecte sua conta do Provider
- Vá para o VSCode e escolha `Custom` como `Provider`
- Clique em `Connect` ou `Set connection`
- Cole a API Key aqui e clique em `Connect`:

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

:::caution Remover Chave
Se você quiser remover sua API Key do CodeGPT, clique na caixa do provedor e clique em `Disconnect`.

<p align="center">
      <img width="300" height="150" src="https://github.com/user-attachments/assets/780f7909-9688-49a8-95ca-b33a23772f6c" />
</p>

:::

## Exemplo: IO Intelligence (io.net)

Para conectar o [IO Intelligence](https://io.net) como provedor Custom:

- `Model`: um id de modelo disponível, por exemplo `meta-llama/Llama-3.3-70B-Instruct` (veja a lista de modelos em https://api.intelligence.io.solutions/api/v1/models)
- `API Key`: sua chave de API do IO Intelligence, obtida em https://io.net
- `Link Personalizado` (endpoint de completion): `https://api.intelligence.io.solutions/api/v1/chat/completions`

:::note Endpoint de completion
Para provedores compatíveis com OpenAI, o Link Personalizado é o endpoint de completion do provedor. O IO Intelligence oferece a API Chat Completions compatível com OpenAI.
:::
