---
sidebar_position: 17
---

# Personalizado/Custom

Esta opción te permite elegir un proveedor. Todo lo que necesitas para conectarte es la clave API y el enlace personalizado del proveedor (endpoint de completion).

## Conectar tu cuenta de Proveedor

- Ve a VSCode y elige `Personalizado` como `Proveedor`
- Haz clic en `Conectar` o `Establecer conexión`
- Pega la clave API aquí y haz clic en `Conectar`:

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

:::caution Eliminar Clave
Si deseas eliminar tu clave API de CodeGPT, haz clic en el cuadro del proveedor y luego en `Desconectar`.

<p align="center">
      <img width="300" height="150" src="https://github.com/user-attachments/assets/780f7909-9688-49a8-95ca-b33a23772f6c" />
</p>

:::

## Ejemplo: IO Intelligence (io.net)

Para conectar [IO Intelligence](https://io.net) como proveedor Custom:

- `Model`: un id de modelo disponible, por ejemplo `meta-llama/Llama-3.3-70B-Instruct` (consulta la [lista de modelos](https://api.intelligence.io.solutions/api/v1/models))
- `API Key`: tu clave de API de IO Intelligence, obtenida en [io.net](https://io.net)
- `Enlace personalizado` (endpoint de completion): `https://api.intelligence.io.solutions/api/v1/chat/completions`

:::note Endpoint de completion
Para proveedores compatibles con OpenAI, el enlace personalizado es el endpoint de completion del proveedor. IO Intelligence ofrece la API Chat Completions compatible con OpenAI.
:::
