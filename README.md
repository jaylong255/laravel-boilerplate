# laravel-boilerplate

```bash
# Install the app
docker-compose up -d

# Don't forget to fix permissions outside of docker
docker-compose down
chmod -R 775 ./laravel/storage
chown -R www-data:www-data ./laravel/storage
sudo chown -R www-data:www-data ./laravel/storage
docker-compose down
docker-compose up -d
```