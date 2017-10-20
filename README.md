# <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/HTML5.png" alt="Sizmek" width="26" height="36" /></a> HTML5 Image Ad <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/logo-dark.png" alt="Sizmek" width="57" height="15" /></a>

Plantilla para crear anuncios con un fichero de imagen de más de 200KB utilizando workspaces de Sizmek.

## Descripción

Los formatos de imagen en la plataforma de Sizmek estan limitados a imagenes de menos de 200Kb. Aunque no es una práctica recomendable, se pueden utilizar imagenes de cualquier peso para crear un anuncio utilizando un "armazon" HTML para ello.

Para crear este formato, a parte de la imagen que tengamos por encima de 200KB, tendremos que preparar una imagen que se encuentre por debajo de ese peso para utilizarse como imagen de backup. Esta imagen solo se mostrará para dispositivos que tengan bloqueado el javascript y en el caso de que el formato se pase de las impresiones contratadas.

## Configuración 

Una vez tengas preparadas tus imagenes, reemplaza la imagen de la plantilla 'images/backup.jpg' por tu imagen de menos de 200KB, y la imagen 'images/heavyImage.gif' por tu fichero de más de 200Kb. Si cambias el nombre de la imagen pesada o si esta no tiene extensión GIF, tendrás que actualizar la ruta en el fichero 'index.html' por la nueva ruta a tu imagen.


```html
<img src="images/heavyImage.gif" alt="Heavy Image">
```

Cuando tengas terminada la creatividad, sube la pieza a la plataforma. En este caso, el formato que debes seleccionar en la plataforma es **HTML5 POLITE BANNER**. ¿No tienes claro cómo? Puedes seguir esta pequeña guia [Subir Creatividades Sizmek](http://www.sizmek.es/wiki/subir-creatividades-html5/).

Una vez configurado el formato deberia quedar como en este ejemplo:

![Ejemplo Image Ad Polite](http://www.sizmek.es/eb/users/javiegido_/__GithubImages/HTML5_Image_Ad_Setup.png)

Recuerda que si tienes cualquier duda puedes ponerte en contacto con el equipo de <a href="mailto:creativesupport-spain@sizmek.com">Soporte Creativo de Sizmek</a>

*** 