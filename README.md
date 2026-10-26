# DevOps FastAPI

Proyecto de laboratorio para aprender prácticas modernas de desarrollo y DevOps utilizando Python y FastAPI.

## Objetivos

- Desarrollo local con Python y PyCharm
- Control de versiones con Git y GitHub
- Tests automatizados con pytest
- Integración continua con GitHub Actions
- Contenedores con Docker
- Despliegue a un ambiente de TEST en Proxmox
- Automatización de infraestructura y configuración

## Ejecutar localmente

Crear y activar un entorno virtual e instalar las dependencias:

```bash
pip install -r requirements.txt
```

Ejecutar la aplicación:

```bash
python -m uvicorn app.main:app --reload
```

La API estará disponible en:

```text
http://127.0.0.1:8000
```

Documentación Swagger:

```text
http://127.0.0.1:8000/docs
```

## Tests

Ejecutar:

```bash
python -m pytest
```