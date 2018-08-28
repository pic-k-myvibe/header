# Git
Tutorial rapido para usar Git

1. Primero crea un nuevo repositorio "New repository" (Este lo puedes crear desde tu perfil)

2. Agrega un nombre, descipción, publico, "Initialize this repository with a README" (selecciona el checkbox), agrega una licencia.

3. Posicionate en la carpeta de tu proyecto ejemplo: mis-documentos/mi-proyecto/
```
git init
```
4. Ahora tienes que establecer la conexión con el repositorio ya creado.
(Para entender el punto cuatro necesitas leerlo todo.)

⋅⋅* Es el nombre de tu conexion con el repositorio (puedes cambiarlo si deseas).
```
origin
```

⋅⋅* Para establecer la conexión necesitas la ruta de tu repositorio en Git.
(Esta la obtienes en tu repositorio en la parte de "Clone or download")
```
SSH/HTTPS
```

⋅⋅* Conecta un repositorio con nuestro equipo local.
```
git remote add [origin] [SSH/HTTPS]
```
⋅⋅* El comando va sin [], ejemplo:

```
git remote add origin https://github.com/la-ruta-de-tu-proyecto.git
```

5. Paa ver que la conexión es correcta escribe

```
git remote -v
```

⋅⋅* Veras algo como esto

```
origin  https://github.com/la-ruta-de-tu-proyecto.git (fetch)
origin  https://github.com/la-ruta-de-tu-proyecto.git (push)
```

6. Continuara...
