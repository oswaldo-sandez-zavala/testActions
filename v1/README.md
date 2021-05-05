# Docker action "Hola Mundo"

This actions prints "Hello world" or "Hello" + the name of a person to greet to the log.
Esta action imprime "Hola mundo" o "Hola" + el nombre de la persona al log.

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a quien saludar. Por defecto `"Mundo"`.

## Outputs

### `time`

La fecha en la que te saludé.

## Example usage

```
uses: pablokbs/hello-world-docker-action@v1
with:
   who-to-greet: 'Pelades'
```
