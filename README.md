# Laboratorio 1 · API Gateway local (Spring Cloud Gateway)

Estructura lista para iniciar. Sigue la guía completa aquí:
https://github.com/cmartinezs/DSY1107-DESARROLLO-CLOUD-NATIVE-I-2026-2/blob/master/semanas/semana-01/laboratorio-api-gateway/README.md

## Arranque rápido

```bash
cd gateway
mvn spring-boot:run
```

Prueba:

```bash
curl -i http://localhost:8080/api/v1/posts/1
```

## Cliente CORS

Sirve `client/index.html` con Live Server (VS Code) en el puerto 5500,
o con cualquier servidor estático:

```bash
cd client
python3 -m http.server 5500
```

Luego abre: http://localhost:5500
