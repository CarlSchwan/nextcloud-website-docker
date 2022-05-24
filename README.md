## Wordpress setup with docker

1. `docker compose up`
2. Open http://locahost:8000
3. `git clone git@github.com:nextcloud/nextcloud-theme.git`
4. `sudo mv nextcloud-theme wordpress/wp-content/themes`
5. `sudo chown $USER wordpress/wp-content/themes/nextcloud-theme`