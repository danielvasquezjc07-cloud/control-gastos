# 💰 Libro de Gastos

Aplicación web para registrar y controlar las finanzas personales del día a día: ingresos, gastos, categorías y balance mensual.

🔗 **Demo en vivo:** https://danielvasquezjc07-cloud.github.io/control-gastos

---

## 📋 Descripción

Permite llevar un registro de en qué se gasta el dinero, cuánto ingresó en el mes y cuál es el balance disponible. Funciona completamente en el navegador, sin servidor ni base de datos, y guarda la información de forma local para que no se pierda al cerrar la página.

## ✨ Funcionalidades

- **Registro de movimientos:** agregar ingresos o gastos con descripción, categoría y monto.
- **Categorías:** Comida, Transporte, Vivienda, Servicios, Salud, Ocio, Educación y Otros.
- **Selector de mes:** consultar los movimientos de cualquier mes.
- **Resumen mensual:** cálculo automático de ingresos, gastos y balance.
- **Historial:** listado de movimientos del mes con opción de eliminar.
- **Gastos por categoría:** gráfico de barras que muestra en qué se gasta más.
- **Modo oscuro automático:** se adapta a la configuración del dispositivo.
- **Persistencia local:** los datos se guardan en el navegador con `localStorage`.
- **Diseño responsive:** se adapta a celular, tablet y computador.

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de la aplicación |
| CSS3 | Estilos, variables CSS, modo oscuro y diseño responsive (Grid / Flexbox) |
| JavaScript (Vanilla) | Lógica, cálculos y manipulación del DOM |
| LocalStorage | Almacenamiento de los datos en el navegador |

## 🚀 Cómo usarla

### En línea
Abrir el enlace de la demo: https://danielvasquezjc07-cloud.github.io/control-gastos

### Local
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/danielvasquezjc07-cloud/control-gastos.git
   ```
2. Abrir `index.html` en cualquier navegador.

No requiere instalación ni dependencias.

## 📁 Estructura del proyecto

```
control-gastos/
├── index.html      ← Aplicación completa (HTML, CSS y JavaScript)
└── README.md
```

## 🔒 Privacidad

Toda la información se almacena únicamente en el navegador del usuario. No se envían datos a ningún servidor.

> Si se borran los datos de navegación o se usa otro navegador o dispositivo, los registros no estarán disponibles.

## 🔮 Mejoras futuras

- Editar movimientos existentes.
- Elegir la fecha exacta de cada movimiento.
- Exportar movimientos a Excel o PDF.
- Presupuestos mensuales por categoría con alertas.
- Sincronización en la nube con inicio de sesión.

## 👤 Autor

**Daniel Vásquez** — Desarrollador Full Stack
