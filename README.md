```bash
docker run --name nginx -p 80:80 --hostname ng1 -d nginx
```
```bash
docker run --name nginx -p 80:80 --hostname ng1 -v /home/dev/code/nginx/html:/usr/share/nginx/html -d nginx
```
