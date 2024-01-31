This is a simple and lightweight WebDAV server, allowing to easily set up a file sharing server compatible with WebDAV and NextCloud clients. It has no dependencies and good performance.

It is written in PHP (8+). The only dependency is SQLite3 for the database.

If you are looking for an even lighter WebDAV server, try [PicoDAV](https://github.com/kd2org/picodav/). It isn't compatible with NextCloud/ownCloud clients, but it is a single file that you can drop anywhere in your document root, nothing to install!  
You can easily install it using [my_webapp_ynh](https://apps.yunohost.org/app/my_webapp).

### Known issues

- [iOS NextCloud and ownCloud apps don't work, any other WebDAV app should work](https://github.com/kd2org/karadav/issues/22) (upstream bug)
