# Docker compose installation guide

1. Download and unpack the archive, go to the unpacked directory.
2. Build images with the following command:

```
docker compose build 
```

3. Generate env\_docker

```
docker run --rm easypon-backend init > .env_docker 
```

4. Start your project

```
docker compose up -d 
```

5. To create an admin user, utilize the login and password from the environment variables specified in the ".env\_docker" file:

```
docker compose exec -ti backend_main bash compose/backend-entry-point.sh create_user
```

### Accessing EasyPon

To access EasyPon, open your browser and navigate to your domain name or IP address of your server. You will be prompted to log in with your credentials, which you received in the terminal during installation, or which can be found in \`/root/.tmp\_ep\_users\`.
