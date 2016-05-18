# Taller-git-Clase-2

Copia de tut. del john para iniciar un repositorio y clonarlo localmente para documentos de Overleaf:

Primer paso será clonar el respositorio Git de nuestro documento en Overleaf:

(git clone "link url del doc overleaf")

Luego renombramos el origen:

(git remote rename origin overleaf)

Cuando queramos bajar los cambios de Overleaf a nuestro PC usamos:

(git pull overleaf master)

Ahora tenemos que vincular nuestro documentos a Github

(git remote add github "Nombre del repositorio")

Y subimos todo a Github

(git push github)