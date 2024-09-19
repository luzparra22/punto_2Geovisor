# Geovisor con Filtro de Fechas y Tabla de Datos

## Descripción

Este proyecto crea un geovisor que permite visualizar un mapa, aplicar filtros de fecha y hora a los datos de una capa de características, y mostrar los resultados en una tabla. Utiliza la API de ArcGIS para JavaScript para la integración de mapas y la filtración de datos.

## Dependencias

Para ejecutar este proyecto, asegúrate de tener las siguientes dependencias instaladas:

- **Node.js**: Asegúrate de tener Node.js instalado en tu sistema. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).

## Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/luzparra22/geovisor_prueba
   ```
## Herramientas Utilizadas

### 1. **ArcGIS API for JavaScript**

- **Descripción**: La API de ArcGIS para JavaScript es una biblioteca de JavaScript que facilita la creación de aplicaciones web interactivas con mapas y análisis espacial. Permite la integración de mapas, la visualización de datos geoespaciales y la realización de consultas.
- **Componentes Utilizados**:
  - `Map`: Crea y maneja el mapa en la aplicación.
  - `MapView`: Proporciona una vista del mapa y controla la interacción del usuario con él.
  - `FeatureLayer`: Agrega una capa de características al mapa, permitiendo la visualización y consulta de datos espaciales.

  - **Documentación**: [ArcGIS API for JavaScript Documentation](https://developers.arcgis.com/javascript/latest/)

### 2. **HTML**

- **Descripción**: HTML (HyperText Markup Language) es el lenguaje de marcado utilizado para estructurar el contenido de las páginas web. En este proyecto, HTML se utiliza para definir la estructura del formulario de filtros, la tabla de resultados y la vista del mapa.

  - **Documentación**: [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)

### 3. **CSS**

- **Descripción**: CSS (Cascading Style Sheets) se utiliza para definir la presentación y el diseño visual del contenido HTML. En este proyecto, CSS se usa para estilizar la disposición del banner, los paneles, el mapa y la tabla.

- **Componentes Utilizados**:
  - `flexbox`: Utilizado para crear una disposición flexible y adaptativa del contenido, como el diseño del banner, los paneles laterales y el mapa.
  - `box-shadow`: Añadido para crear efectos de sombra en los elementos y darles una apariencia elevada.
  - `border-radius`: Aplicado para redondear las esquinas de los elementos y darles un diseño más suave.
  - `overflow-y: auto`: Habilita el desplazamiento vertical en los paneles y la tabla para manejar el contenido que excede el tamaño visible.
  - `@media queries`: Se utilizan para hacer que el diseño sea responsivo, adaptándose a diferentes tamaños de pantalla y dispositivos.

  - **Documentación**: [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)

### 4. **JavaScript**

- **Descripción**: JavaScript es un lenguaje de programación que permite la implementación de lógica en la web. En este proyecto, JavaScript se utiliza para manejar la lógica de filtrado de datos en el mapa y la actualización dinámica de la tabla basada en los filtros aplicados.
- **Librerías y Métodos Utilizados**:
  - `querySelector`: Para seleccionar elementos del DOM.
  - `addEventListener`: Para manejar eventos, como clics en botones y cambios en campos de entrada.
  - `FeatureLayer.createQuery()`: Para crear consultas sobre la capa de características.
  - `FeatureLayer.queryFeatures()`: Para realizar consultas y obtener los datos filtrados.

  - **Documentación**: [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Implementación en Local

Para ejecutar el geovisor en tu entorno local, sigue estos pasos:

### 1. **Clonar el Repositorio**

Si aún no lo has hecho, clona el repositorio desde GitHub a tu máquina local utilizando el siguiente comando en tu terminal:

```bash
git https://github.com/luzparra22/geovisor_prueba
```

### 2. Preparar Archivos
Verifica que todos los archivos necesarios estén presentes en las carpetas adecuadas. La estructura típica del proyecto debería ser:

 - HTML: `index.html` en la carpeta public.
 - CSS: `styles.css` en la carpeta public.
 - JavaScript: `app.js` en la carpeta src.
Asegúrate de que los archivos estén en las ubicaciones correctas y que las rutas en el HTML apunten a los archivos de JavaScript y CSS adecuados.

### 3. Configurar el Entorno
No es necesario realizar configuraciones adicionales en el entorno local para el proyecto, ya que no se utilizan herramientas de construcción o empaquetado. Simplemente asegúrate de que la API de ArcGIS se carga correctamente desde el CDN.


### 4. Ejecutar un Servidor Local
Para visualizar el geovisor, puedes usar un servidor local o abrir el archivo HTML directamente en tu navegador.

```bash
http-server
```
Esto iniciará un servidor en `http://localhost:8080`  (o un puerto similar) donde podrás ver el geovisor

### 5.  Verificar el Funcionamiento

Navega a la carpeta que contiene tu archivo `index.html`. Abre el archivo en tu navegador web o arrástralo a una ventana del navegador. Verifica que el mapa y los elementos de la interfaz se carguen correctamente y que los filtros funcionen como se espera.





