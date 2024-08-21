# Proyecto Final Frontend: Slack Clone

## Descripción

En este proyecto, desarrollé una aplicación de chat inspirada en Slack, implementando características similares a las de la aplicación original. 
Abordé el proyecto desde un enfoque de "cambio de identidad visual" utilizando Behance y Figma para buscar un nuevo logo y una paleta de colores.

## Tecnologías y Librerías Utilizadas

- **React**
- **React Router DOM**
- **Google Fonts**
- **Bootstrap Icons**

## Funcionalidades

- **Almacenamiento de datos en `localStorage` desde el inicio del proyecto.**

- **Creación de nuevos espacios de trabajo y canales.**

**Barra de búsqueda que filtra por contenido y autor del mensaje**

**Navegación a través de los entornos y canales**

**Envío de nuevos mensajes con auto-scroll hacia abajo:** 

## Desafíos y Soluciones

**Manejo de Estado y Contexto:**
- Uso de `useContext` para mantener la consistencia y facilitar la comunicación entre componentes.

**Validación de Formularios:** 
- Desarrollo de funciones de validación generales en el archivo `validationHelpers` para reutilizar en ambos formularios de creación de nuevos espacios de trabajo y canales.

**Diseño Responsivo:** 
- Medidas de responsividad: de 320 a 2000px.
- Implementación de menú desplegable para pantallas más pequeñas.

- **Implementación del Auto-Scroll con useRef:** Para lograrlo tuve que investigar y aprender a usar `useRef`. Consulté recursos en Medium.com y YouTube para entender como implementar esta técnica correctamente, lo cual fue un gran desafío.

## Diseño 

Para el diseño, me inspiré en el concepto de identidad visual de Slack que encontré en Behance.

**Paleta de colores y tonalidades:** 
- Definida utilizando Coolors y Figma.

![Paleta de Colores](public/assets/images/paleta-colores.png)


**Logo:** 
- Adaptado del concepto visual encontrado en [Behance](https://www.behance.net/gallery/75131405/Slack-Visual-Identity-Concept) de Oleg Turbaba.

## Conclusión

Este proyecto fue desafiante y entretenido a la vez. Hubo momentos de frustación pero estoy muy contenta con el resultado. Fue una excelente oportunidad para poner en práctica los conocimientos adquiridos en las clases de FrontEnd y aprender nuevas técnicas.
Me gustaría seguir trabajando en este proyecto para agregar más funcionalidades y mejorar la experiencia del usuario.