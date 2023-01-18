# Wordpress Docker

Deploy Wordpress with docker staticly by injecting the theme and plugins into the image. This method helps for Railway deployment method.

### How to Deploy

#### Railway

1. Add MySQL Database Service

2. Deploy this repo

3. Set environment variable for wordpress service from database service

```
WORDPRESS_DB_HOST
WORDPRESS_DB_USER
WORDPRESS_DB_PASSWORD
WORDPRESS_DB_NAME

# for railway support to expose app
PORT=80
```
