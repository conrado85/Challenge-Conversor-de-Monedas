# 💱 Conversor de Moneda - Challenge Alura Latam

![Portada del proyecto](https://i.imgur.com/e4HoxE1.png) <!-- Podés cambiar esta URL por una imagen propia del proyecto -->

![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)
![Java](https://img.shields.io/badge/Java-21-blue)
![API](https://img.shields.io/badge/API-ExchangeRate--API-purple)
![License](https://img.shields.io/github/license/tu-usuario/tu-repo)

---

## 🧭 Índice

- [📌 Descripción del Proyecto](#-descripción-del-proyecto)
- [🚧 Estado del Proyecto](#-estado-del-proyecto)
- [✨ Demostración de funciones](#-demostración-de-funciones)
- [🛠️ Tecnologías utilizadas](#-tecnologias-utilizadas-)
- [👨‍💻 Desarrollador](#-desarrollador-)
- [🚀 Instrucciones de uso](#-instrucciones-de-uso)

---

## 📌 Descripción del Proyecto

El **Conversor de Moneda** es una aplicación de consola escrita en Java, que permite realizar conversiones en tiempo real entre diferentes monedas del mundo. Utiliza la **ExchangeRate-API** para obtener las tasas de cambio más recientes.

Este proyecto forma parte del **challenge de Alura Latam**, enfocado en prácticas de consumo de API REST, modularización de código y uso seguro de claves mediante archivos `.env`.


### Calculos.java

Esta clase es responsable de manejar la lógica relacionada con las conversiones de moneda. Aquí se definen métodos para almacenar valores de moneda, realizar conversiones y obtener mensajes de respuesta.

### ConsultasDeConversion.java

Clase responsable de realizar consultas a una API externa para obtener las tasas de cambio entre diferentes monedas.

### GeneradorDeArchivos.java

Esta clase se encarga de guardar el historial de consultas en un archivo de texto.

### Principal.java

El punto de entrada principal del programa. Aquí se maneja la interacción con el usuario a través de la consola, mostrando un menú de opciones y gestionando las conversiones de moneda.

---

## 🚧 Estado del Proyecto

✅ Proyecto iniciado  
🚧 Funcionalidad básica implementada  
🔐 Integración con `.env` para ocultar API Key  
📦 En proceso de mejoras en modularización y posibles futuras interfaces gráficas

---

## ✨ Demostración de funciones

```bash
               ***************************************************
                ***  Bienvenido al Conversor de Monedas ***
                
                (1) Pesos Argentinos ==>> Dólar Estadounidense
                (2) Peso Argentinos ==>> Euro
                (3) Peso Argentinos ==>> Libra Esterlina
                (4) Dólar Estadounidense ==>> Pesos Argentinos
                (5) Euro ==>> Peso Argentinos
                (6) Libra Esterlina ==>> Peso Argentinos
                
                (7) Otra opción de conversión
                
                (8) Salir
                ***************************************************
```               
---

## 🛠️ Tecnologias utilizadas 


- **Lenguaje de Programación:** Java
- **API de Tasas de Cambio:** Se utilizó una API de tasas de cambio en tiempo real para obtener las tasas de conversión entre diferentes divisas.
- **Biblioteca Gson:** Gson se empleó para analizar la respuesta JSON de la API y convertirla en objetos Java para su manipulación.
- **Control de Versiones:** Git/GitHub se usaron para el control de versiones del proyecto y la colaboración en equipo.
- **Entorno de Desarrollo Integrado (IDE):** IntelliJ IDEA fue el entorno de desarrollo utilizado para escribir, depurar y ejecutar el código Java.

---

## 👨‍💻 Desarrollador 

Conrado Carlos Alberto , Gonzalez

---
## 🚀 Instrucciones de uso

1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en IntelliJ IDEA u otro IDE de tu elección.
3. Ejecuta la clase Principal.java para iniciar el programa.
4. Sigue las instrucciones en pantalla para realizar conversiones de moneda.

¡Disfruta convirtiendo monedas!