# ⚡ Proyecto Ejecutivo: Instalación Eléctrica Residencial (AEA 90364-7-770)

 Legajo técnico de ingeniería de detalle y proyecto ejecutivo para la instalación eléctrica trifásica embutida de una vivienda unifamiliar ubicada en Resistencia, Chaco.

---

## 📋 Resumen del Proyecto

* **Ubicación:** Resistencia, Chaco, Argentina
* **Superficie cubierta:** 72,36 m²
* **Alimentación:** Trifásica ($220/380\text{ V} - 50\text{ Hz}$)
* **Grado de Electrificación:** Superior (>6 circuitos y >11 kVA)
* **Normativa de aplicación:** Reglamentación AEA 90364-7-770
* **Formato de entrega:** Legajo técnico unificado en PDF (7 láminas ejecutivas)

---

## ⚙️ Parámetros Técnicos y Criterios de Diseño

### 1. Balance de Cargas y Fases
* **Potencia Total Instalada:** $25.930\text{ VA}$
* **Demanda Máxima Prevista (DPMS):** $24.643\text{ VA}$
* **Simetría de Fases:** Desbalance del **4,52%** (*IDEAL*) entre las fases $R$, $S$ y $T$.

### 2. Dimensionamiento de Alimentador y Protecciones
* **Alimentador Principal:** $3 \times 16\text{ mm}^2 + \text{PE } 16\text{ mm}^2$ (IRAM NM 247-3).
* **Capacidad Admisible Corregida:** $I_z = 51,33\text{ A}$ (Método B1, factor de corrección por agrupamiento/temperatura $f = 0,87$).
* **Coordinación de Protecciones:** Cumplimiento de $I_b \le I_n \le I_z$ ($37,44\text{ A} \le 50\text{ A} \le 51,33\text{ A}$).
* **Selectividad en Serie:** Interruptor General Principal (IGP de $63\text{ A}$) en Tablero Principal (TP) e Interruptor Seccional (IS de $50\text{ A}$) en Tablero Seccional (TS).
* **Protección Diferencial:** Interruptores diferenciales selectivos (Tipo S, $300\text{ mA}$) en cabecera e ID instantáneos de $30\text{ mA}$ por grupo de circuitos. Protecciones contra sobretensiones transitorias mediante DPS Tipo 2.

### 3. Sistema de Puesta a Tierra (PAT)
* **Electrodo Dispersor:** Jabalina de acero-cobre IRAM 2309 $\varnothing 5/8'' \times 1,5\text{ m}$.
* **Conductor de Protección:** Unipolar verde-amarillo $1 \times 16\text{ mm}^2$.
* **Cámara de Inspección:** $30 \times 30\text{ cm}$ accesible con morseto de bronce silicio para control periódico con telurímetro.

---

## 📄 Estructura del Legajo Técnico (7 Láminas)

| Lámina | Código | Contenido |
| :--- | :--- | :--- |
| **01** | `PE-VU-001` | Portada, Datos Generales y Memoria Descriptiva Sintética |
| **02** | `PE-VU-002` | Índice y Lista de Documentos del Expediente |
| **03** | `PE-VU-003` | Planta de Instalaciones - Circuitos Seccionales e Iluminación (1:50) |
| **04** | `PE-VU-004` | Planta de Distribución - Tomacorrientes y Fuerza Motriz (1:50) |
| **05** | `PE-VU-005` | Esquema Unifilar General, Planilla de Cargas Integrada y Detalle PAT |
| **06** | `PE-VU-006` | Planilla de Cargas Detallada y Matriz de Balance de Fases |
| **07** | `PE-VU-007` | Disposición Topográfica de Tableros (Frente y Rieles DIN - IP55/IP41) |

---

## 📁 Archivos Adjuntos

El legajo técnico completo compilado en PDF de alta resolución se encuentra alojado en la raíz de este repositorio:
* 📄 [`PE-VU_Proyecto_Electrico_Vivienda_Unifamiliar.pdf`](./PE-VU_Proyecto_Electrico_Vivienda_Unifamiliar.pdf)

---

**Proyectista:** Ing. José Roberto Audicio  
**Especialidad:** Ingeniería Electromecánica | Diseño y Documentación de Instalaciones Eléctricas (AEA)
