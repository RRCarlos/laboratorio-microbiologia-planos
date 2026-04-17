# Especificación de Instalaciones - Laboratorio BSL-2

## VeriTest.LAB

**Memoria de Instalaciones del Proyecto de Laboratorio de Microbiología BSL-2**

---

## 1. INSTALACIÓN ELÉCTRICA

### 1.1 Cuadro Eléctrico

| Componente | Especificación |
|-----------|---------------|
| **Cuadro general** | En zona común, acceso fácil |
| **Protección general** | Diferencial 40A 30mA |
| **Protección líneas** | Magnetotérmicos 16A, 20A, 25A |
| **SAI/UPS** | Para equipos críticos (BSC, congeladores) |

### 1.2 Tomas de Corriente

| Zona | Tomas 16A | Tomas especiales |
|------|------------|---------------|
| **Recepción** | 4 | - |
| **Preparación** | 6 | 2x32A (autoclave) |
| **Cultivo** | 6 | - |
| **Análisis** | 8 | 2x32A (centrífuga) |
| **BSC** | 4 por cabin |专用 |
| **Almacenamiento** | 4 | 1x32A (ultracongelador) |

### 1.3 Alumbrado

| Zona | Tipo | Luxes (mínimo) |
|------|------|--------------|
| **General** | LED 4000K | 500 lux |
| **Mesas trabajo** | LED empotrado | 750 lux |
| **Cabinas BSC** | LED integrados | 500 lux |
| **Emergencia** | LED autónomo | 1 lux |

### 1.4 Presupuesto Estimado

| Concepto | Importe (€) |
|---------|------------|
| **Cuadro y protecciones** | 8.000 |
| **Tomas y cableado** | 12.000 |
| **Alumbrado** | 6.000 |
| **SAI 3000VA** | 4.000 |
| **TOTAL ELÉCTRICA** | **30.000** |

---

## 2. INSTALACIÓN DE FONTANERÍA

### 2.1 Red de Agua

| Punto | Tipo | Observaciones |
|-------|------|-------------|
| **Lavabos laboratorios (x4)** | Agua fría/caliente | Accionamientocodopierna |
| **Lavabo preparación** | Agua purificada Tipo I | Para preparación medios |
| **Ducha emergencia** | Agua tibia | Temperatura 37°C |
| **Lavaojos** | Agua potable | Flujo continuo |

### 2.2 Red de Desagüe

| Zona | Tipo de desagüe |
|------|----------------|
| **Lavabos** | HC (homologado) |
| **Duchas** | HC con arqueta |
| **Autoclave** | Desagüe festone |

**IMPORTANTE**: Los líquidos biocontaminados deben tratarse antes de vertido:
-Autoclave in situ para descontaminación
-OColección de residuos terceros

### 2.3 Presupuesto Estimado

| Concepto | Importe (€) |
|---------|------------|
| **Red agua fría/caliente** | 7.000 |
| **Red desagües** | 5.000 |
| **Equipo ducha/lavaojos** | 3.000 |
| **Tratamiento aguas** | 5.000 |
| **TOTAL FONTANERÍA** | **20.000** |

---

## 3. INSTALACIÓN DE CLIMATIZACIÓN (HVAC)

### 3.1 Sistema de Ventilación

| Parámetro | Especificación |
|-----------|---------------|
| **Tipo** | Extracción controlada |
| **Renovaciones** | 6-12 ACH |
| **Filtración** | Filtros HEPA H14 salida |
| **Presión** | Negativa (-15 a -25 Pa) |
| **Control** | Sistema BMS |

### 3.2 Aire Acondicionado

| Zona | Temperatura | Humedad | Capacidad |
|------|-------------|--------|----------|
| **Laboratorio** | 20-24°C | 30-70% | 8.000 W |
| **Cultivo** | 37°C ±1°C | 50-70% | 3.000 W |
| **Almacenamiento** | Variable | - | Frío directo |

### 3.3 Extracción Dedicada

| Equipo | Extracción requerida |
|--------|----------------|
| **BSC (x2)** | 600 m³/h cada una |
| **Autoclave** | 400 m³/h |
| **Sala sucia** | 300 m³/h |

### 3.4 Presupuesto Estimado

| Concepto | Importe (€) |
|---------|------------|
| **UTA (Unidad tratamiento)** | 18.000 |
| **Red de conductos** | 12.000 |
| **Extractores** | 6.000 |
| **Filtros HEPA** | 4.000 |
| **Control BMS** | 5.000 |
| **TOTAL CLIMATIZACIÓN** | **45.000** |

---

## 4. INSTALACIÓN DE DATOS Y TELECOMUNICACIONES

### 4.1 Red de Datos

| Punto | Especificación |
|-------|-------------|
| **Switches** | 1 principal + 2 secundarios |
| **Cableado** | Cat6a (mínimo) |
| **Puntos de red** | 20-30 puntos |
| **WiFi** | Ubiquiti (2 puntos) |

### 4.2 Integración LIMS

| Sistema | Conexión |
|---------|---------|
| **Balanza analítica** | RS232/USB |
| **Autoclave** | Ethernet |
| **Incubadoras** | Ethernet |
| **Centrífugas** | USB |
| **PCR** | USB/Ethernet |
| **Lector código barras** | USB |

### 4.3 Presupuesto Estimado

| Concepto | Importe (€) |
|---------|------------|
| **Cableado y rosetas** | 4.000 |
| **Switches y equipos** | 3.000 |
| **Integración equipos** | 2.000 |
| **TOTAL DATOS** | **9.000** |

---

## 5. INSTALACIÓN DE GAS (si aplica)

### 5.1 Gases Comprimidos

| Gas | Uso | Suministro |
|-----|-----|----------|
| **N₂** | Criopreservación | Tanque Dewar |
| **CO₂** | Incubadoras | Botellascilindro |
| **N₂ líquido** | Criogenia | Tanque principal |

### 5.2 Presupuesto Estimado

| Concepto | Importe (€) |
|---------|------------|
| **Tanque N₂ (alquiler)** | 2.000/año |
| **Suministro CO₂** | 500/año |
| **Instalación** | 2.000 |
| **TOTAL GASES** | **4.500** |

---

## 6. RESUMEN PRESUPUESTO INSTALACIONES

| Instalación | Importe (€) |
|------------|-------------|
| **Eléctrica** | 30.000 |
| **Fontanería** | 20.000 |
| **Climatización (HVAC)** | 45.000 |
| **Datos** | 9.000 |
| **Gases** | 4.500 |
| **TOTAL INSTALACIONES** | **108.500** |

---

## 7. CUMPLIMIENTO BSL-2

### Requisitos de Ventilación (BMBL)

| Requisito | Cumplimiento |
|----------|-------------|
| **Flujo direccional** | ✅ Desde entrada hacia salida |
| **Presión negativa** | ✅ Monitorizada |
| **6-12 ACH** | ✅ Sistema calculado |
| **Filtros HEPA** | ✅ En todas las extracciones |
| **Sin recirculación** | ✅ 100% extracción |

### Requisitos Eléctricos (ISO 15190)

| Requisito | Cumplimiento |
|----------|-------------|
| **SAI equipos críticos** | ✅ UPS dedicado |
| **Iluminación emergencia** | ✅ LED autónomos |
| **Tomas con tierra** | ✅ Todas protegidas |

---

## 8. NOTAS

1. **Proyecto técnico** debe ser firmado por ingenieroo instalador
2. **Certificaciones** requiered annually para BSC, HVAC
3. **Mantenimiento** preventivo obligatorio
4. **Registro** de mantenimiento obligatorio

---

*Documento conceptual para desarrollo por profesional*
*VeriTest.LAB - Laboratorio Microbiología BSL-2*
*Versión 1.0 — Abril 2026*