# Laboratorio de IA: apuntes que se tocan

Una página web interactiva para entender cómo funciona el aprendizaje automático **moviendo los controles en lugar de leer fórmulas**. Pensada para quien trabaja con datos, seguridad o comunicación y necesita criterio, no solo definiciones.

**▶ Demo:** `https://TU-USUARIO.github.io/laboratorio-ia/`

> Un solo archivo HTML. Sin instalación, sin servidor, sin cuentas, sin rastreo. Todos los datos de las demos son simulados.

---

## Por qué existe

Casi todo el material sobre IA se queda en dos extremos: o es una charla conceptual que no se puede comprobar, o es código que exige montar un entorno antes de aprender nada. Este laboratorio busca un punto intermedio: cada idea tiene una demo pequeña que puedes romper y observar. Si entiendes *por qué* un modelo falla, sabes cuándo no fiarte de él.

Es un proyecto de **[Bermuda Comunica](https://github.com/TU-USUARIO)** para explicar de forma práctica la teoría de la integridad digital: que los sistemas que toman decisiones con datos sean comprensibles, verificables y honestos sobre sus límites.

## Qué contiene

| Pestaña | Idea que se toca |
|---|---|
| **El mapa** | IA, ML, DL e IA generativa como círculos anidados. Reglas escritas a mano frente a reglas aprendidas. Datos (X), respuesta (Y) y modelo (F). |
| **El proyecto es un círculo** | El ciclo de vida de un modelo y por qué envejece cuando el mundo cambia. Formas de aprender, tipos de modelo y niveles de uso de los datos. |
| **Generalizar** | Subajuste, equilibrio y sobreajuste en un gráfico manipulable. |
| **Umbral y tasa base** | Matriz de confusión y la trampa de la tasa base: un modelo "preciso" puede ser inútil si lo que buscas es raro. |
| **Laboratorio 1** | Regla hecha a mano contra regla aprendida a partir de ejemplos. |
| **Preparar los datos** | Limpieza, texto a números, número Z y escalado, creación de pistas desde un log de acceso y cuatro formas de dividir datos (aleatoria, temporal, por grupos y estratificada) con detección de fuga. |

## Principios de diseño

Estos son los criterios que se han seguido al construirlo. Si los cambias, que sea a propósito.

1. **Aprender haciendo.** Cada concepto tiene un control que se puede mover. Si no se puede tocar, es texto breve.
2. **Datos simulados, siempre.** Nada de datos personales ni de sistemas reales. Se puede experimentar sin riesgo.
3. **Enseñar los fallos, no solo los aciertos.** Hay pestañas dedicadas a sobreajuste, tasa base, fuga de datos y deriva del modelo.
4. **Transparencia sobre los límites.** Un modelo se documenta con lo que vio, lo que no cubre y cuándo falla.
5. **Ética explícita.** Público no significa libre (licencia y consentimiento) y los ataques solo se practican en entornos de prueba con autorización.
6. **Accesible y ligero.** Funciona sin conexión salvo por la tipografía, respeta el modo oscuro y `prefers-reduced-motion`, es navegable con teclado y los gráficos llevan etiqueta ARIA.
7. **Cero dependencias.** HTML, CSS y JavaScript sin librerías. Se puede leer entero en una tarde.

## Cómo usarlo

**En local:** descarga `index.html` y ábrelo en el navegador. Ya está.

**Clonando el repositorio:**

```bash
git clone https://github.com/TU-USUARIO/laboratorio-ia.git
cd laboratorio-ia
# abre index.html en tu navegador
```

## Estructura

```
laboratorio-ia/
├── index.html    # toda la aplicación (HTML + CSS + JS)
├── README.md
├── LICENSE
├── .gitignore
└── .nojekyll     # evita que GitHub Pages procese el sitio con Jekyll
```

## Privacidad

La página no usa cookies, analítica ni peticiones a servidores propios. La única petición externa es la de **Google Fonts** (Sora e IBM Plex Sans). Si quieres eliminarla por completo, descarga las fuentes, aloja los archivos en el repositorio y sustituye el `<link>` de la cabecera; el diseño tiene tipografías de respaldo y funciona igual.

## Limitaciones

- Es material didáctico: los modelos de las demos son deliberadamente simples y los datos, sintéticos. No sirve para tomar decisiones reales.
- Los resultados de las demos son ilustrativos y no representan el rendimiento de ningún sistema en producción.

## Contribuir

Las sugerencias son bienvenidas: abre un *issue* si encuentras un error conceptual, una explicación confusa o un problema de accesibilidad. Para cambios de contenido, un *pull request* pequeño y con una sola idea es lo más fácil de revisar.

## Licencia

[MIT](LICENSE) © 2026 Bermuda Comunica. Puedes usarlo, adaptarlo y compartirlo citando la autoría.

## Contacto

Bermuda Comunica · [LinkedIn](https://www.linkedin.com/) · TU-EMAIL
