---
layout: default
title: Portafolio | Leslie Carolina Páez Balderas
---

# Leslie Carolina Páez Balderas  
**Junior Data Analyst | SQL • Tableau • Python • Excel**  

<div style="text-align:center; margin: 18px 0 10px 0;">
  <img 
    src="/portafolio/assets/foto_perfil.png" 
    alt="Foto de perfil - Leslie Carolina Páez Balderas"
    style="width:160px; height:160px; object-fit:cover; border-radius:50%; border: 3px solid rgba(0,0,0,0.08);"
  />
</div>

[LinkedIn](https://www.linkedin.com/in/leslie-carolina-paez-balderas/) · [Tableau Public](https://public.tableau.com/app/profile/leslie.p.ez/vizzes) · [Email](mailto:leslie.pabal6@gmail.com)

---

## Sobre mí
En la licenciatura aprendí que toda obra literaria tiene una estructura; en el análisis de datos descubrí que esa estructura también revela patrones y decisiones estratégicas.

Soy **Data Analyst Junior en transición hacia el análisis de datos**, proceso que comenzó durante mi **Maestría en Administración**, donde identifiqué el valor del análisis de información en la toma de decisiones empresariales. Trabajo con **SQL, Tableau, Python y Excel** para limpiar datos, analizar desempeño y comunicar insights con dashboards claros y visualmente atractivos.

Me interesa desarrollarme en **Business Intelligence, análisis comercial y calidad de datos** dentro de corporativos grandes y multinacionales (incluyendo farmaceúticas).  
📩 Estoy abierta a oportunidades, conectar y aprender cosas nuevas.

---

## Habilidades técnicas
- **SQL:** joins, agregaciones, filtros, análisis exploratorio
- **Tableau:** dashboards, filtros, data storytelling
- **Python:** limpieza, EDA, visualización (Pandas, NumPy, Matplotlib)
- **Excel:** tablas dinámicas, validación/limpieza, dashboards

## Habilidades blandas
Análisis de datos | Manipulación de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle 

---

## Proyectos destacados

### 1) Ventas globales — Dashboard (Tableau)
**Objetivo:** explorar ventas globales y comunicar insights con un dashboard interactivo.  
**Qué hice:**
- Diseñé visualizaciones, filtros y métricas para analizar tendencias por país/región/periodo/tipo de producto.
- Apliqué data storytelling para destacar hallazgos de negocio.

**Herramientas:** Tableau Public  
**Ver dashboard:** [Tableau Public – Ventas globales](https://public.tableau.com/app/profile/leslie.p.ez/viz/EntregaFinalPez/Nubepalabras)

---

### 2) Tienda Ice (Videojuegos) — Perfil de usuario por región + pruebas de hipótesis
**Objetivo:** construir un perfil de usuario por región y validar hipótesis para apoyar decisiones de marketing/contenido.  
**Qué hice:**
- Limpieza/estandarización y análisis por región (plataformas, géneros y rating ESRB).
- Pruebas de hipótesis sobre calificaciones de usuarios por plataforma y género.

**Herramientas:** Python (Pandas, Matplotlib), estadística (pruebas de hipótesis), Jupyter  

**Visualizaciones:**
1. **Ventas por plataforma:**
   Las ventas se encuentran altamente concentradas en pocas plataformas, mientras que el resto forma una “cola larga” con participación menor. Esto indica que gran parte del desempeño depende de un grupo reducido de consolas/plataformas principales, lo cual ayuda a definir prioridades: enfocar lanzamientos, presupuesto o inventario en las plataformas top para maximizar impacto, y dejar el resto para tácticas más específicas o de nicho.
![Ventas por plataforma](/portafolio/assets/tienda_ice_ventas_vs_plataforma.png)

2. **Comparación de género por región:**
   Se observa que Action domina claramente en Norteamérica y Europa, lo que lo convierte en el género más “seguro” para alcance y ventas en esos mercados. En Japón destaca con más fuerza Role-playing, reforzando la idea de que el mix de géneros debe adaptarse por región. Este contraste es útil para orientar campañas: priorizar títulos de acción en NA/EU y fortalecer RPG en JP con mensajes y selección de juegos alineados a la preferencia local.
![Comparación de género por región](/portafolio/assets/tienda_ice_comparacion_genero_vs_region.png)

**Hallazgos clave:**
- **Norteamérica:** X360 + Action + Rating **E**  
- **Europa:** PS3 + Action + Rating **E**  
- **Japón:** DS + Role-playing + Rating **E**
- Diferencia en calificaciones promedio **Xbox One vs PC**; sin evidencia suficiente para diferencia **Action vs Sports**.

**Entregables:**
- ✅ [Reporte HTML](projects/tienda_ice/tienda_ice_report.html)  
- ✅ [Notebook (Jupyter)](projects/tienda_ice/tienda_ice_public.ipynb)

---

### 3) Instacart — Hábitos de compra (Python / EDA)
**Objetivo:** limpiar un dataset modificado y analizar hábitos de compra (horarios, días, reorden y productos top).  
**Qué hice:**
- Limpieza: tipos, ausentes, duplicados y validación de rangos.
- EDA + visualizaciones para responder preguntas de negocio sobre comportamiento y reorden.

**Herramientas:** Python (Pandas, Matplotlib), Jupyter  

**Visualizaciones:**
1. **Número de pedidos por hora en los días Miércoles y Sábado:**
   El comportamiento horario muestra que los pedidos se concentran desde la mañana hacia la tarde, con una actividad fuerte en horas pico de media mañana/mediodía. El sábado tiende a concentrar mayor intensidad en los picos (posible compra más planificada o mayor disponibilidad de tiempo), mientras que el miércoles luce más estable. Esto sugiere ventanas claras para activaciones comerciales: promociones, notificaciones o campañas de conversión pueden rendir mejor en la franja de mañana a tarde, especialmente durante fin de semana.
![Pedidos por hora: Miércoles vs Sábado](/portafolio/assets/instacart_pedidos_hora_miercoles_vs_sabado.png)

2. **Top 10 primero artículos agregados al carrito:**
   El top de “primer artículo agregado al carrito” está dominado por productos básicos y recurrentes (como banana), lo que sugiere que muchos usuarios inician sus compras con artículos “ancla” antes de completar el resto del carrito. Este patrón es valioso para optimizar la experiencia y aumentar conversión: esos productos pueden usarse como punto de entrada para recomendaciones personalizadas, bundles y estrategias de “comprar de nuevo” desde el primer paso del proceso de compra.
![Top 10 primer artículo agregado al carrito](/portafolio/assets/instacart_top10_primer_item.png)

**Hallazgos clave:**
- Mayor actividad entre **9:00–17:00** (pico **10:00**).
- Más compras: **domingo y lunes**; menos: **jueves**.
- Producto #1: **banana** (**66,050** compras).

**Entregables:**
- ✅ [Reporte HTML](projects/instacart/instacart_report.html)  
- ✅ [Notebook (Jupyter)](projects/instacart/instacart_public.ipynb)

---

## Contacto
📩 **Email:** leslie.pabal6@gmail.com  
🔗 **LinkedIn:** (https://www.linkedin.com/in/leslie-carolina-paez-balderas/)

_Última actualización: Feb 2026_
