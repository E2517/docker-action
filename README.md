# Acción de docker Hello world

Esta acción imprime "Hello World" o "Hello" + lo que quieras escribir.

## Entradas

### ` write-a-word`

**Obligatorio** Escribe algo para que se muestre. Default `"World"`.

## Outputs

### `time`

El tiempo en que escribimos algo.

## Git commands

```
git add action.yml entrypoint.sh Dockerfile README.md
git commit -m "Mi primera acción está lista"
git tag -a -m "Mi primera versión de acción" v1
git push --follow-tags
```

## Ejemplo de uso, el nombre de tu proyecto en github y la version con tag al final

uses: actions/docker-action@v1
with:
write-a-word: 'Mona the Octocat'
