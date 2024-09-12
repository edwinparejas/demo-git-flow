# Gitflow

## Comandos git flow

### Incializar git flow

```bash
# Inicialización simple
git flow init

# Inicialización con valores por defecto
git flow init -y

# Forzar reinicialización
git flow init -f
```

### Incializar feature

```bash
$ git flow feature start <feature>
```

### Subir cambios

```bash
# Primera vez
$ git flow feature publish <feature>

# Segunda vez a posterior
$ git push
```

# Obtener cambios

```bash
# Formna compuesta
$ git flow feature pull origin <feature>

# Formna simple
$ git pull
```

### Finalizar feature

```bash
$ git flow feature finish <feature>
$ git push
```
