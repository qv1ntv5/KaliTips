### Descripción

Añadir línea a un fichero:

```
echo "Message" | sudo tee -a /path/to/file
```

Por ejemplo:

```bash
echo "127.0.0.1\tlocalhost" | sudo tee -a /etc/hosts
```