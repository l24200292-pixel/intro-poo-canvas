# 2.1 Creación de clases para gráficos 2D 🎨

Este repositorio contiene la actividad práctica sobre el uso de la **Programación Orientada a Objetos (POO)** aplicada a entornos gráficos en 2D utilizando el API Canvas de HTML5.

## 📌 Objetivo
Comprender y aplicar los pilares de la POO (encapsulamiento y abstracción) para la manipulación de escenarios gráficos, gestionando múltiples objetos de forma eficiente.

## 🚀 Características del Proyecto
La aplicación web se divide en tres secciones interactivas que demuestran el control de objetos:

1.  **Objeto 2D estático:** Instancia única de la clase `Circle` con parámetros fijos.
2.  **Objeto Aleatorio:** Generación de un círculo con posición ($x, y$) y radio aleatorios, validando que se mantenga dentro de los límites del lienzo.
3.  **Múltiples Objetos (Detección de Colisiones):** Arreglo de 10 objetos que utilizan una función de validación de distancia para evitar que los círculos se encimen al ser creados.

## 🛠️ Tecnologías Utilizadas
* **HTML5 & Canvas API** - Estructura y renderizado gráfico.
* **JavaScript (ES6)** - Lógica de Programación Orientada a Objetos.
* **Bootstrap 5** - Diseño responsivo de la interfaz.
* **Git & GitHub** - Control de versiones y despliegue (GitHub Pages).

## 📂 Estructura de Archivos
```text
intro-poo-canvas/
├── index.html        # Interfaz de usuario y estructura del Canvas
├── README.md         # Documentación del proyecto
└── assests/
    ├── img/          # Recursos visuales (favicon)
    └── js/
        └── main.js   # Lógica de la clase Circle y algoritmos de dibujo
