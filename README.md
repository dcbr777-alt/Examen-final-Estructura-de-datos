# Árbol AVL Interactivo

**Examen Final – Estructuras de Datos**  
**Leonel David Cabrera Esquivel — Carné: 20252578011**  
**Universidad Distrital Francisco José de Caldas**

---

## ¿Que es el programa?

Es una aplicación web que visualiza un Árbol AVL con animaciones. Los nodos se ven como personajes que caminan hasta su posición en el árbol. Hecha en HTML + JavaScript puro, no necesita instalar nada.

---

## Cómo ejecutarlo

1. Descargar o clonar el repositorio
2. Abrir el archivo `index.html` en el navegador (Chrome o Firefox)
3. Listo, no hay que instalar nada


## Qué funciona

- Insertar, eliminar y buscar nodos con animación
- Cada nodo muestra su valor, altura (h) y factor de equilibrio (FE)
- Balanceo automático o paso a paso (con pausa y control de velocidad)
- Slider para ajustar la velocidad (desde muy lenta hasta rápida)
- Botón para cargar la secuencia personalizada #12
- Generador de árbol aleatorio (entre 5 y 20 nodos)
- Exportar a PNG, PDF e imprimir
- Panel de log que registra todo lo que pasa

---

## Secuencia personalizada #12

```
52 → 32 → 82 → 22 → 42 → 72 → 92 → 40 → 41 → 39 → 38 → 43
```

---

## Video

▶ [Ver en YouTube](#) https://youtu.be/VZdcraS6F5o

---

## Archivos del proyecto

```
index.html                        ← toda la aplicación
README.md                         ← este archivo
Autoevaluacion_LeonelCabrera.pdf  ← tabla de autoevaluación
```

---

*La única dependencia externa es jsPDF (solo para exportar PDF), se carga automáticamente desde internet cuando se usa esa función.*
