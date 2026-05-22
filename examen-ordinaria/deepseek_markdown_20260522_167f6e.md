# EXAMEN ORDINARIO - MME (Montaje y Mantenimiento de Equipos)
**Módulo:** Montaje y Mantenimiento de Equipos  
**Curso:** 1º CFGM SMR  
**Duración:** 2 horas  
**Porcentaje sobre módulo:** 100%

---

## Instrucciones
- Responde en hoja aparte indicando claramente el número de pregunta.
- Parte práctica: realiza las operaciones en el taller y muestra el resultado al profesor.
- Usa vocabulario técnico preciso.
- Cuando se pida un **dibujo o esquema**, realízalo a mano en tu hoja de respuestas.

---

## RA1 – Selección de componentes (30%)

### Pregunta 1.1 [6 puntos]
Explica la función de cada uno de estos componentes y cita **dos fabricantes diferentes** para cada uno, comparando una prestación clave:

- Procesador (CPU)
- Placa base (chipset)
- Memoria RAM
- Unidad de almacenamiento (SSD vs HDD)

### Pregunta 1.2 [8 puntos]
Un cliente quiere montar un equipo para **ofimática básica** y otro para **edición de vídeo profesional**.

**Completa la siguiente tabla:**

| Componente | Equipo ofimática (gama baja) | Equipo edición vídeo (gama alta) |
|------------|-------------------------------|----------------------------------|
| CPU (modelo ejemplo) | | |
| RAM (cantidad y tipo) | | |
| Almacenamiento (tipo y capacidad) | | |
| Tarjeta gráfica | | |

Justifica cada elección.

### Pregunta 1.3 [8 puntos] – PRÁCTICA
En el taller dispones de tres placas base diferentes (marcas y modelos distintos). Identifica:

1. El socket del procesador de cada una.
2. El tipo de RAM compatible (DDR3/DDR4/DDR5).
3. El factor de forma (ATX, Micro-ATX, Mini-ITX).
4. Número de conectores SATA y su velocidad.

**Entrega una tabla con tus respuestas.**

### Pregunta 1.4 [8 puntos]
¿Qué criterios utilizarías para elegir una fuente de alimentación? Explica:
- Potencia recomendada según componentes (método de cálculo).
- Certificaciones de eficiencia (80 Plus, niveles: Bronce, Plata, Oro, Platino, Titanio).
- Conectores necesarios (24 pines, EPS12V, PCIe, SATA, Molex).

---

## RA2 – Ensamblaje de equipos (15%)

### Pregunta 2.1 [7 puntos] – PRÁCTICA
**Ensamblaje completo.** Dispones de: torre, placa base, CPU, disipador, RAM, fuente, SSD/HDD y cables.

Realiza el montaje siguiendo este orden y documenta cada paso con un dibujo esquemático:

1. Instalación CPU + disipador (con pasta térmica correcta)
2. Instalación módulos RAM (dual channel)
3. Colocación separadores y fijación placa base a torre
4. Montaje fuente de alimentación
5. Instalación unidad almacenamiento
6. Conexiones eléctricas (24 pines, EPS12V, SATA, cables panel frontal)
7. Prueba POST

*Al finalizar, muestra al profesor que el equipo emite pitido o imagen en pantalla.*

### Pregunta 2.2 [4 puntos]
Se te proporciona el siguiente texto extraído de un manual real de placa base:

> **Panel frontal (F_PANEL):** Pines 1 y 3: Power LED+ y Power LED- (ánodo y cátodo). Pines 5 y 7: Power SW (sin polaridad). Pin 2 y 4: HDD LED+ y HDD LED-. Pines 6 y 8: Reset SW (sin polaridad).

**Realiza un dibujo a mano** de cómo distribuirías estos cables en un conector macho de 2 filas de 4 pines (formato 2x4). Identifica claramente qué pin corresponde a cada cable.

### Pregunta 2.3 [4 puntos]
Enumera **cinco errores comunes** de montaje y explica cómo prevenir cada uno.

---

## RA3 – Medición de parámetros eléctricos (10%)

### Pregunta 3.1 [3 puntos]
Define y escribe la unidad de medida de:

- Tensión (voltaje) → unidad: _____
- Intensidad (corriente) → unidad: _____
- Resistencia → unidad: _____
- Potencia → unidad: _____

### Pregunta 3.2 [3 puntos]
Diferencia entre **señal digital** y **señal analógica**. Pon un ejemplo de cada una dentro de un PC.

**Dibuja** cómo se verían en un osciloscopio ambas señales (una señal digital cuadrada y una señal analógica sinusoidal).

### Pregunta 3.3 [4 puntos] – PRÁCTICA
Con un **multímetro digital**, realiza las siguientes mediciones en un equipo encendido (con supervisión del profesor):

1. Tensión en el conector de alimentación de 4 pines (EPS12V) – entre pin amarillo (+12V) y negro (GND).
2. Tensión en un conector SATA de alimentación (medir entre rojo y negro: +5V esperado; entre amarillo y negro: +12V esperado).
3. Continuidad en un cable de datos SATA (de extremo a extremo).

**Anota los valores obtenidos y compáralos con los valores teóricos esperados (+-5% de tolerancia).**

---

## RA4 – Mantenimiento de equipos (10%)

### Pregunta 4.1 [4 puntos]
Un equipo se apaga inesperadamente después de 10-15 minutos de uso. Propón **tres posibles causas** y el procedimiento para diagnosticar cada una.

### Pregunta 4.2 [3 puntos]
Explica el procedimiento de limpieza preventiva de un equipo. Especifica:
- Herramientas permitidas (aire comprimido, brochas antiestáticas, alcohol isopropílico, etc.)
- Herramientas prohibidas (aspiradora doméstica, paños de algodón, etc.)
- Frecuencia recomendada (entorno de aula con polvo moderado)

### Pregunta 4.3 [3 puntos] – PRÁCTICA
El profesor te asigna un equipo con un **disco duro HDD ruidoso**. Realiza:
- Diagnóstico del estado del disco usando software (CrystalDiskInfo, HDDScan o similar).
- Extrae el informe de salud (S.M.A.R.T.): escribe al menos 3 atributos (Reallocated Sectors, Current Pending Sector, etc.).
- Indica si es necesario reemplazar y justifica tu respuesta.

---

## RA5 – Instalación de software (10%)

### Pregunta 5.1 [4 puntos]
Describe paso a paso el proceso para instalar **Windows 10/11** (o Linux Ubuntu) desde un USB booteable. Incluye:
- Herramienta para crear el USB (Rufus, Ventoy, o Media Creation Tool)
- Configuración de BIOS/UEFI (orden de arranque, deshabilitar Secure Boot si es necesario)
- Particionado (recomendación: crear partición sistema y datos)

### Pregunta 5.2 [3 puntos]
¿Qué es un **clonado de disco**? Explica la diferencia entre:
- Clonado sector a sector
- Clonado por ficheros (imagen)

¿En qué situación usarías cada uno?

### Pregunta 5.3 [3 puntos] – PRÁCTICA
Desde una imagen `.iso` proporcionada por el profesor, crea un USB booteable e inicia el asistente de instalación hasta la pantalla de particionado. **Muestra al profesor cada paso.**

---

## RA6 – Nuevas tendencias en ensamblaje (5%)

### Pregunta 6.1 [3 puntos]
Explica brevemente **tres tendencias actuales** en hardware. Para cada una, indica una ventaja y un caso de uso:

| Tendencia | Ventaja | Caso de uso |
|-----------|---------|-------------|
| 1. | | |
| 2. | | |
| 3. | | |

*Ejemplo de tendencias posibles: Almacenamiento NVMe M.2, Refrigeración líquida, DDR5, PCIe 5.0, Chipsets con WiFi integrado, Fuentes de alimentación modulares, etc.*

### Pregunta 6.2 [2 puntos]
¿Qué es la **refrigeración líquida** (AIO o custom loop)? ¿En qué tipo de equipos es recomendable frente a la refrigeración por aire?

**Dibuja un esquema básico** de un circuito de refrigeración líquida cerrado indicando: bomba, bloque CPU, radiador, ventiladores y tuberías.

---

## RA7 – Mantenimiento de periféricos (10%)

### Pregunta 7.1 [4 puntos]
Un monitor no muestra imagen pero el LED de encendido parpadea. Propón un **protocolo de diagnóstico** paso a paso (mínimo 4 pasos, desde lo más simple a lo más complejo).

### Pregunta 7.2 [3 puntos]
Explica cómo realizarías el mantenimiento de:
- **Teclado mecánico** con líquido derramado (pasos: desconexión, limpieza, secado).
- **Ratón** con doble clic involuntario (causa más probable: microinterruptor desgastado).

### Pregunta 7.3 [3 puntos] – PRÁCTICA
Se te entrega una **impresora láser** que imprime con rayas verticales negras. Realiza:
1. Identificación de la causa más probable (tambor fotoconductor, unidad de tóner, rodillo limpiador).
2. Limpieza del componente adecuado o simulación del cambio siguiendo el protocolo de seguridad.

---

## RA8 – Prevención de riesgos laborales y ambiental (10%)

### Pregunta 8.1 [3 puntos]
Identifica **cinco riesgos** en el taller de montaje y para cada uno indica:
- Medida preventiva
- Equipo de protección individual (EPI) si aplica

**Completa la tabla:**

| Riesgo | Medida preventiva | EPI necesario |
|--------|-------------------|---------------|
| 1. Contacto eléctrico | | |
| 2. Corte con disipadores | | |
| 3. Inhalación de polvo | | |
| 4. Caída de componentes | | |
| 5. Incendio | | |

### Pregunta 8.2 [3 puntos]
Explica cómo se deben gestionar estos residuos electrónicos según normativa ambiental (RAEE - Residuos de Aparatos Eléctricos y Electrónicos):
- Baterías de portátil (incluye litio)
- Placas base inservibles
- Tóner de impresora
- Pantallas LCD rotas (con mercurio en retroiluminación CCFL)

### Pregunta 8.3 [2 puntos]
¿Qué debes hacer en caso de un **pequeño incendio** en un equipo conectado a la red eléctrica? Ordena las siguientes acciones correctamente (numerar del 1 al 4):

`__` Usar extintor de CO2 (nunca agua)
`__` Desconectar el equipo de la red eléctrica
`__` Evacuar si el fuego se extiende
`__` Avisar al profesor o a emergencias

### Pregunta 8.4 [2 puntos]
Define los siguientes símbolos de seguridad que deben aparecer en el taller. **Dibuja cada símbolo** (forma simple) y explica qué indican:

1. **Peligro eléctrico** (triángulo con rayo)
2. **Peligro biológico** (símbolo ☣)
3. **Obligatorio usar guantes** (círculo azul con guantes)
4. **Residuo electrónico** (contenedor tachado: no tirar a basura general)

---

## Resumen de ponderación por RA

| RA | Descripción | Peso | Puntos examen |
|----|-------------|------|---------------|
| RA1 | Selección de componentes | 30% | 30 |
| RA2 | Ensamblaje | 15% | 15 |
| RA3 | Medición parámetros eléctricos | 10% | 10 |
| RA4 | Mantenimiento de equipos | 10% | 10 |
| RA5 | Instalación de software | 10% | 10 |
| RA6 | Nuevas tendencias | 5% | 5 |
| RA7 | Mantenimiento de periféricos | 10% | 10 |
| RA8 | Prevención de riesgos y ambiental | 10% | 10 |
| **TOTAL** | | **100%** | **100** |

---

## Hoja de respuestas (recortable para el alumno)
