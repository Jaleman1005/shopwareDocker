- pull: `docker-compose pull`
- init: `docker-compose exec shop /swtools/init.sh`
- refresh plugins: `docker-compose exec shop php bin/console sw:plugin:refresh`
- install plugin: `docker-compose exec shop php bin/console sw:plugin:install SwagPluginName`
- activate plugin: `docker-compose exec shop php bin/console sw:plugin:activate SwagPluginName`
- clear cache: `docker-compose exec shop php bin/console sw:cache:clear`
- reinstall plugin (for development): `docker-compose exec shop php bin/console sw:plugin:reinstall SwagPluginName --clear-cache`
- install demo data: `docker-compose exec shop php bin/console sw:store:download SwagDemoDataEN`