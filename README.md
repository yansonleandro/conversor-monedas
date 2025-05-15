# Conversor de Monedas en Java 💱

Este es un proyecto simple de consola en Java que permite convertir montos entre distintas monedas utilizando una API de tipo de cambio. El programa permite realizar conversiones predefinidas o ingresar monedas personalizadas.

## 🚀 Características

- Conversión entre monedas como ARS, USD, BRL y COP.
- Opción de ingresar códigos de moneda personalizados.
- Consulta de tasas de conversión en tiempo real.
- Interfaz por consola sencilla.
- Uso de la biblioteca Gson para parsear respuestas JSON.

## 🧱 Estructura del Proyecto

📁 ConversorMonedas/
┣ 📄 Main.java
┣ 📄 ConvertirMoneda.java
┣ 📄 ConsultarMoneda.java
┣ 📄 Monedas.java
┣ 📄 README.md

📋 Uso
Ejecutá la clase Main.

Elegí una opción del menú para seleccionar qué conversión realizar:

Convertir de ARS a USD

Convertir de USD a BRL

...

Opción personalizada para cualquier par de monedas (por código ISO 4217, ej: EUR, GBP)

Ingresá el monto a convertir.

El programa mostrará el resultado en pantalla.

📤 API utilizada
El proyecto utiliza una API REST (por ejemplo, ExchangeRate-API o similar) para obtener las tasas de cambio.
