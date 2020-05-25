# fastt
Fast and Simple Translation Tool 

Podés usar FASTT para traducir al español un archivo `.po` usando Google Translate.
Por cada uno de los strings a traducir hace la consulta con Google Translate y marca la entrada como *fuzzy*.

# Requisitos

1. Instalar con `poetry install`
2. Crear credenciales en GCP, usá la guía en [Google Cloud Python Basic Setup](https://cloud.google.com/translate/docs/basic/setup-basic#python)
3. Guardá el archivo de credenciales como `credentials.json` en la raíz de este repo.

# Uso

```bash
poetry run python fastt/cli.py FILENAME 
```

## Opciones

```bash
poetry run python fastt/cli.py --help
```
