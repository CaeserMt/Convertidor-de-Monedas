# Proyecto Final del Programa ONE

## Descripción
Este repositorio contiene la solución al desafío propuesto por la empresa, desarrollado como parte del programa ONE (Oracle Next Education). El objetivo es demostrar las habilidades técnicas y de resolución de problemas adquiridas durante el programa.

## Autor
**Cesar Raul Morales Ticona**  
Estudiante de Ingeniería de Sistemas e Informática con especialización en seguridad. Apasionado por la implementación de soluciones tecnológicas innovadoras para la seguridad y el desarrollo de sistemas eficientes.

## Tecnologías Utilizadas
- **Lenguaje de Programación**: Java
- **Herramientas y Librerías**:
  - Gson para manejo de JSON
  - Java HTTP Client para solicitudes HTTP
- **Plataforma**: Programa ONE de Alura y Oracle

## Propósito
El desafío consiste en crear una aplicación funcional que permita convertir monedas utilizando datos en tiempo real de una API de tasas de cambio. Esto incluye:
- Crear un menú interactivo para el usuario.
- Integrar una API para obtener las tasas de conversión de monedas.
- Implementar un diseño modular que facilite la escalabilidad y el mantenimiento.

## Funcionalidades Principales
1. Conversión de moneda entre diferentes divisas:
   - Dólar estadounidense (USD) a Peso argentino (ARS), Real brasileño (BRL), y Peso colombiano (COP).
   - Conversión inversa desde ARS, BRL, y COP a USD.
2. Validación de opciones ingresadas por el usuario.
3. Manejo de errores en caso de fallos en la conexión a la API.

## Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

```
|-- src
|   |-- ExchangeRateClient.java  // Clase principal con el menú interactivo
|   |-- ApiService.java          // Clase para manejar solicitudes a la API
|   |-- ConversionHandler.java   // Clase para realizar los cálculos de conversión
|-- README.md                    // Documentación del proyecto
```

## Requisitos
- **Java Development Kit (JDK)**: Versión 11 o superior
- **Conexión a Internet** para acceder a la API de tasas de cambio

## Ejecución del Proyecto
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tuusuario/nombre-del-repositorio.git
   ```
2. Navegar al directorio del proyecto:
   ```bash
   cd nombre-del-repositorio
   ```
3. Compilar el código:
   ```bash
   javac src/*.java
   ```
4. Ejecutar el programa:
   ```bash
   java src.ExchangeRateClient
   ```

## API Utilizada
- **ExchangeRate API**: [https://www.exchangerate-api.com](https://www.exchangerate-api.com)

## Ejemplo de Uso
- Al ejecutar el programa, el usuario verá un menú interactivo que permite seleccionar la conversión deseada.
- Ingrese la cantidad a convertir y obtenga el resultado en tiempo real.

### Salida Esperada
```
Bienvenido al Conversor de Moneda
Elija una opción válida:
1. Dólar a Peso Argentino
2. Peso Argentino a Dólar
3. Dólar a Real Brasileño
4. Real Brasileño a Dólar
5. Dólar a Peso Colombiano
6. Peso Colombiano a Dólar
7. Salir
Opcion: 1
Ingrese la cantidad en USD: 100
100 USD = 23,456 ARS
```

## Contribuciones
Este proyecto fue desarrollado como parte de un desafío personal. Si deseas contribuir, no dudes en enviar un pull request o abrir un issue.

## Licencia
Este proyecto está bajo la Licencia MIT. Puedes ver el archivo LICENSE para más detalles.

## Contacto
**Cesar Raul Morales Ticona**  
[LinkedIn](https://www.linkedin.com/in/cesar-raul-morales-ticona)  

