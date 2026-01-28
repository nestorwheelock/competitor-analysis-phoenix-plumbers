# Phoenix Plumbing Market Research Report
**[English Version](./market-research-2026-01-28.md)** | Español

## Análisis Integral de Inteligencia Competitiva | January 2026

**Informe Generado:** 2026-01-28 20:33 UTC
**Enfoque Geográfico:** Phoenix metropolitan area
**Herramienta de Análisis:** Plumber Market Research Platform

---

## Tabla de Contenidos

1. [Resumen Ejecutivo](#1-executive-summary)
2. [Metodología de Investigación](#2-research-methodology)
3. [Visión General del Mercado](#3-market-overview)
4. [Marco Estadístico](#4-statistical-framework)
5. [Análisis de Competidores](#5-competitor-analysis) (122 competidores)
6. [Análisis Cruzado de Competidores](#6-cross-competitor-analysis)
7. [Apéndices](#7-appendices)

---

## 1. Resumen Ejecutivo

### 1.1 Objetivos de Investigación

Este informe proporciona inteligencia competitiva integral para el mercado de servicios de plomería del Phoenix metropolitan area. El análisis tiene como objetivo:

1. **Mapear el panorama competitivo** - Identificar y categorizar todos los competidores activos
2. **Evaluar la presencia digital** - Evaluar la calidad del sitio web, rendimiento SEO y adopción de tecnología
3. **Identificar oportunidades** - Descubrir brechas de palabras clave y debilidades competitivas
4. **Establecer puntos de referencia** - Definir líneas base del mercado para métricas de rendimiento

### 1.2 Hallazgos Clave

- **Tamaño del Mercado:** 122 competidores identificados, 83% (102) tienen sitios web
- **Distribución de Reseñas:** Mediana 108 reseñas (IQR: 27-344), 20 valores atípicos estadísticos
- **Rendimiento Técnico:** Puntuación móvil promedio 61 (median 60), 102 competidores analizados
- **Profundidad de Contenido:** 46 Promedio de páginas rastreadas por sitio

### 1.3 Recomendaciones Estratégicas

Basado en el análisis competitivo, se identifican las siguientes oportunidades estratégicas:

1. **Diferenciación Técnica** - Con una puntuación móvil mediana de 60, alcanzar 80+ lo colocaría en el cuartil superior
2. **Explotación de Brechas de Contenido** - Muchos competidores tienen contenido delgado; las páginas de servicio completas representan una oportunidad
3. **Segmentación de Palabras Clave** - Enfocarse en palabras clave de alto volumen con baja cobertura competitiva
4. **SEO Local** - Páginas específicas geográficamente para códigos postales desatendidos

### 1.4 Declaración de Calidad de Datos

Este informe se basa en datos recopilados de fuentes públicamente disponibles:

| Fuente | Cobertura | Confianza |
|--------|----------|------------|
| Google Places API | 122/122 competitors | High |
| Website Crawl | 102/102 sites | Alta |
| PageSpeed Insights | 102/102 sites | Alta |
| Keyword Extraction | 95/102 sites | Media |

**Nota:** Los conteos de reseñas pueden estar agregados entre múltiples ubicaciones para competidores empresariales. Ver Sección 4 para tratamiento de valores atípicos.

---

## 2. Metodología de Investigación

### 2.1 Diseño de Investigación

**Tipo de Investigación:** Análisis cuantitativo de inteligencia competitiva

**Alcance Geográfico:** Phoenix metropolitan area con enfoque en comunidades del valle oeste
- Primarias: Surprise, Sun City, Sun City West, Glendale (Oeste), Peoria
- Códigos postales: 85301-85388 (23 códigos únicos)

**Alcance Temporal:** Datos recopilados January 2026

**Tamaño de Muestra:** N = 122 competidores identificados
- Con sitios web: 102 (83.6%)
- Con datos de rendimiento: 102 (100.0% de sitios web)
- Con datos de palabras clave: 95 (93.1% de sitios web)

### 2.2 Métodos de Recopilación de Datos

#### 2.2.1 Descubrimiento de Competidores

**Fuente:** API de Google Places (Búsqueda Cercana)

**Método:**
1. Define search grid covering target ZIP codes
2. Query "plumber" + "plumbing" + related terms at each coordinate
3. Deduplicate by `place_id` (Google's unique identifier)
4. Enrich via Place Details API for complete business information

#### 2.2.2 Rastreo de Sitios Web

**Herramienta:** Rastreador personalizado basado en Rust

**Datos Extraídos Por Página:**
- URL, HTTP status code, response time (ms)
- Title tag, meta description, meta keywords
- H1 text, heading hierarchy (H1-H6)
- Word count (content text only)
- Internal/external link inventory

#### 2.2.3 Análisis de Rendimiento

**Fuente:** API de Google PageSpeed Insights

**Métricas Recopiladas:**
- Lighthouse scores (mobile, desktop): 0-100
- Core Web Vitals: LCP, INP, CLS
- Resource breakdown: HTML, CSS, JS, images, fonts

**Umbrales de Core Web Vitals (según estándares de Google):**

| Métrica | Bueno | Necesita Mejora | Pobre |
|--------|------|-------------------|------|
| LCP | ≤2.5s | ≤4.0s | >4.0s |
| INP | ≤200ms | ≤500ms | >500ms |
| CLS | ≤0.1 | ≤0.25 | >0.25 |

### 2.3 Calidad de Datos y Limitaciones

**Limitaciones Conocidas:**

1. **Sesgo de Descubrimiento** - Solo se incluyen negocios descubribles a través de la API de Google Places
2. **Ambigüedad en Conteo de Reseñas** - Las marcas con múltiples ubicaciones pueden tener conteos de reseñas agregados
3. **Instantánea de Rendimiento** - Las puntuaciones de PageSpeed se capturaron en un solo punto en el tiempo
4. **Extracción de Palabras Clave** - Basada solo en contenido rastreado (no anuncios pagados)

**Indicadores de Confianza de Datos:**

- **Alta** ✓ - Fuente primaria verificada, múltiples señales corroboran
- **Media** ~ - Fuente única, plausible pero no verificada
- **Baja** ⚠ - Inferida, posibles problemas de calidad de datos
- **Desconocida** ? - Datos no recopilados o no aplicables

---

## 3. Visión General del Mercado

### 3.1 Resumen del Panorama Competitivo

| Métrica | Valor |
|--------|-------|
| Total de Competidores Identificados | 122 |
| Con Sitios Web Activos | 102 |
| Con Datos de Rendimiento | 102 |
| Con Datos de Palabras Clave | 95 |

### 3.2 Distribución de Reseñas

| Estadística | Valor |
|-----------|-------|
| Media | 676 |
| Mediana | 108 |
| Percentil 25 (Q1) | 27 |
| Percentil 75 (Q3) | 344 |
| IQR | 317 |
| Umbral de Valores Atípicos | >819 |

### 3.3 Rendimiento Técnico

| Métrica | Valor |
|--------|-------|
| Puntuación Móvil Promedio | 61/100 |
| Puntuación Móvil Mediana | 60/100 |
| Promedio de Páginas Rastreadas | 47 |

---

## 4. Marco Estadístico

### 4.1 Detección de Valores Atípicos (Método IQR)

Para distribuciones sesgadas (por ejemplo, conteos de reseñas), utilizamos el método del Rango Intercuartílico:

**Fórmula:**
```
Q1 = 25th percentile
Q3 = 75th percentile
IQR = Q3 - Q1
Upper bound = Q3 + 1.5 × IQR
```

**Application to Review Counts:**

- Q1 = 27, Q3 = 344, IQR = 317
- Upper bound = 344 + (1.5 × 317) = 819
- Competitors with >819 reviews classified as statistical outliers

### 4.2 Criterios de Clasificación de Entidades

| Clase | Criterios |
|-------|----------|
| Operador Local | Ubicación única, <500 reseñas |
| Marca Regional | 2-5 ubicaciones O 500-2000 reseñas |
| Red Empresarial | >5 ubicaciones O >2000 reseñas |
| Agregador de Marcas | Multi-servicio (HVAC+Plomería+Electricidad) |

**Nota:** La comparación directa entre diferentes clases de entidades puede ser engañosa. Este informe identifica claramente la clase de entidad para contexto.

### 4.3 Performance Rating Thresholds

| Rating | Mobile Score | Description |
|--------|--------------|-------------|
| Excellent | 90-100 | Top-tier performance |
| Bueno | 80-89 | Above average |
| Necesita Mejora | 50-79 | Average, has issues |
| Pobre | 0-49 | Significant problems |

---

## 5. Análisis de Competidores

This section provides detailed analysis for each of the 122 competidores identified.

### 100% Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.100percentplumber.com/ |
| Calificación | 5.0/5 (1595 reseñas) |
| Teléfono | (602) 757-6780 |
| Dirección | 17437 N 71st Dr Ste 106, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1595 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Housecall Pro, Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 15 | 3 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| review | 1776 | N/A |
| slider | 1400 | N/A |
| var | 1296 | N/A |
| water | 1234 | N/A |
| cur | 1120 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 90 | 47 | Above |
| Avg Word Count | 1206 | - | Good |
| Thin Content (<300) | 8 (8%) | - | Good |
| Rich Content (>1000) | 76 (84%) | - | Excellent |

**Content Distribution:**
- Service pages: 18
- Location pages: 0
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 51 | Needs Improvement |
| Desktop | 46 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 49.5s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 2 |
| Form Labels Missing | 7 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 7 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 97/100 | 1595 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 90 Páginas |
| Técnico | 48/100 | Puntuación móvil 51 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (51) con 80+


---

### 24/7 Water Conditioning & Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.247plumbingaz.com/ |
| Calificación | 4.4/5 (43 reseñas) |
| Teléfono | (623) 206-4892 |
| Dirección | 18700 N 107th Ave #9B, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 43 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 27 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 99 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.7s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 54/100 | 43 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 99/100 | Puntuación móvil 99 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### A Better Choice Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (9 reseñas) |
| Teléfono | (602) 935-6501 |
| Dirección | 8542 W Tuckey Ln, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 9
- Standard local operator profile: 9 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 9 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### A to Z Prestigious Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://atozprestigious.com/ |
| Calificación | 4.8/5 (35 reseñas) |
| Teléfono | (602) 638-9911 |
| Dirección | 20064 W Luke Ave, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 35 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 5197 | N/A |
| specs | 4427 | N/A |
| false | 2381 | N/A |
| https | 2088 | N/A |
| com | 1812 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 14 | 47 | Below |
| Avg Word Count | 1480 | - | Good |
| Thin Content (<300) | 6 (42%) | - | Needs Work |
| Rich Content (>1000) | 8 (57%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 6
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 62 | Needs Improvement |
| Desktop | 90 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.9s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Mixed |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 58/100 | 35 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 14 Páginas |
| Técnico | 76/100 | Puntuación móvil 62 |
| Marca | 35/100 | 1.8 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### A-1 Plumbing Contractors

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 3.0/5 (2 reseñas) |
| Teléfono | (623) 915-5502 |
| Dirección | 5200 W Bethany Home Rd, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 2
- Standard local operator profile: 2 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 40/100 | 2 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### ALLPRO, by Denali

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.denalicorp.com/our-brands/appumping/ |
| Calificación | 4.9/5 (39 reseñas) |
| Teléfono | (623) 776-3230 |
| Dirección | 6525 W State Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 39 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Webflow markers found"],"name":"Webflow","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| color | 16571 | N/A |
| scheme | 14944 | N/A |
| var | 7418 | N/A |
| important | 6856 | N/A |
| 0rem | 5112 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 172 | 47 | Above |
| Avg Word Count | 1662 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 172 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 28
- Location pages: 19
- Blog posts: 3
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 60 | Needs Improvement |
| Desktop | 93 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 12.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 8 |
| Form Labels Missing | 10 |

**Issues:** Missing skip link, Missing lang attribute, 8 empty links, 10 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 59/100 | 39 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 172 Páginas |
| Técnico | 76/100 | Puntuación móvil 60 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance, deep content

**Fortalezas:**
- Buen rendimiento técnico
- Contenido completo


---

### ATS Plumbing Inc.

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://atsplumbinginc.com/ |
| Calificación | 5.0/5 (1 reseñas) |
| Teléfono | (602) 690-7529 |
| Dirección | 7220 N Glen Harbor Blvd # 100, Glendale, AZ 85307, USA, Glendale, AZ, 85307 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Dormant Listing |
| Confianza | 70% |

**Evidencia:**
- Very low review count: 1
- Domain age 1050 days with only 1 reviews

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| return | 447 | N/A |
| const | 368 | N/A |
| true | 352 | N/A |
| error | 333 | N/A |
| thunderbolt | 327 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 3176 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 2 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 70 | Needs Improvement |
| Desktop | 88 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 7.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Poor |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: Poor, Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 1 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 79/100 | Puntuación móvil 70 |
| Marca | 50/100 | 2.9 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### AZ Home Services Group AC Repair & Plumbing Services of Sun City

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://azhomeservices.group/service-areas/sun-city-arizona-air-conditioner-plumbing-services/ |
| Calificación | 5.0/5 (6 reseñas) |
| Teléfono | (623) 307-5731 |
| Dirección | 10451 W Palmeras Dr, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 6
- Standard local operator profile: 6 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 61 | Needs Improvement |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.8s | ≤2.5s | Fail ✗ |
| CLS | 0.29 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 6 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 64/100 | Puntuación móvil 61 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### AZ Pro Plumbing and Drain, LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.azproplumbinganddrain.com/ |
| Calificación | 5.0/5 (11 reseñas) |
| Teléfono | (602) 284-9208 |
| Dirección | 5635 W Villa Theresa Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 11 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| rtcommonprops | 282 | N/A |
| window | 270 | N/A |
| true | 202 | N/A |
| important | 196 | N/A |
| rtflags | 156 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 12 | 47 | Below |
| Avg Word Count | 2030 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 12 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 4
- Location pages: 2
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 91 | Excellent |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.7s | ≤2.5s | Needs Work |
| CLS | 0.07 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 11 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 12 Páginas |
| Técnico | 95/100 | Puntuación móvil 91 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Ace Plumbers Phoenix AZ

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 4.9/5 (44 reseñas) |
| Teléfono | (602) 603-4819 |
| Dirección | 10521 Cll De Las Casitas, Phoenix, AZ 85037, USA, Phoenix, AZ, 85037 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 44 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 59/100 | 44 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Adept Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://adeptplumbingllc.com/ |
| Calificación | 5.0/5 (53 reseñas) |
| Teléfono | (623) 692-8348 |
| Dirección | 2955 W Sandra Terrace, Phoenix, AZ 85053, USA, Phoenix, AZ, 85053 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 53 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (5 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 16 | N/A |
| plumbing | 14 | N/A |
| service | 12 | N/A |
| satisfaction | 10 | N/A |
| use | 10 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 6 | 47 | Below |
| Avg Word Count | 249 | - | Thin |
| Thin Content (<300) | 2 (33%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 76 | Needs Improvement |
| Desktop | 97 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.6s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 9 |
| Form Labels Missing | 1 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 9 empty links, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 53 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 6 Páginas |
| Técnico | 86/100 | Puntuación móvil 76 |
| Marca | 75/100 | 6.5 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance, established brand; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Presencia de marca establecida

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### All Drains Emergency Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://alldrainsemergencyplumbing.com/ |
| Calificación | 5.0/5 (186 reseñas) |
| Teléfono | (602) 369-0958 |
| Dirección | 15826 N 64th Dr, Glendale, AZ 85306, USA, Glendale, AZ, 85306 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 186 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.7.4"}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 128419 | N/A |
| element | 78851 | N/A |
| wpr | 36451 | N/A |
| 0px | 22841 | N/A |
| color | 17639 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 103 | 47 | Above |
| Avg Word Count | 3022 | - | Good |
| Thin Content (<300) | 7 (6%) | - | Good |
| Rich Content (>1000) | 96 (93%) | - | Excellent |

**Content Distribution:**
- Service pages: 27
- Location pages: 44
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 47 | Poor |
| Desktop | 51 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 12.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 2 |
| Empty Links | 9 |
| Form Labels Missing | 3 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links, 3 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 186 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 103 Páginas |
| Técnico | 49/100 | Puntuación móvil 47 |
| Marca | 50/100 | 2.8 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (47) con 80+


---

### All Hours Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://allhoursplumbingnow.com/ |
| Calificación | 4.9/5 (65 reseñas) |
| Teléfono | (602) 677-2615 |
| Dirección | 4741 W Park View Ln, Glendale, AZ 85310, USA, Glendale, AZ, 85310 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 65 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 761 | N/A |
| com | 541 | N/A |
| content | 510 | N/A |
| allhoursplumbingnow | 506 | N/A |
| https | 475 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 66 | 47 | Above |
| Avg Word Count | 686 | - | Average |
| Thin Content (<300) | 8 (12%) | - | Good |
| Rich Content (>1000) | 6 (9%) | - | Opportunity |

**Content Distribution:**
- Service pages: 8
- Location pages: 16
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 62 | Needs Improvement |
| Desktop | 78 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 20.2s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 6 |
| Empty Links | 4 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading, 4 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 65 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 66 Páginas |
| Técnico | 70/100 | Puntuación móvil 62 |
| Marca | 35/100 | 1.7 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Alpha-Plumbing Services

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://alpha-plumbingservices.com/ |
| Calificación | 5.0/5 (113 reseñas) |
| Teléfono | (623) 734-7465 |
| Dirección | 16833 W Pierce St, Goodyear, AZ 85338, USA, Goodyear, AZ, 85338 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 113 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 4 | 47 | Below |
| Avg Word Count | 144 | - | Thin |
| Thin Content (<300) | 4 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 4
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 84 | Good |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.5s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 2 |
| Empty Links | 0 |
| Form Labels Missing | 1 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 113 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 4 Páginas |
| Técnico | 91/100 | Puntuación móvil 84 |
| Marca | 50/100 | 2.7 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### American Home Water & Air

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://americanhomewater.com/ |
| Calificación | 4.9/5 (2950 reseñas) |
| Teléfono | (602) 975-2697 |
| Dirección | 2030 W Desert Cove Ave, Phoenix, AZ 85029, USA, Phoenix, AZ, 85029 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 2950 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 47737 | N/A |
| google | 32600 | N/A |
| element | 18703 | N/A |
| maps | 18192 | N/A |
| map | 17391 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4653 | - | Good |
| Thin Content (<300) | 53 (23%) | - | Needs Work |
| Rich Content (>1000) | 177 (76%) | - | Excellent |

**Content Distribution:**
- Service pages: 37
- Location pages: 64
- Blog posts: 1
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 35 | Poor |
| Desktop | 41 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 7.8s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 2950 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 38/100 | Puntuación móvil 35 |
| Marca | 90/100 | 21.7 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong in strong reputation, deep content, established brand; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo
- Presencia de marca establecida

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (35) con 80+


---

### Amigo Rooter & Plumbing Phoenix Arizona

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.amigoplumbingaz.com/ |
| Calificación | 4.8/5 (584 reseñas) |
| Teléfono | (602) 446-6576 |
| Dirección | 3947 N 146th Dr, Goodyear, AZ 85395, USA, Goodyear, AZ, 85395 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 584 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | Housecall Pro, Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 1049 | N/A |
| space | 842 | N/A |
| water | 480 | N/A |
| class | 348 | N/A |
| rteblock | 348 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 10 | 47 | Below |
| Avg Word Count | 6733 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 10 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 35 | Poor |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 4 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 4 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 88/100 | 584 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 10 Páginas |
| Técnico | 57/100 | Puntuación móvil 35 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Anthony's Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.dayandnightair.com/anthonysplumbing/?utm_source=Anthony%27s%20GMB%20redirect%20to%20DNT&utm_medium=Anthony%27s%20GMB&utm_campaign=redirect%20to%20DNT%20page |
| Calificación | 4.8/5 (645 reseñas) |
| Teléfono | (623) 936-5400 |
| Dirección | 1201 N 54th Ave #127, Phoenix, AZ 85043, USA, Phoenix, AZ, 85043 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 645 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 54 | Needs Improvement |
| Desktop | 63 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 88/100 | 645 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 58/100 | Puntuación móvil 54 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Armstrong Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://armstrong-plumbing.com/?utm_source=google&utm_medium=GBP |
| Calificación | 5.0/5 (284 reseñas) |
| Teléfono | (602) 962-0888 |
| Dirección | 4420 W Creedance Blvd, Glendale, AZ 85310, USA, Glendale, AZ, 85310 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 284 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 98 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 100 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 0.8s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 284 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 100/100 | Puntuación móvil 100 |
| Marca | 50/100 | 4.8 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Ascend Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.ascendplumbing.net/ |
| Calificación | 4.8/5 (33 reseñas) |
| Teléfono | (602) 946-4107 |
| Dirección | 100, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 33 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (5 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 37 | N/A |
| ascend | 22 | N/A |
| home | 19 | N/A |
| contact | 16 | N/A |
| calendar | 15 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 16 | 47 | Below |
| Avg Word Count | 87 | - | Thin |
| Thin Content (<300) | 16 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 69 | Needs Improvement |
| Desktop | 94 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 3 |
| Empty Links | 34 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, No H1 heading, 34 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 58/100 | 33 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 16 Páginas |
| Técnico | 81/100 | Puntuación móvil 69 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### At your service plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 3.0/5 (4 reseñas) |
| Teléfono | (623) 755-0104 |
| Dirección | 421 E Wigwam Blvd, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 4
- Standard local operator profile: 4 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 40/100 | 4 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Aurora Plumbing and Mechanical LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.auroraplumbingllc.net/ |
| Calificación | 5.0/5 (56 reseñas) |
| Teléfono | (623) 234-4496 |
| Dirección | 9577 W Ross Ave, Peoria, AZ 85382, USA, Peoria, AZ, 85382 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 56 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (11 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 30 | N/A |
| mechanical | 23 | N/A |
| usresidentialcommercial | 23 | N/A |
| auroraplumbingllc | 22 | N/A |
| industrialcareerscontact | 21 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 14 | 47 | Below |
| Avg Word Count | 219 | - | Thin |
| Thin Content (<300) | 12 (85%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 21.3s | ≤2.5s | Fail ✗ |
| CLS | 0.09 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 8 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 56 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 14 Páginas |
| Técnico | 62/100 | Puntuación móvil 57 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones


---

### Authentic Plumbing, LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://authenticplumbingaz.com/ |
| Calificación | 5.0/5 (255 reseñas) |
| Teléfono | (602) 541-2361 |
| Dirección | 12220 W Candelaria Ct, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 255 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 71 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 18.2s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 255 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 63/100 | Puntuación móvil 56 |
| Marca | 50/100 | 4.3 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Before & After Plumbing and Drain, LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.beforeandafterplumbing.com/?utm_source=GBP&utm_medium=organic&utm_campaign=gbp |
| Calificación | 4.9/5 (960 reseñas) |
| Teléfono | (623) 250-2584 |
| Dirección | 13059 W Grand Ave #9, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 960 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 3 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 3 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 52 | Needs Improvement |
| Desktop | 76 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.5s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 89/100 | 960 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 3 Páginas |
| Técnico | 64/100 | Puntuación móvil 52 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Belsito Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.belsitoplumbing.com/ |
| Calificación | 4.6/5 (280 reseñas) |
| Teléfono | (480) 425-9900 |
| Dirección | 2215 W Melinda Ln # A, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 280 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 76/100 | 280 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Benjamin Franklin Plumbing of Phoenix, AZ

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.benfranklinplumbingaz.com/?utm_source=organic&utm_medium=gbp_listing |
| Calificación | 4.8/5 (1893 reseñas) |
| Teléfono | (480) 223-9348 |
| Dirección | 1911 W Parkside Ln, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1893 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 75 | Needs Improvement |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 13.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 13 | organic |

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 95/100 | 1893 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 87/100 | Puntuación móvil 75 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Blackstone Plumbing Heating & Air Conditioning

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.blackstonehvacaz.com/ |
| Calificación | 4.8/5 (157 reseñas) |
| Teléfono | (602) 507-0222 |
| Dirección | 9915 W Bell Rd #448, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 157 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| hvac | 128 | N/A |
| services | 86 | N/A |
| document | 74 | N/A |
| service | 60 | N/A |
| installation | 54 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 16 | 47 | Below |
| Avg Word Count | 505 | - | Average |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 4
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 100 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.8s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 68/100 | 157 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 16 Páginas |
| Técnico | 100/100 | Puntuación móvil 100 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Brothers Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 4.0/5 (1 reseñas) |
| Teléfono | (623) 232-0731 |
| Dirección | 6730 W Frier Dr # 107, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 1
- Standard local operator profile: 1 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 50/100 | 1 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Bumble Bee Home Services

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://bumblebeeplumbingaz.com/?utm_source=google&utm_medium=organic&utm_campaign=GMBListing-glendale-az/ |
| Calificación | 4.9/5 (3737 reseñas) |
| Teléfono | (602) 813-0298 |
| Dirección | 7600 N 71st Ave, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 3737 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 131 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 82 | Good |
| Desktop | 98 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.9s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 3737 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 90/100 | Puntuación móvil 82 |
| Marca | 90/100 | 13.7 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong in strong reputation, good technical performance, established brand; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Presencia de marca establecida

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Burnett's Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://burnettsplumbing.com/ |
| Calificación | 5.0/5 (124 reseñas) |
| Teléfono | (602) 472-1007 |
| Dirección | 32315 N 171st Ave, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 124 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Vue.js, Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (24 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| astro | 72 | N/A |
| let | 45 | N/A |
| getattribute | 39 | N/A |
| new | 39 | N/A |
| component | 33 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 6 | 47 | Below |
| Avg Word Count | 240 | - | Thin |
| Thin Content (<300) | 4 (66%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 72 | Needs Improvement |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 124 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 6 Páginas |
| Técnico | 85/100 | Puntuación móvil 72 |
| Marca | 50/100 | 2.7 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Cactus Plumbing & Air

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://cactusplumbingandair.com/surprise-plumber-and-ac-repair/?utm_source=gmb&utm_medium=surprise |
| Calificación | 4.9/5 (185 reseñas) |
| Teléfono | (623) 294-2452 |
| Dirección | 12211 W Bell Rd Suite 109, Surprise, AZ 85378, USA, Surprise, AZ, 85378 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 185 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 17 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 15511 | N/A |
| function | 15128 | N/A |
| mejs | 14527 | N/A |
| repair | 14113 | N/A |
| plumber | 10667 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4067 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 44
- Location pages: 26
- Blog posts: 8
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 86 | Good |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.4s | ≤2.5s | Pass ✓ |
| CLS | 0.20 | ≤0.1 | Needs Work |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 185 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 92/100 | Puntuación móvil 86 |
| Marca | 50/100 | 4.1 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: good technical performance, deep content

**Fortalezas:**
- Buen rendimiento técnico
- Contenido completo


---

### Cactus Plumbing And Air

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://cactusplumbingandair.com/sun-city-az/ |
| Calificación | 4.9/5 (226 reseñas) |
| Teléfono | (623) 294-8853 |
| Dirección | 12630 N 103rd Ave # 214, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 226 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 17 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 14667 | N/A |
| mejs | 14600 | N/A |
| plumbing | 14523 | N/A |
| repair | 14115 | N/A |
| plumber | 10992 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 3990 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 62
- Location pages: 9
- Blog posts: 30
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 92 | Excellent |
| Desktop | 97 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.7s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 226 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 94/100 | Puntuación móvil 92 |
| Marca | 50/100 | 4.1 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo


---

### Cactus Plumbing And Air

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://cactusplumbingandair.com/glendale-plumber-and-ac-repair/?utm_source=gmb&utm_medium=glendale |
| Calificación | 4.9/5 (185 reseñas) |
| Teléfono | (623) 257-5117 |
| Dirección | 5008 W Glendale Ave Unit 105, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 185 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 17 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 15491 | N/A |
| function | 15128 | N/A |
| mejs | 14527 | N/A |
| repair | 14085 | N/A |
| plumber | 10617 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4064 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 43
- Location pages: 27
- Blog posts: 6
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | 88 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 185 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 69/100 | Puntuación móvil N/A |
| Marca | 50/100 | 4.1 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: deep content

**Fortalezas:**
- Contenido completo


---

### Canyon Plumbing Solutions

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://canyonplumbingsolutions.com/ |
| Calificación | 5.0/5 (100 reseñas) |
| Teléfono | (623) 335-9032 |
| Dirección | 2550 W Union Hills Dr #354, Phoenix, AZ 85023, USA, Phoenix, AZ, 85023 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 100 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 9 | 2 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| color | 6242 | N/A |
| preset | 5148 | N/A |
| vivid | 3276 | N/A |
| var | 3068 | N/A |
| important | 2705 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 85 | 47 | Above |
| Avg Word Count | 1359 | - | Good |
| Thin Content (<300) | 6 (7%) | - | Good |
| Rich Content (>1000) | 67 (78%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 20
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 67 | Needs Improvement |
| Desktop | 82 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 14.7s | ≤2.5s | Fail ✗ |
| CLS | 0.04 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 2 |
| Empty Links | 1 |
| Form Labels Missing | 2 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 100 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 85 Páginas |
| Técnico | 74/100 | Puntuación móvil 67 |
| Marca | 20/100 | 0.9 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### Canyon State Service Experts

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.serviceexperts.com/surprise-az?&utm_campaign=listing&utm_medium=organic_search&utm_source=gmb&utm_content=brand |
| Calificación | 4.9/5 (2444 reseñas) |
| Teléfono | (602) 844-4104 |
| Dirección | 11560 N Dysart Rd Suite 116, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 2444 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | ServiceTitan | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 14 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| service | 8130 | N/A |
| experts | 5959 | N/A |
| services | 5469 | N/A |
| var | 3800 | N/A |
| process | 3588 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2347 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 194 (84%) | - | Excellent |

**Content Distribution:**
- Service pages: 230
- Location pages: 33
- Blog posts: 17
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 63 | Needs Improvement |
| Desktop | 60 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.7s | ≤2.5s | Needs Work |
| CLS | 0.09 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 13 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 2444 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 61/100 | Puntuación móvil 63 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo


---

### Christian Brothers Plumbing, A/C, & Electrical

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://cbrothers.com/?utm_source=google&utm_medium=organic&utm_campaign=gbp |
| Calificación | 4.8/5 (2105 reseñas) |
| Teléfono | (623) 939-9421 |
| Dirección | 6827 W Belmont Ave, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 2105 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 95 | 36 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| repair | 4122 | N/A |
| electrical | 3229 | N/A |
| plumbing | 2992 | N/A |
| air | 2836 | N/A |
| water | 2811 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1263 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 198 (86%) | - | Excellent |

**Content Distribution:**
- Service pages: 18
- Location pages: 67
- Blog posts: 1
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 71 | Needs Improvement |
| Desktop | 78 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.3s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 5 |
| Form Labels Missing | 8 |

**Issues:** Missing skip link, Missing lang attribute, 5 empty links, 8 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 95/100 | 2105 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 74/100 | Puntuación móvil 71 |
| Marca | 90/100 | 23.9 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo
- Presencia de marca establecida


---

### Copper State Plumbing Services LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 3.9/5 (22 reseñas) |
| Teléfono | (602) 561-3391 |
| Dirección | 13444 W Ocotillo Ln, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 22 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 49/100 | 22 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Courtesy Plumbing of AZ, LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://courtesyplumbingofaz.com/ |
| Calificación | 4.6/5 (42 reseñas) |
| Teléfono | (623) 247-7952 |
| Dirección | 6014 W Glendale Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 42 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 88 | N/A |
| roc | 88 | N/A |
| use | 45 | N/A |
| bonded | 44 | N/A |
| insured | 44 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 23 | 47 | Below |
| Avg Word Count | 231 | - | Thin |
| Thin Content (<300) | 20 (86%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 66 | Needs Improvement |
| Desktop | 82 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.6s | ≤2.5s | Fail ✗ |
| CLS | 0.15 | ≤0.1 | Needs Work |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 56/100 | 42 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 23 Páginas |
| Técnico | 74/100 | Puntuación móvil 66 |
| Marca | 35/100 | 1.1 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Darrels drain cleaning & locating

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.phxdraincleaning.com/ |
| Calificación | 4.4/5 (41 reseñas) |
| Teléfono | (602) 402-3727 |
| Dirección | 10909 W Camelot Cir, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 41 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 93 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 99 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.2s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 54/100 | 41 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 99/100 | Puntuación móvil 99 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Deer Valley Plumbing & Air Conditioning

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.deervalleyplumbing.com/?utm_source=GMB&utm_medium=organic&utm_campaign=glendale |
| Calificación | 5.0/5 (41 reseñas) |
| Teléfono | (623) 283-4500 |
| Dirección | 9524 W Camelback Rd STE 130-440, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 41 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 34 | Poor |
| Desktop | 62 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.0s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 41 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 48/100 | Puntuación móvil 34 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: poor technical performance, thin content

**Debilidades:**
- Mal rendimiento móvil
- Contenido delgado

**Oportunidades a Explotar:**
- Superar su puntuación móvil (34) con 80+
- Crear contenido más profundo que sus páginas delgadas


---

### Deer Valley Plumbing & Air Conditioning

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.deervalleyplumbing.com/ |
| Calificación | 4.8/5 (1237 reseñas) |
| Teléfono | (623) 281-3783 |
| Dirección | 2411 W Lone Cactus Dr, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1237 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 36 | Poor |
| Desktop | 78 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.0s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 0 |
| Avg Position | 10.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 10 | organic |

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 95/100 | 1237 reseñas |
| SERP | 3/100 | 1 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 57/100 | Puntuación móvil 36 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Desert Water Plumbing and Rooter

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.desertwateraz.com/near-me-plumber-peoria-az/?utm_source=google&utm_medium=organic&utm_campaign=gbp_peoria |
| Calificación | 5.0/5 (924 reseñas) |
| Teléfono | (602) 641-2998 |
| Dirección | 8301 W Foothill Dr, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 924 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 325 | N/A |
| function | 253 | N/A |
| true | 200 | N/A |
| plumbing | 185 | N/A |
| repair | 183 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 70 | 47 | Above |
| Avg Word Count | 244 | - | Thin |
| Thin Content (<300) | 64 (91%) | - | Needs Work |
| Rich Content (>1000) | 6 (8%) | - | Opportunity |

**Content Distribution:**
- Service pages: 6
- Location pages: 8
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 72 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.1s | ≤2.5s | Needs Work |
| CLS | 0.32 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 0 |
| Form Labels Missing | 2 |

**Issues:** Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 90/100 | 924 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 70 Páginas |
| Técnico | 75/100 | Puntuación móvil 72 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### Dh Plumbing Llc

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 4.8/5 (67 reseñas) |
| Teléfono | (623) 220-1800 |
| Dirección | 6626 W Villa Theresa Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 67 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 68/100 | 67 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Diamondback Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.diamondbackplumbing.com/ |
| Calificación | 4.5/5 (690 reseñas) |
| Teléfono | (602) 428-0910 |
| Dirección | 17423 N 25th Ave, Phoenix, AZ 85023, USA, Phoenix, AZ, 85023 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 690 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| width | 2044 | N/A |
| height | 1306 | N/A |
| min | 1244 | N/A |
| padding | 1149 | N/A |
| flex | 991 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 34 | 47 | Below |
| Avg Word Count | 2784 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 34 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 77 | Needs Improvement |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.8s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 34.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 34 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 11 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 85/100 | 690 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 40/100 | 34 Páginas |
| Técnico | 88/100 | Puntuación móvil 77 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### Dignity Plumbers Service & Water Softeners

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.dignityplumbingaz.com/ |
| Calificación | 5.0/5 (813 reseñas) |
| Teléfono | (623) 235-4045 |
| Dirección | 11200 W Wisconsin Ave #5A, Youngtown, AZ 85363, USA, Youngtown, AZ, 85363 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 813 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 2 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 42 | Poor |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.7s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 90/100 | 813 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 46/100 | Puntuación móvil 42 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in poor technical performance, thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Mal rendimiento móvil
- Contenido delgado

**Oportunidades a Explotar:**
- Superar su puntuación móvil (42) con 80+
- Crear contenido más profundo que sus páginas delgadas


---

### Donley A/C & Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.donleyservice.com/ |
| Calificación | 4.9/5 (1119 reseñas) |
| Teléfono | (480) 295-7385 |
| Dirección | 11062 N 24th Ave, Phoenix, AZ 85029, USA, Phoenix, AZ, 85029 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1119 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | ServiceTitan | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 24 | 2 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 10761 | N/A |
| hvac | 7576 | N/A |
| sewer | 6388 | N/A |
| water | 5191 | N/A |
| drains | 5075 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2157 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 230
- Location pages: 80
- Blog posts: 74
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 74 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.0s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 13 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 1119 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 76/100 | Puntuación móvil 74 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo


---

### Drain Squad A Plumbing & Drain

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.drainsquadplumbing.com/ |
| Calificación | 4.5/5 (42 reseñas) |
| Teléfono | (623) 594-4333 |
| Dirección | 4446 N 126th Dr, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 42 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 641 | N/A |
| drain | 301 | N/A |
| function | 301 | N/A |
| source | 253 | N/A |
| plumbing | 242 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 27 | 47 | Below |
| Avg Word Count | 1673 | - | Good |
| Thin Content (<300) | 2 (7%) | - | Good |
| Rich Content (>1000) | 25 (92%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 26 | Poor |
| Desktop | 38 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.0s | ≤2.5s | Fail ✗ |
| CLS | 1.00 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 9 |
| Form Labels Missing | 21 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links, 21 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 55/100 | 42 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 27 Páginas |
| Técnico | 32/100 | Puntuación móvil 26 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: poor technical performance

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (26) con 80+


---

### Drain Tech Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://fast-plumbing-glendale.com/ |
| Calificación | 5.0/5 (14 reseñas) |
| Teléfono | (408) 705-2633 |
| Dirección | 5901 W Behrend Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 14 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 94 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.7s | ≤2.5s | Pass ✓ |
| CLS | 0.15 | ≤0.1 | Needs Work |

**Improvement Opportunities:**
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 14 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 97/100 | Puntuación móvil 94 |
| Marca | 50/100 | 3.0 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### E.R. Tankless & Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://erplumbingaz.com/ |
| Calificación | 5.0/5 (82 reseñas) |
| Teléfono | (480) 262-8662 |
| Dirección | 25904 N 96th Ln, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 82 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | jQuery | Media |

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 3265 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 2 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 59 | Needs Improvement |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.6s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 82 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 57/100 | Puntuación móvil 59 |
| Marca | 75/100 | 5.5 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, established brand; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Presencia de marca establecida

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Echo Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://echoplumbingaz.com/ |
| Calificación | 5.0/5 (76 reseñas) |
| Teléfono | (602) 515-5171 |
| Dirección | 17646 W Running Deer Trl, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 76 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Vue.js, Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| document | 173 | N/A |
| function | 107 | N/A |
| var | 93 | N/A |
| style | 65 | N/A |
| addeventlistener | 44 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 34 | 47 | Below |
| Avg Word Count | 125 | - | Thin |
| Thin Content (<300) | 32 (94%) | - | Needs Work |
| Rich Content (>1000) | 2 (5%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 2
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 62 | Needs Improvement |
| Desktop | 83 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 28.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 15 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 15 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 76 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 34 Páginas |
| Técnico | 72/100 | Puntuación móvil 62 |
| Marca | 35/100 | 1.6 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### Edge Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://edgeplumbingllc.com/ |
| Calificación | 5.0/5 (29 reseñas) |
| Teléfono | (623) 208-1668 |
| Dirección | 13337 W Cottonwood St, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 29 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.8.3"}  | Medium |
| Reservas | Housecall Pro | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 2271 | N/A |
| plumbing | 2198 | N/A |
| window | 1906 | N/A |
| elem | 1508 | N/A |
| style | 1419 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 154 | 47 | Above |
| Avg Word Count | 945 | - | Good |
| Thin Content (<300) | 16 (10%) | - | Good |
| Rich Content (>1000) | 60 (38%) | - | Excellent |

**Content Distribution:**
- Service pages: 19
- Location pages: 47
- Blog posts: 6
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 39 | Poor |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 27.7s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 29 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 154 Páginas |
| Técnico | 47/100 | Puntuación móvil 39 |
| Marca | 20/100 | 1.0 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in deep content; vulnerable in poor technical performance

**Fortalezas:**
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (39) con 80+


---

### Emergency Master Plumbing & Air

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://emergencymasterplumbingair.com/ |
| Calificación | 4.9/5 (727 reseñas) |
| Teléfono | (623) 584-4706 |
| Dirección | 16200 N 154th Dr, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 727 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 1 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| block | 910 | N/A |
| emergencymasterplumbingair | 873 | N/A |
| com | 872 | N/A |
| https | 541 | N/A |
| content | 508 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 398 | 47 | Above |
| Avg Word Count | 102 | - | Thin |
| Thin Content (<300) | 395 (99%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 40
- Location pages: 175
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 66 | Needs Improvement |
| Desktop | 81 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 89/100 | 727 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 398 Páginas |
| Técnico | 73/100 | Puntuación móvil 66 |
| Marca | 50/100 | 3.7 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo


---

### Emergency Plumbing Hero

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.yourplumbinghero.com/ |
| Calificación | 5.0/5 (41 reseñas) |
| Teléfono | (602) 301-1664 |
| Dirección | 6737 W Glendale Ave, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 41 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 11784 | N/A |
| div | 5600 | N/A |
| element | 5554 | N/A |
| data | 4880 | N/A |
| classname | 4560 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2120 | - | Good |
| Thin Content (<300) | 19 (8%) | - | Good |
| Rich Content (>1000) | 167 (72%) | - | Excellent |

**Content Distribution:**
- Service pages: 78
- Location pages: 17
- Blog posts: 91
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 9 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 41 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: deep content

**Fortalezas:**
- Contenido completo


---

### Faucet Doctor Plumbing and HVAC Services

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.faucetdoctorplumbingaz.com/ |
| Calificación | 4.9/5 (1110 reseñas) |
| Teléfono | (623) 214-7161 |
| Dirección | 28214 N 168th Ave, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1110 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| blurb | 4205 | N/A |
| header | 4082 | N/A |
| footer | 3871 | N/A |
| important | 3402 | N/A |
| menu | 3388 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 63 | 47 | Above |
| Avg Word Count | 1107 | - | Good |
| Thin Content (<300) | 9 (14%) | - | Good |
| Rich Content (>1000) | 36 (57%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 4
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 51 | Needs Improvement |
| Desktop | 37 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.9s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 1110 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 63 Páginas |
| Técnico | 44/100 | Puntuación móvil 51 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (51) con 80+


---

### Flow Tech Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.flowtechplumbingaz.com/general-plumbing |
| Calificación | 5.0/5 (341 reseñas) |
| Teléfono | (623) 303-7736 |
| Dirección | 10530 W Sands Dr, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 341 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Reservas | Housecall Pro, Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| block | 21168 | N/A |
| sqs | 10821 | N/A |
| width | 7678 | N/A |
| yui | 6575 | N/A |
| grid | 6052 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 164 | 47 | Above |
| Avg Word Count | 2445 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 164 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 103
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 36 | Poor |
| Desktop | 45 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.6s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 341 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 164 Páginas |
| Técnico | 40/100 | Puntuación móvil 36 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (36) con 80+


---

### Flush King Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://flushking.com/ |
| Calificación | 4.8/5 (468 reseñas) |
| Teléfono | (602) 644-1950 |
| Dirección | 6619 N Scottsdale Rd, Scottsdale, AZ 85250, USA, Scottsdale, AZ, 85250 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 468 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.8.3"}  | Medium |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 5281 | N/A |
| fusion | 5163 | N/A |
| header | 4499 | N/A |
| plumbing | 4286 | N/A |
| cdata | 3909 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1081 | - | Good |
| Thin Content (<300) | 7 (3%) | - | Good |
| Rich Content (>1000) | 200 (86%) | - | Excellent |

**Content Distribution:**
- Service pages: 26
- Location pages: 170
- Blog posts: 7
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | 93 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 78/100 | 468 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 71/100 | Puntuación móvil N/A |
| Marca | 90/100 | 26.3 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo
- Presencia de marca establecida


---

### Forrest Anderson Plumbing & Air Conditioning

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://forrestanderson.net/ |
| Calificación | 4.6/5 (108 reseñas) |
| Teléfono | (623) 780-4060 |
| Dirección | 17225 N 63rd Ave, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 108 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 509360 | N/A |
| specs | 462717 | N/A |
| false | 206007 | N/A |
| https | 143427 | N/A |
| com | 117862 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4163 | - | Good |
| Thin Content (<300) | 4 (1%) | - | Good |
| Rich Content (>1000) | 224 (97%) | - | Excellent |

**Content Distribution:**
- Service pages: 3
- Location pages: 37
- Blog posts: 8
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 52 | Needs Improvement |
| Desktop | 75 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.5s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Mixed |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 11 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading, 11 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 66/100 | 108 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 63/100 | Puntuación móvil 52 |
| Marca | 90/100 | 21.2 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: deep content, established brand

**Fortalezas:**
- Contenido completo
- Presencia de marca establecida


---

### Glendale Plumbing Experts

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (24 reseñas) |
| Teléfono | (520) 392-7887 |
| Dirección | 6631 W Peoria Ave, Glendale, AZ 85302, USA, Glendale, AZ, 85302 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 24 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 24 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Good Guys Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.good-guys-plumbing.com/ |
| Calificación | 5.0/5 (6 reseñas) |
| Teléfono | (623) 776-2457 |
| Dirección | 8427 W Glendale Ave Lot 55, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 6
- Standard local operator profile: 6 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 1049 | N/A |
| good | 984 | N/A |
| guys | 983 | N/A |
| var | 915 | N/A |
| supports | 912 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 108 | 47 | Above |
| Avg Word Count | 433 | - | Average |
| Thin Content (<300) | 4 (3%) | - | Good |
| Rich Content (>1000) | 6 (5%) | - | Opportunity |

**Content Distribution:**
- Service pages: 14
- Location pages: 52
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.6s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 6 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 108 Páginas |
| Técnico | 67/100 | Puntuación móvil 56 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: deep content

**Fortalezas:**
- Contenido completo


---

### Grand Canyon Home Services

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://grandcanyonac.com/surprise-az/?utm_source=gmb&utm_medium=organic&utm_campaign=suprise |
| Calificación | 4.9/5 (331 reseñas) |
| Teléfono | (623) 444-6988 |
| Dirección | 15331 W Bell Rd Ste. 212-66, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 331 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 10073 | N/A |
| services | 6663 | N/A |
| var | 5845 | N/A |
| return | 5425 | N/A |
| document | 5209 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 171 | 47 | Above |
| Avg Word Count | 2894 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 171 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 17
- Location pages: 51
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 53 | Needs Improvement |
| Desktop | 64 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 13.7s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 6 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 6 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 331 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 171 Páginas |
| Técnico | 58/100 | Puntuación móvil 53 |
| Marca | 90/100 | 14.8 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo
- Presencia de marca establecida


---

### Hotrod plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.hotrod-plumbing.com/ |
| Calificación | 5.0/5 (159 reseñas) |
| Teléfono | (480) 210-9957 |
| Dirección | 2920 W Robin Ln, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 159 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Vue.js, Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (23 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 60 | N/A |
| hotrod | 36 | N/A |
| content | 31 | N/A |
| com | 30 | N/A |
| https | 28 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 38 | 47 | Average |
| Avg Word Count | 1716 | - | Good |
| Thin Content (<300) | 2 (5%) | - | Good |
| Rich Content (>1000) | 26 (68%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 75 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 18.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 16 |
| Form Labels Missing | 1 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 16 empty links, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 159 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 38 Páginas |
| Técnico | 65/100 | Puntuación móvil 56 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones


---

### Impact Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (53 reseñas) |
| Teléfono | (623) 330-0858 |
| Dirección | 11828 N 44th Ave, Glendale, AZ 85304, USA, Glendale, AZ, 85304 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 53 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 53 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Instant Plumbing and Rooter

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://instant.plumbing/?utm_source=organic&utm_medium=gbp&utm_campaign=testing&utm_id=9x10&utm_term=post |
| Calificación | 5.0/5 (344 reseñas) |
| Teléfono | (480) 353-7267 |
| Dirección | 4340 W Charleston Ave, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 344 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 97 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 63 | Needs Improvement |
| Desktop | 77 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 344 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 70/100 | Puntuación móvil 63 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### JV7 Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://jv7plumbingllc.com/ |
| Calificación | 5.0/5 (21 reseñas) |
| Teléfono | (602) 621-7894 |
| Dirección | 7502 N 47th Dr A14, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 21 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| mejs | 7957 | N/A |
| jacqueline | 5341 | N/A |
| storage | 5341 | N/A |
| empty | 2616 | N/A |
| error | 2442 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 179 | 47 | Above |
| Avg Word Count | 899 | - | Good |
| Thin Content (<300) | 43 (24%) | - | Needs Work |
| Rich Content (>1000) | 111 (62%) | - | Excellent |

**Content Distribution:**
- Service pages: 11
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 40 | Poor |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.8s | ≤2.5s | Fail ✗ |
| CLS | 0.34 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 3 |
| Empty Links | 5 |
| Form Labels Missing | 4 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading, 5 empty links, 4 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 21 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 179 Páginas |
| Técnico | 59/100 | Puntuación móvil 40 |
| Marca | 75/100 | 7.4 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: deep content, established brand

**Fortalezas:**
- Contenido completo
- Presencia de marca establecida


---

### Kay's Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (52 reseñas) |
| Teléfono | (623) 824-3975 |
| Dirección | 19808 N 44th Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 52 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 52 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### King Charles Plumbing & Air Conditioning

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://kingcharles.com/?utm_source=gmb&utm_medium=surprise |
| Calificación | 5.0/5 (630 reseñas) |
| Teléfono | (623) 223-8065 |
| Dirección | 14924 W Lamoille Dr, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 80% |

**Evidencia:**
- Regional review count: 630 (range: 500-2000)
- Established domain: 26 years

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| https | 78 | N/A |
| com | 75 | N/A |
| water | 70 | N/A |
| kingcharles | 69 | N/A |
| content | 67 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 71 | 47 | Above |
| Avg Word Count | 108 | - | Thin |
| Thin Content (<300) | 68 (95%) | - | Needs Work |
| Rich Content (>1000) | 3 (4%) | - | Opportunity |

**Content Distribution:**
- Service pages: 6
- Location pages: 7
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 88 | Good |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.8s | ≤2.5s | Needs Work |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 90/100 | 630 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 71 Páginas |
| Técnico | 94/100 | Puntuación móvil 88 |
| Marca | 90/100 | 26.2 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Presencia de marca establecida


---

### Lawson Family Plumbing Inc.

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://lawsonfamilyplumbing.com/ |
| Calificación | 4.8/5 (1541 reseñas) |
| Teléfono | (602) 413-5790 |
| Dirección | 1497 E Baseline Rd STE 110, Gilbert, AZ 85233, USA, Gilbert, AZ, 85233 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 80% |

**Evidencia:**
- Regional review count: 1541 (range: 500-2000)
- Established domain: 14 years

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| com | 582 | N/A |
| lawsonfamilyplumbing | 582 | N/A |
| https | 532 | N/A |
| content | 482 | N/A |
| png | 482 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 83 | 47 | Above |
| Avg Word Count | 104 | - | Thin |
| Thin Content (<300) | 81 (97%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 12
- Location pages: 5
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 49 | Poor |
| Desktop | 72 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 95/100 | 1541 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 83 Páginas |
| Técnico | 60/100 | Puntuación móvil 49 |
| Marca | 90/100 | 14.8 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Presencia de marca establecida


---

### Leak Hunters: Leak Detection

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.leakhuntersaz.com/ |
| Calificación | 4.9/5 (129 reseñas) |
| Teléfono | (623) 980-2888 |
| Dirección | 8379 W Midway Ave, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 129 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| leak | 235 | N/A |
| const | 152 | N/A |
| detection | 139 | N/A |
| water | 125 | N/A |
| pool | 82 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 39 | 47 | Average |
| Avg Word Count | 272 | - | Thin |
| Thin Content (<300) | 27 (69%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 10
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 85 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 129 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 39 Páginas |
| Técnico | 71/100 | Puntuación móvil 57 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Lee's Air, Plumbing, & Heating

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://leesair.com/peoria/ |
| Calificación | 5.0/5 (94 reseñas) |
| Teléfono | (602) 649-2180 |
| Dirección | 9210 W Peoria Ave Suite 6b, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 94 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | ServiceTitan, Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 84 | 4 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 25620 | N/A |
| color | 25415 | N/A |
| var | 13364 | N/A |
| preset | 11583 | N/A |
| element | 10466 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 3033 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 44
- Location pages: 107
- Blog posts: 3
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 45 | Poor |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 11.0s | ≤2.5s | Fail ✗ |
| CLS | 0.07 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 94 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 56/100 | Puntuación móvil 45 |
| Marca | 90/100 | 25.4 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo
- Presencia de marca establecida


---

### Lucky Duck Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 4.8/5 (57 reseñas) |
| Teléfono | (623) 341-3245 |
| Dirección | 10135 W Denton Ln, Glendale, AZ 85307, USA, Glendale, AZ, 85307 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 57 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 68/100 | 57 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Maloney Plumbing & Drain Services in Phoenix, AZ

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.maloneyplumbing.com/?utm_source=gmb&utm_medium=organic |
| Calificación | 4.9/5 (1025 reseñas) |
| Teléfono | (602) 671-3617 |
| Dirección | 9119 7th St Suite 201, Phoenix, AZ 85020, USA, Phoenix, AZ, 85020 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1025 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 46 | Poor |
| Desktop | 80 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 26.6s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 41.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 41 | organic |

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 1025 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 63/100 | Puntuación móvil 46 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Navarro Plumbing Services LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 4.4/5 (23 reseñas) |
| Teléfono | (602) 750-5551 |
| Dirección | 5526 N 84th Ln, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 23 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 54/100 | 23 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### One Shot Installation Electrical, Plumbing & Appliance Repair-Electrician & Plumber Phoenix, AZ.

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.oneshotinstallation.com/ |
| Calificación | 4.9/5 (176 reseñas) |
| Teléfono | (602) 791-5659 |
| Dirección | 12370 N 83rd Ave, Peoria, AZ 85381, USA, Peoria, AZ, 85381 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 176 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (23 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 24 | N/A |
| testimony | 22 | N/A |
| service | 20 | N/A |
| electrician | 16 | N/A |
| flagstaff | 16 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 10 | 47 | Below |
| Avg Word Count | 419 | - | Average |
| Thin Content (<300) | 6 (60%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 68 | Needs Improvement |
| Desktop | 86 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.8s | ≤2.5s | Needs Work |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 176 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 10 Páginas |
| Técnico | 77/100 | Puntuación móvil 68 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### P3 Plumbing AZ

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://p3plumbingaz.com/ |
| Calificación | 5.0/5 (216 reseñas) |
| Teléfono | (623) 271-2941 |
| Dirección | 29516 N 223rd Dr, Wittmann, AZ 85361, USA, Wittmann, AZ, 85361 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 216 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Vue.js, Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| menu | 10520 | N/A |
| item | 8989 | N/A |
| class | 4559 | N/A |
| https | 4202 | N/A |
| com | 4114 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 94 | 47 | Above |
| Avg Word Count | 947 | - | Good |
| Thin Content (<300) | 36 (38%) | - | Needs Work |
| Rich Content (>1000) | 53 (56%) | - | Excellent |

**Content Distribution:**
- Service pages: 1
- Location pages: 20
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 64 | Needs Improvement |
| Desktop | 91 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.7s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 11 |
| Empty Links | 0 |
| Form Labels Missing | 5 |

**Issues:** Missing skip link, Missing lang attribute, 5 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 216 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 94 Páginas |
| Técnico | 77/100 | Puntuación móvil 64 |
| Marca | 20/100 | 0.9 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### POP Plumbing LLC - Glendale

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://popplumbing.co/ |
| Calificación | 5.0/5 (155 reseñas) |
| Teléfono | (602) 529-0025 |
| Dirección | 8355 W Midway Ave, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 155 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Vue.js, Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| astro | 96 | N/A |
| let | 60 | N/A |
| getattribute | 52 | N/A |
| new | 52 | N/A |
| component | 44 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 8 | 47 | Below |
| Avg Word Count | 252 | - | Thin |
| Thin Content (<300) | 8 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 67 | Needs Improvement |
| Desktop | 95 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 9 |
| Form Labels Missing | 3 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links, 3 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 155 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 8 Páginas |
| Técnico | 81/100 | Puntuación móvil 67 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Parker & Sons

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.parkerandsons.com/?utm_campaign=gmb_pk-phx_home_cus-all_googlebusinessprofile&utm_medium=gmb&utm_source=google |
| Calificación | 4.7/5 (31728 reseñas) |
| Teléfono | (602) 424-9619 |
| Dirección | 3636 E Anne St A, Phoenix, AZ 85040, USA, Phoenix, AZ, 85040 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 31728 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | ServiceTitan | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| window | 16698 | N/A |
| digitaldata | 10600 | N/A |
| var | 9114 | N/A |
| dlobj | 8600 | N/A |
| digitallaunchdata | 8400 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4127 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 6
- Location pages: 7
- Blog posts: 140
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 44 | Poor |
| Desktop | 45 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 26.2s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 1 |
| Avg Position | 1.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 1 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 94/100 | 31728 reseñas |
| SERP | 3/100 | 1 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 44/100 | Puntuación móvil 44 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (44) con 80+


---

### Patriotic Plumbing And Rooter

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://patrioticplumbingandrooter.com/ |
| Calificación | 4.9/5 (293 reseñas) |
| Teléfono | (602) 755-9373 |
| Dirección | 14208 N 138th Dr, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 293 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Housecall Pro, ScheduleOnce, Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| rpi | 53352 | N/A |
| var | 45096 | N/A |
| color | 31191 | N/A |
| important | 27079 | N/A |
| background | 16524 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 182 | 47 | Above |
| Avg Word Count | 4430 | - | Good |
| Thin Content (<300) | 6 (3%) | - | Good |
| Rich Content (>1000) | 176 (96%) | - | Excellent |

**Content Distribution:**
- Service pages: 53
- Location pages: 80
- Blog posts: 77
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 83 | Good |
| Desktop | 69 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.1s | ≤2.5s | Needs Work |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 13 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 13 empty links, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 293 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 182 Páginas |
| Técnico | 76/100 | Puntuación móvil 83 |
| Marca | 75/100 | 5.5 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo
- Presencia de marca establecida


---

### Peoria Plumbing & Drain Experts

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://peoriaplumbingdrainexperts.site/ |
| Calificación | 5.0/5 (22 reseñas) |
| Teléfono | (623) 283-4574 |
| Dirección | 9772 N Lake Pleasant Pkwy, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 22 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 22 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | 0.2 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Phay Plumbing services LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://phayplumbingaz.com/ |
| Calificación | 5.0/5 (253 reseñas) |
| Teléfono | (602) 291-0525 |
| Dirección | 15941 W Madison St, Goodyear, AZ 85338, USA, Goodyear, AZ, 85338 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 253 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 2 | 2 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| photos | 17480 | N/A |
| checkin | 15470 | N/A |
| https | 11979 | N/A |
| com | 11111 | N/A |
| plumbing | 10915 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 97 | 47 | Above |
| Avg Word Count | 6890 | - | Good |
| Thin Content (<300) | 8 (8%) | - | Good |
| Rich Content (>1000) | 89 (91%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 28
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 63 | Needs Improvement |
| Desktop | 83 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 11.3s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 0 |
| Form Labels Missing | 7 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 7 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 253 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 97 Páginas |
| Técnico | 73/100 | Puntuación móvil 63 |
| Marca | 50/100 | 2.9 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### Phoenician Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.phoenicianplumbing.com/?utm_source=google&utm_medium=wix_google_business_profile&utm_campaign=16294771040885588611 |
| Calificación | 4.8/5 (25 reseñas) |
| Teléfono | (623) 290-3272 |
| Dirección | 9007 W Malapai Dr, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 25 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 58/100 | 25 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Phoenix Pipe Bursting

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://phoenixpipebursting.com/?utm_source=local&utm_medium=organic&utm_campaign=gbp |
| Calificación | 5.0/5 (4 reseñas) |
| Teléfono | (602) 900-9050 |
| Dirección | 8550 N 91st Ave #83, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 4
- Standard local operator profile: 4 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Housecall Pro | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| color | 660 | N/A |
| important | 511 | N/A |
| preset | 495 | N/A |
| var | 486 | N/A |
| vivid | 315 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 10 | 47 | Below |
| Avg Word Count | 3627 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 10 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 10
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 80 | Good |
| Desktop | 98 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.6s | ≤2.5s | Needs Work |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 4 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 10 Páginas |
| Técnico | 89/100 | Puntuación móvil 80 |
| Marca | 20/100 | 0.4 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Pink Plumbing and Sewer

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.pinkplumbingandsewer.com/ |
| Calificación | 4.9/5 (189 reseñas) |
| Teléfono | (602) 562-5290 |
| Dirección | 2375 E Camelback Rd #600, Phoenix, AZ 85016, USA, Phoenix, AZ, 85016 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 189 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| com | 221 | N/A |
| https | 221 | N/A |
| plumbing | 220 | N/A |
| pinkplumbingandsewer | 219 | N/A |
| sewer | 192 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 48 | 47 | Average |
| Avg Word Count | 633 | - | Average |
| Thin Content (<300) | 10 (20%) | - | Needs Work |
| Rich Content (>1000) | 6 (12%) | - | Good |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.1s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 15.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 15 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 189 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 40/100 | 48 Páginas |
| Técnico | 68/100 | Puntuación móvil 57 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Average across all dimensions


---

### PlumbSmart Plumbing Heating and Air

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://itsjustplumbsmart.com/ |
| Calificación | 5.0/5 (262 reseñas) |
| Teléfono | (623) 250-2238 |
| Dirección | 2550 W Union Hills Dr Suite 350-364, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 262 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | ServiceTitan, Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 32 | 4 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 10209 | N/A |
| var | 5519 | N/A |
| replacement | 5100 | N/A |
| repair | 4879 | N/A |
| return | 4517 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1403 | - | Good |
| Thin Content (<300) | 4 (1%) | - | Good |
| Rich Content (>1000) | 223 (96%) | - | Excellent |

**Content Distribution:**
- Service pages: 43
- Location pages: 4
- Blog posts: 184
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 99 | Excellent |
| Desktop | 89 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.7s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 6 |
| Form Labels Missing | 16 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links, 16 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 262 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 94/100 | Puntuación móvil 99 |
| Marca | 90/100 | 19.5 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo
- Presencia de marca establecida


---

### Plumbers Near Me - Water Heater & Plumbing Services of Sun City

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (8 reseñas) |
| Teléfono | (623) 866-5711 |
| Dirección | 10451 W Palmeras Dr, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 8
- Standard local operator profile: 8 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 8 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Plumbing Masters

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://plumbingmastersaz.com/?utm_source=google&utm_medium=gbp |
| Calificación | 4.9/5 (3921 reseñas) |
| Teléfono | (602) 607-1405 |
| Dirección | 9299 W Olive Ave Building 2, Suite 207, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 3921 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Vue.js, Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 46 | 3 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| width | 21331 | N/A |
| border | 20196 | N/A |
| text | 15513 | N/A |
| content | 13083 | N/A |
| top | 13044 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 161 | 47 | Above |
| Avg Word Count | 3293 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 161 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 66
- Location pages: 10
- Blog posts: 52
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 48 | Poor |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.2s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 5 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 5 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 3921 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 161 Páginas |
| Técnico | 57/100 | Puntuación móvil 48 |
| Marca | 90/100 | 13.2 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo
- Presencia de marca establecida


---

### Pridemark Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://pridemarkplumbing.com/?utm_source=gmb&utm_medium=social&utm_campaign=1seo_gmb |
| Calificación | 4.9/5 (316 reseñas) |
| Teléfono | (623) 239-2606 |
| Dirección | 15151 W Dahlia Dr, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 316 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 3152 | N/A |
| https | 3097 | N/A |
| water | 3076 | N/A |
| true | 2904 | N/A |
| com | 2872 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 364 | 47 | Above |
| Avg Word Count | 1267 | - | Good |
| Thin Content (<300) | 134 (36%) | - | Needs Work |
| Rich Content (>1000) | 230 (63%) | - | Excellent |

**Content Distribution:**
- Service pages: 58
- Location pages: 9
- Blog posts: 10
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 38 | Poor |
| Desktop | 68 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 11.8s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 2 |
| Form Labels Missing | 4 |

**Issues:** Missing skip link, Missing lang attribute, 4 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 316 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 364 Páginas |
| Técnico | 53/100 | Puntuación móvil 38 |
| Marca | 75/100 | 7.8 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content, established brand

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo
- Presencia de marca establecida


---

### Pro Plumbers Surprise

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (26 reseñas) |
| Teléfono | (623) 220-5602 |
| Dirección | 16525 N 165th Ave, Surprise, AZ 85388, USA, Surprise, AZ, 85388 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 26 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 26 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Proforce Plumbing Sewer & Drain

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://proforceplumbing.com/ |
| Calificación | 4.9/5 (75 reseñas) |
| Teléfono | (623) 323-8800 |
| Dirección | 8969 W Maryland Ave, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 75 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"5.5.17"}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| menu | 6988 | N/A |
| jquery | 4003 | N/A |
| oxy | 3800 | N/A |
| pro | 3180 | N/A |
| function | 1458 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 74 | 47 | Above |
| Avg Word Count | 1373 | - | Good |
| Thin Content (<300) | 8 (10%) | - | Good |
| Rich Content (>1000) | 66 (89%) | - | Excellent |

**Content Distribution:**
- Service pages: 24
- Location pages: 7
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 65 | Needs Improvement |
| Desktop | 65 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.2s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 75 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 74 Páginas |
| Técnico | 65/100 | Puntuación móvil 65 |
| Marca | 75/100 | 5.7 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: established brand

**Fortalezas:**
- Presencia de marca establecida


---

### Rapid Rooter Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://rapidrooteraz.com/ |
| Calificación | 5.0/5 (187 reseñas) |
| Teléfono | (623) 581-0346 |
| Dirección | 4123 W Saguaro Park Ln, Glendale, AZ 85310, USA, Glendale, AZ, 85310 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 187 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Housecall Pro, Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 11 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 12099 | N/A |
| function | 10004 | N/A |
| com | 8605 | N/A |
| rapidrooteraz | 7959 | N/A |
| content | 7677 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1463 | - | Good |
| Thin Content (<300) | 4 (1%) | - | Good |
| Rich Content (>1000) | 223 (96%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 5
- Blog posts: 1
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 41 | Poor |
| Desktop | 41 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 22.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 6 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 187 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 41/100 | Puntuación móvil 41 |
| Marca | 90/100 | 16.3 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong in strong reputation, deep content, established brand; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo
- Presencia de marca establecida

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (41) con 80+


---

### Right On Time Plumbing & Drain

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 4.8/5 (24 reseñas) |
| Teléfono | (623) 698-1993 |
| Dirección | 8133 W Hatcher Rd, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 24 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 58/100 | 24 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Rivers Plumbing Services

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.riversplumbingservices.com/ |
| Calificación | 4.9/5 (39 reseñas) |
| Teléfono | N/A |
| Dirección | 11352 W Primrose Dr, Avondale, AZ 85392, USA, Avondale, AZ, 85392 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 39 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 1511 | N/A |
| specs | 1500 | N/A |
| return | 894 | N/A |
| const | 736 | N/A |
| thunderbolt | 658 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 12 | 47 | Below |
| Avg Word Count | 931 | - | Good |
| Thin Content (<300) | 8 (66%) | - | Needs Work |
| Rich Content (>1000) | 4 (33%) | - | Excellent |

**Content Distribution:**
- Service pages: 12
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | 92 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 59/100 | 39 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 12 Páginas |
| Técnico | 71/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Roadrunner Plumber

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://roadrunnerplumber.com/ |
| Calificación | 4.9/5 (108 reseñas) |
| Teléfono | (602) 579-7612 |
| Dirección | 17786 W Gambit Trail, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 108 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 3 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 33 | Poor |
| Desktop | 44 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.4s | ≤2.5s | Fail ✗ |
| CLS | 0.80 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 108 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 38/100 | Puntuación móvil 33 |
| Marca | 75/100 | 7.8 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in established brand; vulnerable in poor technical performance, thin content

**Fortalezas:**
- Presencia de marca establecida

**Debilidades:**
- Mal rendimiento móvil
- Contenido delgado

**Oportunidades a Explotar:**
- Superar su puntuación móvil (33) con 80+
- Crear contenido más profundo que sus páginas delgadas


---

### Robins Plumbing Inc

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.robinsplumbing.com/ |
| Calificación | 4.9/5 (1121 reseñas) |
| Teléfono | (623) 486-4657 |
| Dirección | 5955 W Peoria Ave #5160, Glendale, AZ 85302, USA, Glendale, AZ, 85302 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1121 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 7 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 9486 | N/A |
| gform | 7041 | N/A |
| plumbing | 6726 | N/A |
| var | 6248 | N/A |
| content | 5560 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2202 | - | Good |
| Thin Content (<300) | 8 (3%) | - | Good |
| Rich Content (>1000) | 220 (95%) | - | Excellent |

**Content Distribution:**
- Service pages: 10
- Location pages: 14
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 0 |
| Avg Position | 8.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 8 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 1121 reseñas |
| SERP | 3/100 | 1 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo


---

### Rooter Ranger

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.rooterranger.com/service-areas/arizona/sun-city/?utm_source=google&utm_medium=GBP |
| Calificación | 4.9/5 (311 reseñas) |
| Teléfono | (623) 469-5841 |
| Dirección | 9849 W Bell Rd, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 311 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Vue.js, Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (1 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 60 | Needs Improvement |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.8s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 311 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 55/100 | Puntuación móvil 60 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Rooter Relief Plumbing & Drains

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.rooterreliefplumbing.com/ |
| Calificación | 5.0/5 (23 reseñas) |
| Teléfono | (818) 484-0922 |
| Dirección | 5042 N 65th Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 23 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (8 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| astro | 21 | N/A |
| cid | 21 | N/A |
| data | 21 | N/A |
| rect | 20 | N/A |
| jlpqxutv | 13 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 156 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 69 | Needs Improvement |
| Desktop | 94 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.5s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 23 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 81/100 | Puntuación móvil 69 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Roto-Rooter Plumbing & Water Cleanup

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.rotorooter.com/surpriseaz/?utm_source=Google&utm_medium=organic&utm_campaign=gmb&utm_content=website |
| Calificación | 5.0/5 (481 reseñas) |
| Teléfono | (602) 466-7304 |
| Dirección | 12133 W Bell Rd #104, Surprise, AZ 85378, USA, Surprise, AZ, 85378 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 481 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| null | 99632 | N/A |
| typename | 76215 | N/A |
| plumbing | 67408 | N/A |
| src | 41429 | N/A |
| water | 35467 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 5957 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 203 (88%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 65
- Blog posts: 41
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 36 | Poor |
| Desktop | 61 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 481 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 48/100 | Puntuación móvil 36 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (36) con 80+


---

### Roto-Rooter Plumbing & Water Cleanup

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.rotorooter.com/suncityaz/?utm_source=Google&utm_medium=organic&utm_campaign=gmb&utm_content=website |
| Calificación | 4.9/5 (315 reseñas) |
| Teléfono | (623) 696-4812 |
| Dirección | 12630 N 103rd Ave # 112, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 315 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| null | 98664 | N/A |
| typename | 75176 | N/A |
| plumbing | 64895 | N/A |
| src | 40660 | N/A |
| water | 36770 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 6018 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 203 (88%) | - | Excellent |

**Content Distribution:**
- Service pages: 9
- Location pages: 60
- Blog posts: 41
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 33 | Poor |
| Desktop | 49 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.1s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 315 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 41/100 | Puntuación móvil 33 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (33) con 80+


---

### Roto-Rooter Plumbing & Water Cleanup

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.rotorooter.com/glendaleaz/?utm_source=Google&utm_medium=organic&utm_campaign=gmb&utm_content=website |
| Calificación | 4.8/5 (2747 reseñas) |
| Teléfono | (623) 687-2008 |
| Dirección | 7250 W Frier Dr #105, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 2747 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| null | 99712 | N/A |
| typename | 76302 | N/A |
| plumbing | 67409 | N/A |
| src | 41432 | N/A |
| water | 35513 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 5983 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 203 (88%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 65
- Blog posts: 41
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 45 | Poor |
| Desktop | 66 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.8s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 12.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 12 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 95/100 | 2747 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 55/100 | Puntuación móvil 45 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo


---

### Sav-On Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://sav-onplumbing.com/ |
| Calificación | 4.8/5 (140 reseñas) |
| Teléfono | (623) 487-9500 |
| Dirección | 7110 N 45th Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 140 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| tve | 12606 | N/A |
| important | 9017 | N/A |
| data | 7893 | N/A |
| css | 6313 | N/A |
| message | 3846 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1763 | - | Good |
| Thin Content (<300) | 10 (4%) | - | Good |
| Rich Content (>1000) | 208 (90%) | - | Excellent |

**Content Distribution:**
- Service pages: 31
- Location pages: 20
- Blog posts: 5
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 59 | Needs Improvement |
| Desktop | 92 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.5s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 6 |
| Form Labels Missing | 4 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links, 4 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 68/100 | 140 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 75/100 | Puntuación móvil 59 |
| Marca | 90/100 | 20.6 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: good technical performance, deep content, established brand

**Fortalezas:**
- Buen rendimiento técnico
- Contenido completo
- Presencia de marca establecida


---

### Sav-On Plumbing - Sun City

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://sav-onplumbing.com/contact-us/service-areas/plumbing-in-sun-city-az/ |
| Calificación | 4.9/5 (62 reseñas) |
| Teléfono | (623) 537-9898 |
| Dirección | 9508 W Hidden Valley Cir, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 62 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| tve | 12683 | N/A |
| important | 9387 | N/A |
| data | 7980 | N/A |
| css | 6392 | N/A |
| water | 5713 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2051 | - | Good |
| Thin Content (<300) | 16 (6%) | - | Good |
| Rich Content (>1000) | 206 (89%) | - | Excellent |

**Content Distribution:**
- Service pages: 43
- Location pages: 25
- Blog posts: 7
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 79 | Needs Improvement |
| Desktop | 95 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.5s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 62 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 87/100 | Puntuación móvil 79 |
| Marca | 90/100 | 20.6 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: good technical performance, deep content, established brand

**Fortalezas:**
- Buen rendimiento técnico
- Contenido completo
- Presencia de marca establecida


---

### Set Apart Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://setapartplumbing.com/ |
| Calificación | 5.0/5 (188 reseñas) |
| Teléfono | (480) 404-0979 |
| Dirección | 25304 N 144th Dr, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 188 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| block | 27300 | N/A |
| sqs | 15625 | N/A |
| width | 12863 | N/A |
| grid | 11498 | N/A |
| view | 10390 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 218 | 47 | Above |
| Avg Word Count | 1693 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 215 (98%) | - | Excellent |

**Content Distribution:**
- Service pages: 19
- Location pages: 29
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 37 | Poor |
| Desktop | 57 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 19.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 70/100 | 188 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 218 Páginas |
| Técnico | 47/100 | Puntuación móvil 37 |
| Marca | 35/100 | 1.5 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (37) con 80+


---

### Sigma Pro Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.sigmaproplumb.com/ |
| Calificación | 5.0/5 (27 reseñas) |
| Teléfono | (602) 583-5649 |
| Dirección | 22613 N 119th Dr, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 27 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 102 | N/A |
| owned | 71 | N/A |
| plumbing | 61 | N/A |
| cleaningplumbing | 54 | N/A |
| installationplumbing | 54 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 39 | 47 | Average |
| Avg Word Count | 221 | - | Thin |
| Thin Content (<300) | 28 (71%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 76 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.8s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 2 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 27 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 39 Páginas |
| Técnico | 66/100 | Puntuación móvil 56 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Average across all dimensions


---

### Smiley Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://smileyplumbing.com/ |
| Calificación | 4.9/5 (70 reseñas) |
| Teléfono | (623) 583-9400 |
| Dirección | 7918 W Briden Ln, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 70 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 4 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 1917 | N/A |
| document | 1408 | N/A |
| water | 1149 | N/A |
| var | 945 | N/A |
| function | 732 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 139 | 47 | Above |
| Avg Word Count | 676 | - | Average |
| Thin Content (<300) | 13 (9%) | - | Good |
| Rich Content (>1000) | 9 (6%) | - | Opportunity |

**Content Distribution:**
- Service pages: 10
- Location pages: 75
- Blog posts: 5
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 54 | Needs Improvement |
| Desktop | 70 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.1s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 69/100 | 70 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 80/100 | 139 Páginas |
| Técnico | 62/100 | Puntuación móvil 54 |
| Marca | 90/100 | 22.2 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: deep content, established brand

**Fortalezas:**
- Contenido completo
- Presencia de marca establecida


---

### Somers Plumbers - Phoenix Plumbing Company

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.somersplumbers.net/ |
| Calificación | 5.0/5 (292 reseñas) |
| Teléfono | (480) 568-2596 |
| Dirección | 14039 N 8th Pl, Phoenix, AZ 85022, USA, Phoenix, AZ, 85022 |
| Review Context | Above Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 292 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 29 | 2 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 3741 | N/A |
| block | 2706 | N/A |
| sqs | 1683 | N/A |
| plumbing | 1637 | N/A |
| grid | 1504 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 192 | 47 | Above |
| Avg Word Count | 1050 | - | Good |
| Thin Content (<300) | 42 (21%) | - | Needs Work |
| Rich Content (>1000) | 38 (19%) | - | Good |

**Content Distribution:**
- Service pages: 11
- Location pages: 34
- Blog posts: 157
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 38 | Poor |
| Desktop | 71 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 19.9s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 28.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 28 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Poor |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: Poor, Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 292 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 80/100 | 192 Páginas |
| Técnico | 54/100 | Puntuación móvil 38 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo


---

### Southwest Plumbing Services LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.swplumbingservicesaz.com/ |
| Calificación | 5.0/5 (45 reseñas) |
| Teléfono | (480) 999-5678 |
| Dirección | 3216 N 109th Ave, Avondale, AZ 85392, USA, Avondale, AZ, 85392 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 45 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 45 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Spartan Plumbing Solutions LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://spartanplumbingsolutions.com/ |
| Calificación | 4.9/5 (387 reseñas) |
| Teléfono | (602) 366-9077 |
| Dirección | 500 N Estrella Pkwy Suite B2-173, Goodyear, AZ 85338, USA, Goodyear, AZ, 85338 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 387 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 15809 | N/A |
| specs | 14479 | N/A |
| false | 5416 | N/A |
| return | 4480 | N/A |
| bookings | 4258 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 22 | 47 | Below |
| Avg Word Count | 1990 | - | Good |
| Thin Content (<300) | 2 (9%) | - | Good |
| Rich Content (>1000) | 20 (90%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 75 | Needs Improvement |
| Desktop | 92 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.1s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 79/100 | 387 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 22 Páginas |
| Técnico | 83/100 | Puntuación móvil 75 |
| Marca | 20/100 | 0.4 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, good technical performance

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico


---

### Stars 48 Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.stars48plumbing.com/ |
| Calificación | 5.0/5 (16 reseñas) |
| Teléfono | (602) 499-3084 |
| Dirección | 13233 W Tyler Trail, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 16 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (2 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 26 | N/A |
| get | 10 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 6 | 47 | Below |
| Avg Word Count | 146 | - | Thin |
| Thin Content (<300) | 6 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 93 | Excellent |
| Desktop | 98 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.0s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 0 |
| Form Labels Missing | 2 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 16 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 6 Páginas |
| Técnico | 95/100 | Puntuación móvil 93 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in good technical performance; vulnerable in thin content

**Fortalezas:**
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Sun City Action Plumbers

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://bestplumberinsuncity.com/ |
| Calificación | 4.7/5 (15 reseñas) |
| Teléfono | (623) 432-1968 |
| Dirección | 14819 N Del Webb Blvd, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 15 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"4.9.3"}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 1 | 1 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 465 | N/A |
| water | 315 | N/A |
| sewer | 309 | N/A |
| services | 301 | N/A |
| repair | 249 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 64 | 47 | Above |
| Avg Word Count | 847 | - | Good |
| Thin Content (<300) | 4 (6%) | - | Good |
| Rich Content (>1000) | 11 (17%) | - | Good |

**Content Distribution:**
- Service pages: 18
- Location pages: 0
- Blog posts: 2
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 47 | Poor |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.5s | ≤2.5s | Fail ✗ |
| CLS | 0.33 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Minify JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 2 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 57/100 | 15 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 64 Páginas |
| Técnico | 48/100 | Puntuación móvil 47 |
| Marca | 90/100 | 11.9 años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong in established brand; vulnerable in poor technical performance

**Fortalezas:**
- Presencia de marca establecida

**Debilidades:**
- Mal rendimiento móvil

**Oportunidades a Explotar:**
- Superar su puntuación móvil (47) con 80+


---

### Sunland Plumbing & Construction

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.sunlandpc.com/ |
| Calificación | 4.7/5 (93 reseñas) |
| Teléfono | (623) 933-4170 |
| Dirección | 13200 N 113th Ave #5th, Youngtown, AZ 85363, USA, Youngtown, AZ, 85363 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 93 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| obj | 9999 | N/A |
| endobj | 9994 | N/A |
| stream | 8076 | N/A |
| endstream | 7750 | N/A |
| adobed | 3096 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 56 | 47 | Average |
| Avg Word Count | 12676 | - | Good |
| Thin Content (<300) | 2 (3%) | - | Good |
| Rich Content (>1000) | 30 (53%) | - | Excellent |

**Content Distribution:**
- Service pages: 18
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 71 | Needs Improvement |
| Desktop | 96 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 67/100 | 93 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 60/100 | 56 Páginas |
| Técnico | 83/100 | Puntuación móvil 71 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Sunstate Plumbing, Inc

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.sunstateplumbinginc.com/ |
| Calificación | 4.8/5 (104 reseñas) |
| Teléfono | (623) 937-4258 |
| Dirección | 8701 N 78th Ave, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 104 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Framework | Angular, jQuery, Bootstrap | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 47 | 16 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 758 | N/A |
| plumbing | 632 | N/A |
| water | 618 | N/A |
| service | 601 | N/A |
| script | 480 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 70 | 47 | Above |
| Avg Word Count | 1170 | - | Good |
| Thin Content (<300) | 3 (4%) | - | Good |
| Rich Content (>1000) | 38 (54%) | - | Excellent |

**Content Distribution:**
- Service pages: 3
- Location pages: 2
- Blog posts: 10
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 95 | Excellent |
| Desktop | 95 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.0s | ≤2.5s | Pass ✓ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 30.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 30 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 12 |
| Empty Links | 13 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 13 empty links, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 68/100 | 104 reseñas |
| SERP | 1/100 | 1 palabras clave rastreadas |
| Contenido | 60/100 | 70 Páginas |
| Técnico | 95/100 | Puntuación móvil 95 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### Surprise Plumber and Handyman

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://surpriseplumbingandhandyman.com/ |
| Calificación | 5.0/5 (7 reseñas) |
| Teléfono | (602) 643-6000 |
| Dirección | 13856 W Country Gables Dr, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 7
- Standard local operator profile: 7 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| code | 507 | N/A |
| name | 507 | N/A |
| phonecode | 490 | N/A |
| services | 124 | N/A |
| plumbing | 105 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 39 | 47 | Average |
| Avg Word Count | 316 | - | Thin |
| Thin Content (<300) | 24 (61%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 6
- Location pages: 39
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 60 | Needs Improvement |
| Desktop | 82 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.1s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 7 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 39 Páginas |
| Técnico | 71/100 | Puntuación móvil 60 |
| Marca | 20/100 | 0.9 años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: good technical performance

**Fortalezas:**
- Buen rendimiento técnico


---

### The Aussie Plumber

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.theaussieplumber.com/ |
| Calificación | 5.0/5 (899 reseñas) |
| Teléfono | (602) 820-5551 |
| Dirección | 4600 E Shea Blvd Ste 203, Phoenix, AZ 85028, USA, Phoenix, AZ, 85028 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 899 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| Reservas | Square Appointments | Alta |
| Framework | Vue.js, Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Exitosas** (1 palabra clave capturando demanda de búsqueda)

| Palabra Clave | Volumen | Frecuencia | Páginas |
|---------|--------|-----------|-------|
| repiping | 1,900 | 34 | 2 |

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| important | 3923 | N/A |
| 0rem | 3096 | N/A |
| margin | 2698 | N/A |
| padding | 2259 | N/A |
| bottom | 1140 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 122 | 47 | Above |
| Avg Word Count | 1170 | - | Good |
| Thin Content (<300) | 5 (4%) | - | Good |
| Rich Content (>1000) | 79 (64%) | - | Excellent |

**Content Distribution:**
- Service pages: 64
- Location pages: 8
- Blog posts: 3
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 54 | Needs Improvement |
| Desktop | 81 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 15.5s | ≤2.5s | Fail ✗ |
| CLS | 0.08 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Clasificaciones SERP

**Resumen**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 0 |
| Avg Position | 7.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 7 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 6 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 90/100 | 899 reseñas |
| SERP | 3/100 | 1 palabras clave rastreadas |
| Contenido | 80/100 | 122 Páginas |
| Técnico | 67/100 | Puntuación móvil 54 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo


---

### The Family Plumber, LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.callthefamilyplumber.com/?utm_source=GMBlisting&utm_medium=Organic&utm_campaign=GMBwebsite |
| Calificación | 5.0/5 (378 reseñas) |
| Teléfono | (623) 738-6171 |
| Dirección | 17675 W Pershing St, Surprise, AZ 85388, USA, Surprise, AZ, 85388 |
| Review Context | Above 75th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 378 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Reservas | Housecall Pro | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| obj | 2955 | N/A |
| endobj | 2951 | N/A |
| xmp | 2372 | N/A |
| water | 2316 | N/A |
| plumbing | 1727 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 284 | 47 | Above |
| Avg Word Count | 5385 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 136 (47%) | - | Excellent |

**Content Distribution:**
- Service pages: 9
- Location pages: 25
- Blog posts: 3
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 39 | Poor |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 18.4s | ≤2.5s | Fail ✗ |
| CLS | 0.32 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 2 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 1 form fields missing labels

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 80/100 | 378 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 284 Páginas |
| Técnico | 53/100 | Puntuación móvil 39 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong overall: strong reputation, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Contenido completo


---

### The Plumber Guy

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.theplumberguy.com/ |
| Calificación | 4.9/5 (3392 reseñas) |
| Teléfono | (623) 233-4350 |
| Dirección | 9162 W Cactus Rd ste c, Peoria, AZ 85381, USA, Peoria, AZ, 85381 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Enterprise Network |
| Confianza | 80% |

**Evidencia:**
- High review count: 3392 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Reservas | Square Appointments | Alta |
| Framework | Angular, jQuery | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 27740 | N/A |
| var | 18251 | N/A |
| jquery | 16207 | N/A |
| gform | 13735 | N/A |
| return | 13710 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 3504 | - | Good |
| Thin Content (<300) | 6 (2%) | - | Good |
| Rich Content (>1000) | 220 (95%) | - | Excellent |

**Content Distribution:**
- Service pages: 67
- Location pages: 75
- Blog posts: 117
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 73 | Needs Improvement |
| Desktop | 88 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 3 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 96/100 | 3392 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 95/100 | 230 Páginas |
| Técnico | 80/100 | Puntuación móvil 73 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: HIGH**

**Evaluación:** Strong overall: strong reputation, good technical performance, deep content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico
- Contenido completo


---

### The Plumber Guy

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (2 reseñas) |
| Teléfono | N/A |
| Dirección | Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 2
- Standard local operator profile: 2 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 2 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### The Trusted Plumber

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.thetrustedplumber.com/ |
| Calificación | 4.7/5 (31 reseñas) |
| Teléfono | (623) 201-4565 |
| Dirección | 7611 N 74th Ave #2, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Below Median |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 31 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 37 | Poor |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.5s | ≤2.5s | Fail ✗ |
| CLS | 0.29 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 57/100 | 31 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 46/100 | Puntuación móvil 37 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: poor technical performance, thin content

**Debilidades:**
- Mal rendimiento móvil
- Contenido delgado

**Oportunidades a Explotar:**
- Superar su puntuación móvil (37) con 80+
- Crear contenido más profundo que sus páginas delgadas


---

### Tom's Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 3.7/5 (3 reseñas) |
| Teléfono | (623) 933-6363 |
| Dirección | 5323 N Tuthill Rd, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 3
- Standard local operator profile: 3 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 47/100 | 3 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Trident Plumbing & Drain

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.tridentplumbingllc.com/service-areas/peoria-az/?utm_source=gbp&utm_medium=organic&utm_campaign=peoria |
| Calificación | 5.0/5 (1277 reseñas) |
| Teléfono | (623) 879-2020 |
| Dirección | 26134 N 121st Ave, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Statistical Outlier ⚠ |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Regional Brand |
| Confianza | 50% |

**Evidencia:**
- Regional review count: 1277 (range: 500-2000)

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 106 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 73 | Needs Improvement |
| Desktop | 83 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 97/100 | 1277 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 78/100 | Puntuación móvil 73 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Fortalezas:**
- Fuerte volumen de reseñas y calificaciones
- Buen rendimiento técnico

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Vintage Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | https://www.vintageplumbingaz.com/ |
| Calificación | 5.0/5 (13 reseñas) |
| Teléfono | (602) 872-6774 |
| Dirección | 15152 W Calavar Rd, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 13 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Framework | Angular | Media |

#### Análisis de Palabras Clave

**Palabras Clave Desperdiciadas** (30 palabra clave baja/sin demanda de búsqueda)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| name | 756 | N/A |
| code | 750 | N/A |
| phonecode | 735 | N/A |
| block | 556 | N/A |
| sqs | 369 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 24 | 47 | Below |
| Avg Word Count | 933 | - | Good |
| Thin Content (<300) | 3 (12%) | - | Good |
| Rich Content (>1000) | 6 (25%) | - | Excellent |

**Content Distribution:**
- Service pages: 3
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 53 | Needs Improvement |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 21.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 13 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 40/100 | 24 Páginas |
| Técnico | 54/100 | Puntuación móvil 53 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Average across all dimensions


---

### Ward Plumbing & Drain Service LLC.

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | http://www.wardplumbingservices.com/ |
| Calificación | 4.7/5 (12 reseñas) |
| Teléfono | (623) 298-9643 |
| Dirección | 7407 N 185th Ave, Waddell, AZ 85355, USA, Waddell, AZ, 85355 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 12 reviews

#### Stack Tecnológico

| Categoría | Tecnología | Confianza |
|----------|------------|------------|

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Rendimiento Técnico

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 64 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.0s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 57/100 | 12 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 2 Páginas |
| Técnico | 60/100 | Puntuación móvil 57 |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Water Fighters Plumbing

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (15 reseñas) |
| Teléfono | (602) 884-5325 |
| Dirección | 23241 N 87th Dr, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 15 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 15 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Xcel Plumbing Glendale

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (24 reseñas) |
| Teléfono | (480) 264-8585 |
| Dirección | 5905 W Bell Rd #198, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Standard local operator profile: 24 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 24 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

### Xtreme Plumbing LLC

#### Resumen

| Métrica | Valor |
|--------|-------|
| Sitio Web | N/A |
| Calificación | 5.0/5 (5 reseñas) |
| Teléfono | (480) 709-1143 |
| Dirección | 9027 W Griswold Rd, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Clasificación de Entidad

| Attribute | Valor |
|-----------|-------|
| Clase | Local Operator |
| Confianza | 60% |

**Evidencia:**
- Very low review count: 5
- Standard local operator profile: 5 reviews

#### Análisis de Palabras Clave

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Análisis de Contenido

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Evaluación Competitiva

**Análisis de Poder Competitivo**

| Dimensión | Puntuación | Contexto |
|-----------|-------|---------|
| Reputación | 60/100 | 5 reseñas |
| SERP | 0/100 | 0 palabras clave rastreadas |
| Contenido | 20/100 | 0 Páginas |
| Técnico | 50/100 | Puntuación móvil N/A |
| Marca | 20/100 | N/A años |

**Nivel de Amenaza: MEDIUM**

**Evaluación:** Weak overall: thin content

**Debilidades:**
- Contenido delgado

**Oportunidades a Explotar:**
- Crear contenido más profundo que sus páginas delgadas


---

---

## 6. Análisis Cruzado de Competidores

### 6.1 Technology Adoption Trends

**CMS/Platform Distribution:**

| Platform | Count | % |
|----------|-------|---|
| WordPress | 39 | 40% |
| Angular | 30 | 30% |
| GoDaddy Website Builder | 5 | 5% |
| Squarespace | 5 | 5% |
| Wix | 5 | 5% |
| Vue.js | 4 | 4% |
| cloudflare (server) | 3 | 3% |
| Custom | 2 | 2% |
| jQuery | 1 | 1% |
| Webflow | 1 | 1% |

### 6.2 Performance Distribution

**Mobile Score Distribution:**

| Range | Count | % |
|-------|-------|---|
| Poor (0-49) | 32 | 31% |
| Needs Improvement (50-79) | 56 | 55% |
| Good (80-89) | 5 | 5% |
| Excellent (90+) | 9 | 9% |

### 6.3 Competitive Clustering

Based on entity classification and competitive power analysis:

| Cluster | Count | Description |
|---------|-------|-------------|
| Local Operators | 96 | Single location, <500 reviews |
| Regional Brands | 18 | Multiple locations or 500-2000 reviews |
| Enterprise Networks | 8 | Large operations, >2000 reviews |
| Brand Aggregators | 0 | Multi-service companies |

---

## 7. ADA Compliance Analysis

Website accessibility (ADA compliance) is increasingly important for both legal risk and SEO ranking. Google considers accessibility signals in search rankings.

### 7.1 Market-Wide Compliance Issues

| Issue | Count | % of Sites |
|-------|-------|------------|
| Poor/No Alt Text | 19 | 24% |
| Missing Skip Links | 78 | 100% |
| No H1 Heading | 17 | 22% |
| Empty Links (>3) | 21 | 27% |
| Form Fields Missing Labels | 24 | 31% |

### 7.2 Competitors with Multiple ADA Issues

| Competitor | Reviews | Issues |
|------------|---------|--------|
| Plumbing Masters | 3921 | Alt text: None, 5 empty links |
| Christian Brothers Plumbing, A/C, & Electrical | 2105 | 5 empty links, 8 form fields missing labels |
| 100% Plumbing | 1595 | Alt text: None, 7 form fields missing labels |
| Grand Canyon Home Services | 331 | Alt text: None, 6 empty links |
| Patriotic Plumbing And Rooter | 293 | 13 empty links, 1 form fields missing labels |
| PlumbSmart Plumbing Heating and Air | 262 | 6 empty links, 16 form fields missing labels |
| Phay Plumbing services LLC | 253 | Alt text: None, 7 form fields missing labels |
| Pink Plumbing and Sewer | 189 | Alt text: None, No H1 heading |
| All Drains Emergency Plumbing | 186 | 9 empty links, 3 form fields missing labels |
| Hotrod plumbing | 159 | Alt text: None, 16 empty links, 1 form fields missing labels |
| POP Plumbing LLC - Glendale | 155 | 9 empty links, 3 form fields missing labels |
| Sav-On Plumbing | 140 | 6 empty links, 4 form fields missing labels |
| Alpha-Plumbing Services | 113 | Alt text: None, 1 form fields missing labels |
| Forrest Anderson Plumbing & Air Conditioning | 108 | No H1 heading, 11 form fields missing labels |
| Sunstate Plumbing, Inc | 104 | 13 empty links, 1 form fields missing labels |

*Note: ADA non-compliance creates legal liability. Serial ADA litigants actively target businesses with accessibility issues.*

---

## 8. Apéndices

### Appendix A: Data Dictionary

| Field | Description |
|-------|-------------|
| place_id | Google's unique identifier for a business |
| review_count | Total Google reviews at time of collection |
| mobile_score | Lighthouse performance score (0-100) |
| LCP | Largest Contentful Paint - time until largest element loads |
| INP | Interaction to Next Paint - responsiveness metric |
| CLS | Cumulative Layout Shift - visual stability metric |

### Appendix B: Glossary

**Core Web Vitals:** Google's three key metrics for user experience: LCP, INP, CLS.

**IQR (Interquartile Range):** Q3 - Q1. Used for outlier detection.

**Entity Classification:** Categorization of competitors by scale and market position.

**Boilerplate:** Repeated content appearing on multiple pages (nav, footer, etc.).

### Appendix C: Reproducibility

**Tool:** plumber (Rust CLI)

**Data Collection Commands:**
```bash
# Discover competitors
plumber research discover --zip-codes "85301,85374,..."

# Crawl websites
plumber crawl all --max-pages 50

# Analyze performance
plumber analyze performance --all

# Generate report
plumber research ai-report comprehensive
```

---

*Report generated by Plumber Market Research Platform*

---

**Preparado por [South City Computer](https://southcitycomputer.com)**

Derechos de Autor 2026 [South City Computer](https://southcitycomputer.com). Todos los derechos reservados.

Estos datos de investigación son propietarios y confidenciales. La reproducción o distribución no autorizada está prohibida.
