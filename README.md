# Usage

Make sure you have latest docker version installed(>= 27.3.1).

Start server
```bash
docker compose --env-file example.env up -d
```

To get admin user password
```bash
docker exec -it domserver cat /opt/domjudge/domserver/etc/initial_admin_password.secret
```

For more information checkout:
https://hub.docker.com/r/domjudge/domserver/
