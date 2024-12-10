## Entorno para administrar un DNS via web

Hai 3 contedores:
- Servidor web
- Administrador web
- Cliente con utilidades para resolver os nomes (dig, host e nslookup)

Executar `docker compose up -d`

Conectarse co navegador web a http://localhost:9191/
A continuación crear un usuario e loguearse con el.  Desde ese momento pódense crear zonas e dominios novos.

Hai que ter coidado, porque admite calquera tipo de dato no campo de valores.

