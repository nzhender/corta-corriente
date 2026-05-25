# Control de Corta Corriente

Aplicación web para gestionar el corta corriente de vehículos por patente.

## Demo en vivo

Acceso público (GitHub Pages): _(se completa después de activar Pages)_

## Características

- Ingreso y validación de patente argentina (formato AA123BB o ABC123).
- Indicador de estado en tiempo real (activado / desactivado).
- Botones de Activar / Desactivar con confirmación previa.
- Historial local de las últimas 50 acciones.
- Diseño responsive, optimizado para uso desde móvil.

## Uso

Abrir `index.html` en cualquier navegador moderno. No requiere servidor.

> **Nota:** Esta es una versión demo solo de frontend. Los estados se guardan en el navegador (`localStorage`). Para producción, conectar las funciones `setState` y `addHistory` a una API real.
