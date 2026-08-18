# Post-contenido — Unidad 1: Fundamentos de la Web

## Descripción

Repositorio del laboratorio de la Unidad 1 de Programación Web — Séptimo Semestre. Contiene dos partes: configuración del entorno de desarrollo (`parte-1-entorno/`) y análisis de peticiones HTTP con Chrome DevTools y Postman (`parte-2-analisis-http/`).

## Parte 1 — Entorno de desarrollo

Página HTML básica inspeccionada con Chrome DevTools. Ver `parte-1-entorno/`.

## Parte 2 — Análisis de peticiones HTTP

| # | Tipo | URL | Código |
|---|------|-----|--------|
| 1 | GET HTML | https://example.com | 200 OK |
| 2 | GET JSON (exitoso) | /posts/1 | 200 OK |
| 3 | GET JSON (fallido) | /posts/999 | 404 Not Found |
| 4 | POST JSON | /posts | 201 Created |

Ver `parte-2-analisis-http/analisis/`.

## Herramientas utilizadas

- VS Code, Git, GitHub
- Google Chrome + DevTools (panel Network)
- Postman (petición POST con tests)

## Conclusiones

Durante el laboratorio se comprendieron los conceptos fundamentales de las peticiones HTTP y la diferencia entre una página HTML y una API REST. Se analizaron peticiones GET exitosas y fallidas mediante Chrome DevTools, identificando métodos, códigos de estado, headers y tipos de contenido. También se realizó una petición POST con Postman utilizando JSON y se verificó su respuesta mediante tests automatizados. Finalmente, se comprendió la importancia de los códigos HTTP 200, 201 y 404 para interpretar correctamente el resultado de una petición.