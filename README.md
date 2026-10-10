# TripleTen web_project_expenses

# Gestor de Gastos

Aplicación web interactiva para administrar un presupuesto personal, registrar gastos y visualizar estadísticas financieras por categoría. Este proyecto fue desarrollado como parte del aprendizaje de JavaScript, aplicando conceptos fundamentales de programación y manipulación del DOM.

## Descripción del proyecto

El **Gestor de Gastos** permite al usuario establecer un presupuesto, registrar sus gastos y consultar información actualizada sobre sus finanzas. La aplicación calcula automáticamente el total gastado, el promedio por gasto, el saldo disponible y la categoría con mayor consumo.

Además, los datos se almacenan en el navegador mediante `localStorage`, lo que permite conservar la información al recargar la página.

## Funcionalidades

- **Gestión del presupuesto:** establecer y actualizar el presupuesto disponible.
- **Registro de gastos:** agregar gastos seleccionando una categoría e ingresando un importe.
- **Eliminación de gastos:** eliminar registros individuales de la lista.
- **Estadísticas generales:** consultar el total de gastos, el promedio por registro y el saldo restante.
- **Análisis por categorías:** visualizar los gastos correspondientes a comida, comer fuera, transporte, hogar y suscripciones.
- **Categoría con mayor gasto:** identificar automáticamente la categoría que acumula el importe más alto.
- **Indicador visual del saldo:** cambiar el color del saldo según la situación del presupuesto.
- **Persistencia de datos:** conservar el presupuesto y los gastos después de recargar la página.
- **Restablecimiento de datos:** borrar los registros guardados y recuperar los gastos predeterminados.

## Tecnologías utilizadas

- **HTML5:** estructura y organización del contenido.
- **CSS3:** estilos y presentación visual de la interfaz.
- **JavaScript:** lógica de programación, cálculos, eventos e interacción con la página.
- **DOM:** selección y actualización dinámica de elementos HTML.
- **Arreglos y funciones:** organización de los gastos y reutilización de la lógica.
- **`localStorage`:** almacenamiento de datos en el navegador.
- **Git y GitHub:** control de versiones y publicación del código fuente.

## Estructura del proyecto

```text
web_project_expenses_es/
├── blocks/
│   ├── budget.css
│   ├── button.css
│   ├── content.css
│   ├── controls.css
│   ├── expense.css
│   ├── expenses.css
│   ├── footer.css
│   ├── header.css
│   ├── modal.css
│   ├── page.css
│   └── stats.css
├── images/
│   └── delete-icon.svg
├── pages/
│   └── index.css
├── scripts/
│   ├── calculations.js
│   ├── handle-html.js
│   └── index.js
├── vendor/
│   ├── fonts.css
│   ├── normalize.css
│   └── fonts/
├── index.html
└── README.md
```

## Organización del código JavaScript

El código se divide en tres archivos principales:

- **`calculations.js`:** contiene las variables, los datos iniciales y las funciones encargadas de calcular los gastos, el promedio, el saldo, los totales por categoría y la categoría con mayor gasto.
- **`handle-html.js`:** gestiona la interacción con la interfaz, los eventos de los botones, el formulario para agregar gastos, la eliminación de registros y la actualización de las estadísticas.
- **`index.js`:** administra el almacenamiento y la recuperación de información mediante `localStorage`, además de inicializar la lista de gastos y las estadísticas.

Los archivos se cargan en el HTML en el orden necesario para que las funciones y variables estén disponibles cuando se utilizan.

## Cómo ejecutar el proyecto

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Walther77/web_project_expenses_es.git
   ```

2. Entra en la carpeta del proyecto:

   ```bash
   cd web_project_expenses_es
   ```

3. Abre el archivo `index.html` en un navegador web. También puedes utilizar la extensión Live Server de Visual Studio Code para ejecutar la página durante el desarrollo.

## Aprendizajes

Durante el desarrollo de este proyecto se practicaron los siguientes conceptos:

- Declaración y actualización de variables.
- Creación y recorrido de arreglos, incluidos arreglos anidados.
- Definición y llamada de funciones.
- Uso de parámetros, valores de retorno y estructuras condicionales.
- Aplicación de ciclos para procesar información.
- Manipulación del DOM y gestión de eventos.
- Actualización dinámica de elementos HTML.
- Almacenamiento y recuperación de datos en el navegador.
- Uso de Git y GitHub para registrar y publicar cambios.

## Autor

Proyecto desarrollado como parte del proceso de formación en desarrollo web de TripleTen, con el objetivo de fortalecer las habilidades en JavaScript y la creación de aplicaciones web interactivas.
