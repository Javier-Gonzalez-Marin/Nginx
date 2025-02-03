# Nginx


## 1. Introducción

Nginx es un servidor web de alto rendimiento y proxy inverso, ampliamente utilizado por su eficiencia en la gestión de conexiones concurrentes y su baja utilización de recursos. Originalmente desarrollado como solución para el problema C10k (manejo de 10,000 conexiones simultáneas), ha ganado popularidad en aplicaciones web modernas por su capacidad para equilibrar carga, servir contenido estático rápidamente y actuar como proxy para aplicaciones dinámicas.

En la empresa Servicios Web RC, S.A., se ha planteado la migración desde Apache a Nginx con el objetivo de mejorar el rendimiento y la escalabilidad de los servicios ofrecidos.

## 2. [Comparativa con Apache](comparativa_con_apache.md)

## 3. Esquema de red

A continuación, se presenta un esquema básico de red para implementar Nginx como servidor web y proxy inverso:


  - Clientes: Usuarios que acceden al servicio web.

  - Servidor Nginx: Actúa como proxy inverso, distribuyendo las peticiones a los servidores backend.

  - Servidores Backend: Procesan las peticiones dinámicas y generan las respuestas necesarias.

Nginx se posiciona como un punto central en la red, manejando las conexiones y distribuyendo las cargas de manera eficiente para maximizar el rendimiento del sistema.

## 4.[Instalación](Instalación.md)

## 5.[Casos practicos](casos_practicos.md)

## 6.[Referencias](referencias.md)
