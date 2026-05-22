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

## RA1 – Selección de componentes (30 puntos)

### Pregunta 1.1 (6 puntos)

Explica la función de cada uno de estos componentes y cita **dos fabricantes diferentes** para cada uno, comparando una prestación clave:

- Procesador (CPU)
- Placa base (chipset)
- Memoria RAM
- Unidad de almacenamiento (SSD vs HDD)

### Pregunta 1.2 (8 puntos)

Un cliente quiere montar un equipo para **ofimática básica** y otro para **edición de vídeo profesional**.

**Completa la siguiente tabla:**

| Componente | Equipo ofimática (gama baja) | Equipo edición vídeo (gama alta) |
|------------|-------------------------------|----------------------------------|
| CPU (modelo ejemplo) | | |
| RAM (cantidad y tipo) | | |
| Almacenamiento (tipo y capacidad) | | |
| Tarjeta gráfica | | |

Justifica cada elección.

### Pregunta 1.3 (8 puntos) – PRÁCTICA

En el taller dispones de tres placas base diferentes (marcas y modelos distintos). Identifica:

1. El socket del procesador de cada una.
2. El tipo de RAM compatible (DDR3/DDR4/DDR5).
3. El factor de forma (ATX, Micro-ATX, Mini-ITX).
4. Número de conectores SATA y su velocidad.

**Entrega una tabla con tus respuestas.**

### Pregunta 1.4 (8 puntos)

¿Qué criterios utilizarías para elegir una fuente de alimentación? Explica:
- Potencia recomendada según componentes (método de cálculo).
- Certificaciones de eficiencia (80 Plus).
- Conectores necesarios.

---

## RA2 – Ensamblaje de equipos (15 puntos)

### Pregunta 2.1 (7 puntos) – PRÁCTICA

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

### Pregunta 2.2 (4 puntos)

Se te proporciona el siguiente texto extraído de un manual real de placa base:

> **Panel frontal (F_PANEL):** Pines 1 y 3: Power LED+ y Power LED- (ánodo y cátodo). Pines 5 y 7: Power SW (sin polaridad). Pin 2 y 4: HDD LED+ y HDD LED-. Pines 6 y 8: Reset SW (sin polaridad).

**Realiza un dibujo a mano** de cómo distribuirías estos cables en un conector macho de 2 filas de 4 pines (formato 2x8 pines en total). Identifica claramente qué pin corresponde a cada cable.

### Pregunta 2.3 (4 puntos)

Enumera **cinco errores comunes** de montaje y explica cómo prevenir cada uno.

---

## RA3 – Medición de parámetros eléctricos (10 puntos)

### Pregunta 3.1 (3 puntos)

Define y escribe la unidad de medida de:

- Tensión (voltaje) → unidad: \_\_\_\_\_  
- Intensidad (corriente) → unidad: \_\_\_\_\_  
- Resistencia → unidad: \_\_\_\_\_  
- Potencia → unidad: \_\_\_\_\_

### Pregunta 3.2 (3 puntos)

Diferencia entre **señal digital** y **señal analógica**. Pon un ejemplo de cada una dentro de un PC.

**Dibuja** cómo se verían en un osciloscopio ambas señales (una señal digital cuadrada y una señal analógica sinusoidal).

### Pregunta 3.3 (4 puntos) – PRÁCTICA

Con un **multímetro digital**, realiza las siguientes mediciones en un equipo encendido (con supervisión del profesor):

1. Tensión en el conector de alimentación de 4 pines (EPS12V) – entre pin amarillo (+12V) y negro (GND).
2. Tensión en un conector SATA de alimentación (medir entre rojo y negro: +5V esperado; entre amarillo y negro: +12V esperado).
3. Continuidad en un cable de datos SATA (de extremo a extremo).

**Anota los valores obtenidos y compáralos con los valores teóricos esperados (+-5% de tolerancia).**

---

## RA4 – Mantenimiento de equipos (10 puntos)

### Pregunta 4.1 (4 puntos)

Un equipo se apaga inesperadamente después de 10-15 minutos de uso. Propón **tres posibles causas** y el procedimiento para diagnosticar cada una.

### Pregunta 4.2 (3 puntos)

Explica el procedimiento de limpieza preventiva de un equipo. Especifica:
- Herramientas permitidas.
- Herramientas prohibidas.
- Frecuencia recomendada (entorno de aula con polvo moderado).

### Pregunta 4.3 (3 puntos) – PRÁCTICA

El profesor te asigna un equipo con un **disco duro HDD ruidoso**. Realiza:
- Diagnóstico del estado del disco usando software (CrystalDiskInfo, HDDScan o similar).
- Extrae el informe de salud (S.M.A.R.T.): escribe al menos 3 atributos.
- Indica si es necesario reemplazar y justifica tu respuesta.

---

## RA5 – Instalación de software (10 puntos)

### Pregunta 5.1 (4 puntos)

Describe paso a paso el proceso para instalar **Windows 10/11** (o Linux Ubuntu) desde un USB booteable. Incluye:
- Herramienta para crear el USB.
- Configuración de BIOS/UEFI (orden de arranque).
- Particionado (recomendación básica).

### Pregunta 5.2 (3 puntos)

¿Qué es un **clonado de disco**? Explica la diferencia entre:
- Clonado sector a sector.
- Clonado por ficheros (imagen).

¿En qué situación usarías cada uno?

### Pregunta 5.3 (3 puntos) – PRÁCTICA

Desde una imagen `.iso` proporcionada por el profesor, crea un USB booteable e inicia el asistente de instalación hasta la pantalla de particionado. **Muestra al profesor cada paso.**

---

## RA6 – Nuevas tendencias en ensamblaje (5 puntos)

### Pregunta 6.1 (3 puntos)

Explica brevemente **tres tendencias actuales** en hardware. Para cada una, indica una ventaja y un caso de uso:

| Tendencia | Ventaja | Caso de uso |
|-----------|---------|-------------|
| 1. | | |
| 2. | | |
| 3. | | |

### Pregunta 6.2 (2 puntos)

¿Qué es la **refrigeración líquida** (AIO o custom loop)? ¿En qué tipo de equipos es recomendable frente a la refrigeración por aire?

**Dibuja un esquema básico** de un circuito de refrigeración líquida cerrado indicando: bomba, bloque CPU, radiador, ventiladores y tuberías.

---

## RA7 – Mantenimiento de periféricos (10 puntos)

### Pregunta 7.1 (4 puntos)

Un monitor no muestra imagen pero el LED de encendido parpadea. Propón un **protocolo de diagnóstico** paso a paso (mínimo 4 pasos, desde lo más simple a lo más complejo).

### Pregunta 7.2 (3 puntos)

Explica cómo realizarías el mantenimiento de:
- **Teclado mecánico** con líquido derramado.
- **Ratón** con doble clic involuntario.

### Pregunta 7.3 (3 puntos) – PRÁCTICA

Se te entrega una **impresora láser** que imprime con rayas verticales negras. Realiza:
1. Identificación de la causa más probable.
2. Limpieza del componente adecuado o simulación del cambio siguiendo el protocolo de seguridad.

---

## RA8 – Prevención de riesgos laborales y ambiental (10 puntos)

### Pregunta 8.1 (3 puntos)

Identifica **cinco riesgos** en el taller de montaje y para cada uno indica:
- Medida preventiva.
- Equipo de protección individual (EPI) si aplica.

**Completa la tabla:**

| Riesgo | Medida preventiva | EPI necesario |
|--------|-------------------|---------------|
| 1. | | |
| 2. | | |
| 3. | | |
| 4. | | |
| 5. | | |

### Pregunta 8.2 (3 puntos)

Explica cómo se deben gestionar estos residuos electrónicos según normativa ambiental (RAEE):
- Baterías de portátil (incluye litio).
- Placas base inservibles.
- Tóner de impresora.
- Pantallas LCD rotas (con mercurio en retroiluminación CCFL).

### Pregunta 8.3 (2 puntos)

¿Qué debes hacer en caso de un **pequeño incendio** en un equipo conectado a la red eléctrica? Ordena las siguientes acciones correctamente (numerar del 1 al 4):

`___` Usar extintor de CO2 (nunca agua)  
`___` Desconectar el equipo de la red eléctrica  
`___` Evacuar si el fuego se extiende  
`___` Avisar al profesor o a emergencias

### Pregunta 8.4 (2 puntos)

Define los siguientes símbolos de seguridad que deben aparecer en el taller. **Dibuja cada símbolo** (forma simple) y explica qué indican:

1. Peligro eléctrico (triángulo con rayo)
2. Peligro biológico (símbolo de tres lunas)
3. Obligatorio usar guantes (círculo azul con guantes)
4. Residuo electrónico (contenedor tachado)

---

# SOLUCIONARIO - MME

## RA1 – Selección de componentes (30 puntos)

### Solución Pregunta 1.1 (6 puntos)

| Componente | Función | Fabricantes (ejemplo) | Prestación comparada |
|------------|---------|----------------------|---------------------|
| Procesador (CPU) | Ejecuta instrucciones y procesa datos | Intel / AMD | Intel: mayor frecuencia por núcleo / AMD: mejor relación precio-núcleos |
| Placa base (chipset) | Comunica todos los componentes | ASUS / MSI | ASUS: BIOS más estable / MSI: mejor refrigeración en VRM |
| Memoria RAM | Almacena datos temporales de ejecución | Corsair / Kingston | Corsair: latencias más bajas (CL) / Kingston: mejor compatibilidad |
| SSD vs HDD | Almacenamiento permanente | Samsung (SSD) / Seagate (HDD) | SSD: velocidad lectura 550MB/s / HDD: velocidad 150MB/s pero más capacidad por euro |

**Criterio:** 1,5 puntos por cada componente (0,5 función + 0,5 dos fabricantes + 0,5 comparación)

---

### Solución Pregunta 1.2 (8 puntos)

| Componente | Equipo ofimática | Equipo edición vídeo |
|------------|------------------|----------------------|
| CPU | Intel Core i3 o AMD Ryzen 3 | Intel Core i7/i9 o AMD Ryzen 7/9 |
| RAM | 8GB DDR4/DDR5 | 32-64GB DDR5 |
| Almacenamiento | SSD 256GB | SSD NVMe 1TB + HDD 2TB (secundario) |
| Tarjeta gráfica | Integrada (en CPU) | NVIDIA RTX 4060+ o AMD Radeon RX 7000+ |

**Justificaciones:**
- Ofimática: no necesita gran potencia, ahorro energético y coste.
- Edición vídeo: necesita muchos núcleos, gran cantidad de RAM rápida, almacenamiento veloz para archivos grandes y GPU dedicada para aceleración por hardware.

**Criterio:** 1 punto por celda correcta (8 celdas) o 0,5 si es parcialmente correcto.

---

### Solución Pregunta 1.3 (8 puntos) – Práctica

El alumno debe entregar una tabla como esta:

| Placa | Socket | RAM compatible | Factor forma | Conectores SATA | Velocidad SATA |
|-------|--------|----------------|--------------|----------------|----------------|
| 1 | LGA1700 | DDR4 | Micro-ATX | 4 | 6 Gb/s |
| 2 | AM4 | DDR4 | ATX | 6 | 6 Gb/s |
| 3 | LGA1200 | DDR4 | Mini-ITX | 2 | 3 Gb/s |

**Criterio:** 2 puntos por placa (0,5 por cada característica correcta).

---

### Solución Pregunta 1.4 (8 puntos)

**Potencia recomendada:**
- Cálculo: sumar TDP/consumo de CPU + GPU + 50W para resto + 20-30% margen.
- Ejemplo: CPU 65W + GPU 150W + 50W = 265W → Fuente de 350-400W mínimo.

**Certificaciones 80 Plus:**

| Nivel | Eficiencia (20/50/100% carga) |
|-------|-------------------------------|
| Bronce | 82%/85%/82% |
| Plata | 85%/88%/85% |
| Oro | 87%/90%/87% |
| Platino | 90%/92%/89% |
| Titanio | 90%/94%/91% (requiere 230V) |

**Conectores necesarios:**
- 24 pines (placa base)
- EPS12V 4+4 pines (CPU)
- PCIe 6+2 pines (GPU, si aplica)
- SATA (para discos)
- Molex (opcional, para ventiladores antiguos)

**Criterio:** 2 puntos potencia (1 método + 1 ejemplo), 3 puntos certificaciones (0,5 c/u), 3 puntos conectores.

---

## RA2 – Ensamblaje de equipos (15 puntos)

### Solución Pregunta 2.1 (7 puntos) – Práctica

El profesor evaluará con esta rúbrica:

| Paso | Acción correcta | Puntos |
|------|----------------|--------|
| 1 | CPU alineada correctamente (triángulo dorado), disipador con pasta térmica | 1 |
| 2 | RAM en ranuras A2/B2 (dual channel), clips asegurados | 1 |
| 3 | Separadores en posición correcta, placa atornillada sin forzar | 1 |
| 4 | Fuente orientada correctamente (ventilador hacia fuera) | 1 |
| 5 | SSD/HDD fijado con tornillos o clip | 1 |
| 6 | Todos los conectores insertados hasta el tope y con clip | 1 |
| 7 | POST correcto (pitido o imagen) | 1 |

**Observaciones:** Si no hay POST, el alumno debe diagnosticar antes de entregar.

---

### Solución Pregunta 2.2 (4 puntos)

El alumno debe dibujar una disposición similar a:

- Fila superior (pines impares 1,3,5,7): Pin1 Power LED+ / Pin3 Power LED- / Pin5 Power SW / Pin7 Power SW
- Fila inferior (pines pares 2,4,6,8): Pin2 HDD LED+ / Pin4 HDD LED- / Pin6 Reset SW / Pin8 Reset SW

**Datos clave:**
- Power LED: polaridad (ánodo y cátodo) – invertir si no enciende.
- HDD LED: polaridad.
- Power SW: sin polaridad.
- Reset SW: sin polaridad.

**Criterio:** 2 puntos por disposición correcta, 2 puntos por identificación de polaridad.

---

### Solución Pregunta 2.3 (4 puntos)

| Error | Prevención |
|-------|------------|
| 1. Montar placa sin separadores | Colocar todos los separadores antes de atornillar |
| 2. Olvidar conectar EPS12V (CPU) | Revisar checklist antes de cerrar torre |
| 3. Pasta térmica en exceso o falta | Aplicar tamaño de un guisante o línea fina |
| 4. RAM mal insertada (clip no cierra) | Presionar ambos extremos hasta oír clic |
| 5. Cable panel frontal invertido | Leer manual y respetar polaridad (LEDs) |

**Criterio:** 0,8 puntos por cada error + prevención correcta.

---

## RA3 – Medición de parámetros eléctricos (10 puntos)

### Solución Pregunta 3.1 (3 puntos)

| Magnitud | Definición | Unidad |
|----------|-----------|--------|
| Tensión | Diferencia de potencial eléctrico | Voltio (V) |
| Intensidad | Flujo de carga eléctrica | Amperio (A) |
| Resistencia | Oposición al paso de corriente | Ohmio (Ω) |
| Potencia | Energía por unidad de tiempo | Vatio (W) |

**Criterio:** 0,75 puntos por cada fila (0,4 definición + 0,35 unidad).

---

### Solución Pregunta 3.2 (3 puntos)

**Diferencias:**
- **Señal digital:** Valores discretos (0 y 1, niveles de tensión fijos). Ejemplo: señal de reloj del procesador, bus SATA.
- **Señal analógica:** Valores continuos en un rango. Ejemplo: salida de sensor de temperatura, señal de audio.

**Dibujo esperado:**
- Digital: onda cuadrada (sube/baja bruscamente)
- Analógica: onda sinusoidal o variable continua

**Criterio:** 1 punto definiciones, 2 puntos dibujo (1 cada señal).

---

### Solución Pregunta 3.3 (4 puntos) – Práctica

| Medición | Valor teórico | Tolerancia ±5% | Valor medido alumno |
|----------|---------------|----------------|---------------------|
| EPS12V (amarillo-negro) | +12V | 11,4V – 12,6V | _____ |
| SATA rojo-negro | +5V | 4,75V – 5,25V | _____ |
| SATA amarillo-negro | +12V | 11,4V – 12,6V | _____ |
| Continuidad cable SATA | 0Ω (o pitido) | < 1Ω | _____ |

**Criterio:** 1 punto por medición correcta + comparación con valor teórico.

---

## RA4 – Mantenimiento de equipos (10 puntos)

### Solución Pregunta 4.1 (4 puntos)

| Causa posible | Diagnóstico |
|---------------|-------------|
| 1. Sobrecalentamiento (CPU/GPU) | Monitorizar temperaturas (HWMonitor), comprobar ventiladores y pasta térmica |
| 2. Fuente de alimentación defectuosa | Probar con fuente alternativa o medir voltajes con multímetro |
| 3. Condensadores hinchados en placa base | Inspección visual, buscar fugas o abombamientos |

**Criterio:** 1,33 puntos por cada causa (0,66 identificación + 0,67 diagnóstico).

---

### Solución Pregunta 4.2 (3 puntos)

**Herramientas permitidas:**
- Aire comprimido (en lata o compresor con baja presión)
- Brochas antiestáticas (cerdas suaves)
- Alcohol isopropílico (99%) + bastoncillos
- Pulsera antiestática

**Herramientas prohibidas:**
- Aspiradora doméstica (genera ESD y puede dañar componentes)
- Paños de algodón o microfibra seca (electricidad estática)
- Líquidos no específicos (agua, limpiadores multiuso)

**Frecuencia:** Cada 6-12 meses en entorno de aula. En entorno doméstico con mascotas o fumadores, cada 3-6 meses.

**Criterio:** 1 punto herramientas permitidas, 1 punto prohibidas, 1 punto frecuencia.

---

### Solución Pregunta 4.3 (3 puntos) – Práctica

**Atributos S.M.A.R.T. clave:**

| Atributo ID | Nombre | Valor crítico |
|-------------|--------|---------------|
| 05 | Reallocated Sectors Count | > 0 (sectores reasignados) |
| 197 | Current Pending Sector Count | > 0 |
| 198 | Uncorrectable Sector Count | > 0 |

**Conclusión:** Si algún valor crítico > 0 o el estado es "Cuidado" o "Failing", se recomienda reemplazo inmediato y copia de seguridad.

**Criterio:** 1 punto diagnóstico software, 1 punto tres atributos correctos, 1 punto justificación.

---

## RA5 – Instalación de software (10 puntos)

### Solución Pregunta 5.1 (4 puntos)

**Paso 1 – Crear USB booteable:**
- Descargar ISO de Windows/Linux.
- Abrir Rufus: seleccionar USB, partición GPT (UEFI) o MBR (BIOS legacy).
- Seleccionar ISO, iniciar grabación.

**Paso 2 – Configurar BIOS/UEFI:**
- Acceder (F2/DEL/Supr al encender).
- Deshabilitar Secure Boot (si da problemas).
- Establecer USB como primer dispositivo de arranque.

**Paso 3 – Instalación:**
- Iniciar desde USB.
- Seleccionar idioma, aceptar licencia.
- Particionado recomendado: eliminar particiones existentes, crear nueva (NTFS para Windows, ext4 para Linux).
- Continuar instalación.

**Criterio:** 1,33 puntos por cada paso bien explicado.

---

### Solución Pregunta 5.2 (3 puntos)

**Clonado sector a sector:**
- Copia bit a bit incluyendo sectores vacíos y borrados.
- Útil para discos de arranque con particiones ocultas.
- Desventaja: requiere disco destino igual o mayor tamaño.

**Clonado por ficheros (imagen):**
- Copia solo archivos del sistema de archivos.
- Útil para backups selectivos o restauración en discos de distinto tamaño.
- Desventaja: no preserva todas las particiones.

**Criterio:** 1,5 puntos por cada tipo (0,5 definición, 0,5 ventaja/desventaja, 0,5 caso uso).

---

### Solución Pregunta 5.3 (3 puntos) – Práctica

El alumno debe demostrar al profesor:
1. USB booteable detectado en BIOS.
2. Arranque exitoso desde USB.
3. Llegada a pantalla de particionado.

**Criterio:** 1 punto por cada hito alcanzado.

---

## RA6 – Nuevas tendencias en ensamblaje (5 puntos)

### Solución Pregunta 6.1 (3 puntos)

| Tendencia | Ventaja | Caso de uso |
|-----------|---------|-------------|
| 1. NVMe M.2 PCIe 5.0 | Velocidad lectura 10.000 MB/s | Edición 8K, IA local |
| 2. DDR5 | Mayor ancho de banda (hasta 4x DDR4) | Workstations, servidores |
| 3. Refrigeración líquida AIO | Mejor disipación en espacio reducido | SFF (Small Form Factor) |

**Otras tendencias válidas:** Fuentes ATX 3.0 (conector 12VHPWR para GPUs), Placas base con WiFi 7, Chips ARM en PC, etc.

**Criterio:** 1 punto por tendencia (0,4 nombre, 0,3 ventaja, 0,3 caso uso).

---

### Solución Pregunta 6.2 (2 puntos)

**Refrigeración líquida:** Sistema que disipa calor mediante un líquido refrigerante que circula entre bloque (CPU/GPU) y radiador.

**Tipos:**
- AIO (All-In-One): cerrado, fácil instalación, bajo mantenimiento.
- Custom loop: personalizable, mayor rendimiento, más caro y complejo.

**Cuándo usar vs aire:**
- Recomendable: CPUs de gama alta (i9/Ryzen 9), overclocking, equipos compactos.
- Aire suficiente: CPUs de gama media/baja, equipos con buen flujo de aire.

**Dibujo esperado del alumno:** Bomba → CPU bloque → Tubería → Radiador → Tubería retorno → Bomba (ciclo cerrado).

**Criterio:** 1 punto definición y tipos, 1 punto comparación y dibujo correcto.

---

## RA7 – Mantenimiento de periféricos (10 puntos)

### Solución Pregunta 7.1 (4 puntos)

**Pasos ordenados (de simple a complejo):**

1. **Verificar conexiones:** ¿El cable de alimentación está enchufado? ¿El cable de vídeo está bien conectado tanto al monitor como al PC? Probar otro cable.
2. **Probar el monitor con otra fuente:** Conectar a otro PC o portátil. ¿Funciona?
3. **Probar el PC con otro monitor** (o pantalla/TV). ¿Funciona?
4. **Revisar tarjeta gráfica:** Reseat (volver a insertar) la GPU. Probar con gráfica integrada si existe.
5. **Comprobar retroiluminación:** Linterna cerca de la pantalla; si se ve imagen muy tenue, problema de retroiluminación/backlight.

**Criterio:** 1 punto por paso válido y orden lógico (máximo 4 pasos).

---

### Solución Pregunta 7.2 (3 puntos)

**Teclado mecánico con líquido derramado:**
1. Desconectar inmediatamente (USB).
2. Voltear y dejar escurrir.
3. Retirar teclas (keycaps) afectadas.
4. Limpiar con alcohol isopropílico y bastoncillo.
5. Dejar secar mínimo 24h antes de reconectar.

**Ratón con doble clic involuntario:**
- Causa: microinterruptor desgastado (oxidación o fatiga mecánica).
- Solución: reemplazar el interruptor (soldadura), o comprar ratón nuevo si el coste no merece la pena.
- Solución temporal (no recomendada): soplar aire comprimido o abrir y limpiar contactos.

**Criterio:** 1,5 puntos teclado, 1,5 puntos ratón (0,5 causa + 1 solución).

---

### Solución Pregunta 7.3 (3 puntos) – Práctica

**Diagnóstico rayas verticales negras en láser:**
- Causa más probable: **tambor fotoconductor rayado o sucio**.
- Causa secundaria: unidad de tóner defectuosa (si las rayas son repetitivas con patrón).

**Procedimiento:**
1. Apagar impresora y desconectar.
2. Extraer unidad de tóner y tambor (según modelo).
3. Inspeccionar visualmente el tambor (brillante, cilindro verde/azul).
4. Limpiar suavemente con paño suave y seco (nunca alcohol ni objetos duros).
5. Si el rayón persiste, reemplazar tambor.

**Seguridad:** Evitar luz solar directa sobre tambor (fotosensibilidad), no tocar superficie.

**Criterio:** 1 punto diagnóstico correcto, 1 punto limpieza, 1 punto seguridad.

---

## RA8 – Prevención de riesgos laborales y ambiental (10 puntos)

### Solución Pregunta 8.1 (3 puntos)

| Riesgo | Medida preventiva | EPI necesario |
|--------|-------------------|---------------|
| 1. Contacto eléctrico | Desconectar equipo antes de manipular internamente | Guantes dieléctricos |
| 2. Corte con disipadores | Manipular con cuidado, usar guantes de protección | Guantes anticorte |
| 3. Inhalación de polvo | Limpiar con aire comprimido en zona ventilada | Mascarilla FFP2 |
| 4. Caída de componentes | Mesa ordenada, usar bandejas magnéticas | Calzado de seguridad |
| 5. Incendio (fuente/batería) | No sobrecargar regletas, usar extintor CO2 | No aplica |

**Criterio:** 0,6 puntos por fila (0,2 cada columna).

---

### Solución Pregunta 8.2 (3 puntos)

| Residuo | Gestión correcta |
|---------|------------------|
| Baterías de portátil (litio) | Entregar en punto limpio o contenedor específico de baterías (nunca basura general o fuego) |
| Placas base inservibles | Reciclaje en planta RAEE (contienen metales como oro, cobre, plomo) |
| Tóner de impresora | Contenedor de tóner en tiendas o punto limpio (peligro de inhalación si se rompe) |
| Pantallas LCD rotas (CCFL) | RAEE peligroso por mercurio de retroiluminación, punto limpio especial |

**Criterio:** 0,75 puntos por cada residuo.

---

### Solución Pregunta 8.3 (2 puntos)

**Secuencia correcta (numerar del 1 al 4):**

| Orden | Acción |
|-------|--------|
| 1 | Desconectar el equipo de la red eléctrica |
| 2 | Usar extintor de CO2 (nunca agua) |
| 3 | Avisar al profesor o a emergencias |
| 4 | Evacuar si el fuego se extiende |

**Criterio:** 0,5 puntos por cada posición correcta.

---

### Solución Pregunta 8.4 (2 puntos)

| Símbolo | Nombre | Significado |
|---------|--------|-------------|
| Triángulo con rayo | Peligro eléctrico | Riesgo de descarga o componentes bajo tensión |
| Trébol de 3 lunas | Peligro biológico | Residuos biopeligrosos |
| Círculo azul con guantes | Obligatorio usar guantes | Protección obligatoria para manipular ciertos componentes |
| Contenedor tachado | No tirar a basura general | Residuo electrónico (RAEE) – llevar a punto limpio |

**Criterio:** 0,5 puntos por símbolo (0,25 identificación + 0,25 significado).

---

## Resumen de puntuación por RA

| RA | Descripción | Puntos |
|----|-------------|--------|
| RA1 | Selección de componentes | 30 |
| RA2 | Ensamblaje | 15 |
| RA3 | Medición parámetros eléctricos | 10 |
| RA4 | Mantenimiento de equipos | 10 |
| RA5 | Instalación de software | 10 |
| RA6 | Nuevas tendencias | 5 |
| RA7 | Mantenimiento de periféricos | 10 |
| RA8 | Prevención de riesgos y ambiental | 10 |
| **TOTAL** | | **100** |

---

**FIN DEL EXAMEN Y SOLUCIONARIO DE MME**