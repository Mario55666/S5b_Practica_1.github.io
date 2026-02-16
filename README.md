# Simulador de Auditoría Perceptiva para Diseño Visual

Este proyecto es una herramienta educativa interactiva desarrollada para la **Semana 5 del curso Semiótica de la Imagen**. Permite a los estudiantes experimentar con los principios de percepción visual mediante la manipulación en tiempo real de las capas de un anuncio publicitario para dispositivos móviles (formato 9:16).

A través de controles intuitivos, los usuarios pueden simular daltonismos, ajustar propiedades visuales de cada capa (desenfoque, opacidad, contraste, escala) y registrar sus conclusiones, todo dentro de una interfaz optimizada para dispositivos táctiles (Android) y navegadores de escritorio.

## 📌 Propósito Educativo

Aplicar de manera autónoma los conocimientos sobre **etapas y tipos de percepción visual**, consolidando el aprendizaje mediante el análisis crítico de piezas visuales y la fundamentación de decisiones de diseño basadas en evidencia perceptiva. La actividad está diseñada para realizarse en equipos de 3 estudiantes, siguiendo la guía de "Auditoría perceptiva de diseños".

## ✨ Características principales

- **Visualización por capas**: El anuncio se compone de 5 capas independientes (fondo, persona, texto, CTA, logo) que pueden manipularse por separado.
- **Controles por capa**: Desenfoque (blur), opacidad, contraste y escala. Cada capa incluye una sugerencia sobre el principio Gestlat asociado.
- **Simuladores de daltonismo**: Filtros para protanopia, deuteranopia, tritanopia y acromatopsia, aplicables a todo el cartel (basados en SVG `feColorMatrix`).
- **Perfil de Osgood interactivo**: Barras deslizables para registrar valoraciones semánticas (polaridades) en 6 dimensiones. Compatible con arrastre por mouse y táctil.
- **Campos de conclusiones**: Áreas de texto para responder las preguntas de la auditoría, junto con identificación del estudiante (nombre y correo).
- **Exportación**: Envío de respuestas por correo electrónico (cliente predeterminado) y simulación de generación de PDF.
- **Diseño responsivo**: Se adapta a pantallas pequeñas (máx. 430px) y grandes, manteniendo la usabilidad táctil.

## 🧱 Estructura del proyecto
