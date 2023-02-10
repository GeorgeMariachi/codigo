# Primer dia con Git y Github

Lista de comandos de git

*Para poder ver la version de git ejecutamos nuestra terminal:

```bash
git --version
git -v
```

* Para configurar el correo y el nombre (solo la primera vez en nuestra maquina)


```bash
git config --global user.email "micorreo@gmail.com"
git config --global user.name "Mi nombre"
```

* Para ver la configuracion de git

```bash
git config --list
```

* Para inicializar nuestro repositorio en git:

```bash
git init
```

* Para ver el estado de nuestros cambios:

```bash
git status
```

* Para preparar nuestros archivos para la zona de stage (prepararlos para comit)

```bash
git add .
git add nombreDelArichivo.extension
```

* crear el registro de los cambios realizados:

```bash
git commit -m "comentario corto y conciso"
```

* Para ver una linea de tiempo de los commits que hemos realizado:

```bash
git log
```
* Para poder ver el detalle de un commit especifico usamos:

```bash
git show id-de-commit
```