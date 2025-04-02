# 🐘 Symfony Docker Images

Images Docker personnalisées pour exécuter des projets Symfony en environnement PHP/Nginx, hébergées sur GitHub Container Registry (GHCR).

## 📦 Images disponibles

| Service | Image GHCR                                                              | Description                          |
|---------|-------------------------------------------------------------------------|--------------------------------------|
| PHP     | `ghcr.io/gauthierauge/php-symfony`                                     | PHP 8.x + Composer + extensions Symfony |
| Nginx   | `ghcr.io/gauthierauge/nginx-symfony`                                   | Nginx configuré pour Symfony         |

---

## 🏷️ Tags disponibles

### PHP

- `ghcr.io/gauthierauge/php-symfony:1.0.0` → version stable
- `ghcr.io/gauthierauge/php-symfony:1.0` → dernière mineure de la série 1.x
- `ghcr.io/gauthierauge/php-symfony:latest` → dernière version buildée

### Nginx

- `ghcr.io/gauthierauge/nginx-symfony:1.0.0`
- `ghcr.io/gauthierauge/nginx-symfony:1.0`
- `ghcr.io/gauthierauge/nginx-symfony:latest`

---

## 🚀 Utilisation avec Docker

```bash
docker pull ghcr.io/gauthierauge/php-symfony:1.0.0
docker pull ghcr.io/gauthierauge/nginx-symfony:1.0.0