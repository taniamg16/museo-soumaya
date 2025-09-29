# Museo Soumaya
Esta es una imitación del sitio web del Museo Soumaya, hecho con html y CSS. Se utiliza el apoyo de Bootstrap. 

## Índice
- [Comandos utilizados](#comandos-utilizados)
- [Pull requests](#pull-requests)
- [Despliegue de la página a GitHub Pages](#despliegue-de-la-página-a-github-pages)
- [Evidencias Responsividad](#enlace-a-los-videos-de-evidencia)


## Comandos utilizados
Pasos para crear el repositorio y subir el código.

```bash
# iniciamos git, conectamos con github y nombramos la rama principal
git init
git remote add origin https://github.com/taniamg16/museo-soumaya
git branch -M main     
git push -u origin main

# damos datos necesarios
git config --global user.email "taniaamg2003@gmail.com"
git config --global user.name "Tania"

# en VS Code, creamos archivo html donde vamos a trabajar

# creamos la rama donde vamos a trabajar y nos cambiamos a ella
git branch ramaTrabajo
git branch # para verificar
git checkout ramaTrabajo

# después de hacer cambios, hacemos stages y commits
git status
git add .
git commit -m "Descripción del cambio"

# hacemos push a la rama (subimos los cambios)
git push
```


## Pull requests
Solicitud para que los cambios que hiciste en tu rama de un repositorio sean revisados e integrados en otra rama (main). En este proyecto, se hicimos dos. A continuación, se incluyen sus links: 

### Link pull request código
`https://github.com/taniamg16/museo-soumaya/pull/1`
### Link pull request evidencias
`https://github.com/taniamg16/museo-soumaya/pull/2`

## Despliegue de la página a GitHub Pages

**GitHub Pages** es un servicio gratuito de GitHub que te permite publicar sitios web directamente desde un repositorio, sin necesidad de un servidor propio.

### Pasos para el despliegue

1. En GitHub, abre tu **repositorio**.  
2. Haz clic en **Settings** --> **Pages**.  
3. En la sección **Branch**, selecciona la **rama de trabajo** (en este caso, `ramaTrabajo`).  
4. Da clic en **Save**.  

Después de unos segundos, tu sitio estará disponible en:  
`https://TU_USUARIO.github.io/NOMBRE_DEL_REPOSITORIO/`

### Link página web desplegada
`https://taniamg16.github.io/museo-soumaya/`


## Evidencias Responsividad
En el siguiente enlace de OneDrive, se encuentran los videos de lo siguiente:
1. Prueba en iPad Pro
2. Prueba en iPad Mini
3. Prueba eb Galaxy S8+
4. Prueba en Escritorio

En cada video, se muestra lado al lado la página creada con la página original, para mostrar su funcionamiento.
El enlace a la página original es: `https://www.museo-soumaya.org/`

### Enlace a los Videos de Evidencia
`https://itam2-my.sharepoint.com/:f:/g/personal/tmendoz4_itam_mx/EjV6duwLzKZEj5ZCnpTMyA4BeDGoTUoLKgynOl7SaDwZ6w?e=lbBxTe`


