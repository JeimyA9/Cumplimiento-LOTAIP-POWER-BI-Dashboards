# Supervisión de Entidades Públicas y Privadas — Cumplimiento LOTAIP

Dashboard interactivo en Power BI para monitorear y evaluar el cumplimiento de la **Ley Orgánica de Transparencia y Acceso a la Información Pública (LOTAIP)** por parte de entidades públicas y privadas del Ecuador, con base en datos proporcionados por la **Defensoría del Pueblo** (períodos 2020 y 2022).

## Objetivo

Ofrecer una visión integral y gráfica del estado de las entidades, permitiendo segmentar por período, ubicación geográfica, tipo de organización, ámbito y estado de cumplimiento — facilitando la supervisión, promoviendo la transparencia institucional y ayudando a identificar áreas con oportunidades de mejora en el acceso a la información.

## Estructura del Dashboard (5 páginas)

### 1. Inicio
Página principal con filtros y totales generales: total de entidades, entidades privadas vs. públicas, y totales por cantón, parroquia y provincia. Incluye segmentación por período, división política e información de identidad, además de botones de navegación hacia las demás páginas.

### 2. Supervisión de Entidades Públicas y Privadas
Vista general del universo de entidades supervisadas, con desglose por tipo de entidad (adscritas a la municipalidad, empresas públicas, empresas públicas municipales, entidades del régimen autónomo descentralizado, entidades privadas) y por catastro (pública/privada), así como distribución por función (gobiernos autónomos descentralizados, otras instituciones públicas, función ejecutiva, entidades privadas, función de transparencia y control social, función electoral, judicial y legislativa).

### 3. Cumplimiento
Análisis del estado del proceso mediante gráfico de embudo/barras que muestra los diferentes estados en los que se encuentran los procesos de cumplimiento. Incluye tabla detallada con procesos, nombre de entidad, estado, fecha de cierre y tiempo transcurrido.

### 4. Información de Entidades
Tabla con información detallada de cada entidad: nombre, RUC, teléfono, ámbito y estado de la entidad. Permite filtrado por nombre y por RUC.

### 5. Georeferencia
Visualización geográfica de la distribución de entidades por ciudad, provincia o cantón, utilizando direcciones e información de catastro. Al pasar el cursor sobre cada provincia se muestra un tooltip con la cantidad de entidades y la bandera de la provincia correspondiente.

## Tecnologías

- Power BI (modelado de datos, DAX, visualizaciones)
- Fuente de datos: Base de monitoreo de entidades de la Defensoría del Pueblo del Ecuador (2020 y 2022)


## Estructura del Repositorio

```
├── dashboard/
│   ├── lotaip-supervision.pbix
│   └── diccionarioDatos.pdf
├── capturas/
│   ├── inicio.png
│   ├── supervision-entidades.png
│   ├── cumplimiento.png
│   ├── informacion-entidades.png
│   └── georeferencia.png
└── README.md
```

## 📚 Fuente de Datos

Base de datos de monitoreo de entidades públicas y privadas — Defensoría del Pueblo del Ecuador, períodos 2020 y 2022.
