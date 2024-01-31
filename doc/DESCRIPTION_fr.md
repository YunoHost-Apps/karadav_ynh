Un serveur WebDAV simple et léger, permettant de mettre en place facilement un serveur de partage de fichiers compatible avec les clients WebDAV et NextCloud. Il n'a pas de dépendances et a de bonnes performances.

Il est écrit en PHP (8+). La seule dépendance est SQLite3 pour la base de données.

Si vous cherchez un server WebDAV encore plus léger, vous pouvez essayer [PicoDAV](https://github.com/kd2org/picodav/). Il n'est pas compatible avec les clients NextCloud/ownCloud, mais c'est un simple fichier que vous pouvez juste mettre dans votre dossier de données, rien à installer!
Vous pouvez l'installer facilement en utilisant [my_webapp_ynh](https://apps.yunohost.org/app/my_webapp).

### Bugs connus

- [les apps iOS NextCloud et ownCloud ne fonctionnent pas, les autres apps WebDAV devraient fonctionner](https://github.com/kd2org/karadav/issues/22) (bug upstream)
