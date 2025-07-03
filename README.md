# Prueba Técnica - Función de Consulta API

## Descripción

Deberas desarrollar una función que realice consultas a una API externa utilizando el lenguaje de programación y editor de código de su preferencia.

### Función a Implementar

- **Nombre de la función**: `realizar_consulta`
- **Parámetros de entrada**:
  - `input`: El mensaje o consulta del usuario
  - `system`: El prompt del sistema o contexto
- **Tipo de retorno**: El resultado de la llamada a la API

### Especificaciones de la API

- **URL del endpoint**: `https://openlifter-editor.agentesai.es/webhook/prueba`
- **Método HTTP**: `POST`
- **Tipo de contenido**: `application/json`
- **Estructura del body**:

```json
{
  "input": "mensaje o consulta del usuario",
  "system": "prompt del sistema"
}
```
