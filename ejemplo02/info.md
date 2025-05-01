## Pasos

1. Crear una base de datos en couchDB
2. Darle los permisos necesario a la base datos
3. ejecutar run.py

```
  curl -d @datos.json -H "Content-type: application/json" -X POST http://127.0.0.1:5984/su-base/_bulk_docs
```
