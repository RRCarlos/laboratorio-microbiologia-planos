# Especificación Arquitectónica - Laboratorio BSL-2

## VeriTest.LAB

**Memoria Descriptiva del Proyecto de Laboratorio de Microbiología BSL-2**

---

## 1. DATOS GENERALES DEL PROYECTO

| Campo | Valor |
|-------|-------|
| **Proyecto** | Laboratorio de Microbiología BSL-2 |
| **Propietario** | VeriTest.LAB |
| **Nivel de Bioseguridad** | BSL-2 |
| **Superficie útil estimada** | 120-150 m² |
| **Altura libre** | Mínimo 2,7 m (recomendado 3,0 m) |
| **Ubicación** | Por definir |

---

## 2. PROGRAMA DE NECESIDADES

### 2.1 Áreas Funcionales

| Área | Descripción | Superficie (m²) | Observaciones |
|------|-------------|-----------------|----------------|
| **Recepción de muestras** | Recepción, registro, clasificación | 15 | Zona limpio/sucio separada |
| **Preparación de medios** | Preparación de medios de cultivo, esterilización | 20 | BSC dedicada, autoclave |
| **Cultivo e incubación** | Incubadoras, cultivos, cámaras | 25 | Control temperatura/humedad |
| **Área de análisis** | Microscopia, PCR, electroforesis | 20 | Mesas antivibratorias |
| **Cabinas BSC** | Cabinas de seguridad biológica (x2) | 15 | Clase II Tipo A2 |
| **Almacenamiento** | Refrigeración, criogenia, reactivos | 15 | Zona segregada |
| **Vestuarios** | Cambio EPIs, aseos | 10 | Filtrado entrada/salida |
| **Pasillos y distribuciones** | Circulaciones | 20 | - |
| **TOTAL** | | **~140 m²** | |

### 2.2 Diagrama de Flujo

```
┌──────────────────────────────────────────────────────────────────────────┐
│                         ENTRADA                                   │
│                    (Zona limpia)                                │
└────────────────────────────┬───────────────────────────────────┘
                             ▼
┌──────────────────────────────────────────────────────────────────┐
│                   RECEPCIÓN DE MUESTRAS                        │
│              (15 m²) - Registro, código barras                │
└────────────────────────────┬───────────────────────────────────┘
                             ▼
┌──────────────┐    ┌──────────────┐    ┌──────────────────────────┐
│ PREPARACIÓN  │    │   CULTIVO E   │    │   ÁREA DE ANÁLISIS      │
│   DE MEDIOS  │───▶│ INCUBACIÓN   │───▶│   (Microscopia, PCR)    │
│   (20 m²)    │    │   (25 m²)    │    │      (20 m²)           │
└──────────────┘    └──────────────┘    └──────────────────────────┘
       │                                           │
       ▼                                           ▼
┌──────────────────────────────────────────────────────────────────┐
│              CABINAS DE SEGURIDAD BIOLÓGICA (x2)                  │
│                       (15 m²)                                    │
└──────────────────────────────────────────────────────────────────┘
                             │
                             ▼
┌──────────────────────────────────────────────────────────────────┐
│                   ALMACENAMIENTO                                │
│     (4°C, -20°C, -80°C, N₂ líquido) - (15 m²)                  │
└──────────────────────────────────────────────────────────────────┘
                             │
                             ▼
┌──────────────────────────────────────────────────────────────────┐
│                         SALIDA                                   │
│               (Zona de residuos biocontaminados)                 │
└──────────────────────────────────────────────────────────────────┘
```

---

## 3. REQUISITOS ARQUITECTÓNICOS BSL-2

### 3.1 Barrera Secundaria (Instalación)

| Requisito | Especificación |
|-----------|---------------|
| **Wallas selladas** | Sin grietas, penetraciones selladas |
| **Puertas** | Con cierre automático, sellado perimetral |
| **Ventanas** | Fijas o de emergencia sellada |
| **Suelos** | Continuos, sin juntas, resistencia química |
| **Paredes** | Pintura epoxi, resistencia a desinfectantes |
| **Techos** | Falsos techo sellados, registro limitado |

### 3.2 Sistema de Presión

| Parámetro | Especificación |
|----------|---------------|
| **Presión** | Negativa respecto a pasillo (-15 a -25 Pa) |
| **Flujo de aire** | Desde áreas limpias hacia áreas sucias |
| **Cambios de aire** | 6-12 ACH (air changes per hour) |
| **Extracción** | 100% salida,sin recirculacion |

### 3.3 Ventilación

| Zona | Temperatura | Humedad | Renovaciones |
|------|-------------|--------|---------------|
| General | 20-24°C | 30-70% | 6 ACH |
| Cabinas BSC | Local | - | Extacción dedicada |
| Esterilización | Local | - | Extracción 100% |

---

## 4. ACABADOS Y MATERIALES

### 4.1 Suelos

| Área | Material | Requísit |
|------|----------|---------|
| **Laboratorio** | Resina epoxi autoniivellante | Antideslizante, continuo |
| **Vestuarios** | Vinilo homologado | Antiestático |
| **Pasillos** | Resina epoxi | Alto tráfico |
| **Almacén** | Hormigon pulido | Resistente |

### 4.2 Paredes

| Área | Material | Observaciones |
|------|----------|--------------|
| **Laboratorio** | Pintura epoxi antimicrobial | Lavable, resistente |
| **Paredes húmedas** | Azulejo 20 cm | Zonas de lavabo |
| **Vestuarios** | Pintura plástica | Transpirable |

### 4.3 Puertas

| Tipo | Especificación |
|------|-------------|
| **Entrada principal** | Puerta automática, 1,20 m, cierre automático |
| **Interior laboratorio** | Puerta con respiradero inferior, cierre hermético |
| **Salida de emergencia** | Apertura interior, sin cerradura |

### 4.4 Señalización

| Señal | Ubicación |
|-------|-----------|
| **Biohazard** | Entrada principal |
| **BSL-2** | Entrada laboratorio |
| **EPP obligatorio** | Entrada zona dirty |
| **Peligro biológico** | Puertas de áreas biocontaminadas |
| **Plano de evacuación** | Entrada y pasillo |

---

## 5. DISTRIBUCIÓN DE EQUIPOS (Referencia)

### 5.1 Área de Recepción

- Mesa reception: 1,8 m x 0,8 m (acero inoxidable)
- Lector código barras: 1 unidad
- Refrigerador 4°C: 1 unidad (muestras temporales)
- Terminal LIMS: 1 unidad

### 5.2 Área de Preparación

- Cabina BSC Clase II Tipo A2: 1 unidad (1,2 m)
- Autoclave de doble puerta: 1 unidad (100-150 L)
- Baño termostático: 1 unidad
- Balanza analítica: 1 unidad
- Agitador magnético: 2 unidades
- Sistema purificación agua: 1 unidad

### 5.3 Área de Cultivo

- Incubadora CO₂: 3 unidades (150-200 L)
- Incubadora estándar: 2 unidades
- Incubador orbital: 1 unidad
- Microscopio invertido: 1 unidad

### 5.4 Área de Análisis

- Microscopio campo claro: 1 unidad
- Microscopio fluorescencia: 1 unidad
- Termociclador PCR: 1 unidad
- Sistema electroforesis: 1 unidad
- Lector microplacas: 1 unidad
- Centrífuga mesa: 1 unidad
- Centrífuga refrigerada: 1 unidad

### 5.5 Cabinas BSC

- BSC Clase II Tipo A2: 2 unidades (1,2 m cada una)
- Ubicación:远离 de puertas y corrientes de aire

### 5.6 Almacenamiento

- Refrigerador 4°C: 2 unidades
- Congelador -20°C: 1 unidad
- Ultracongelador -80°C: 2 unidades
- Tanque nitrógeno: 1 unidad (30-50 L)

---

## 6. EQUIPO DE PROTECCIÓN PERSONAL (EPP)

### 6.1 Zona de Vestuario

| Elemento | Cantidad |
|---------|---------|
| Batas descartables | 20 unidades |
| Guantes latex/nitrilo | 10 cajas |
| Protección ocular | 10 unidades |
| Mascarillas FFP2 | 10 cajas |
| Calzas descartables | 10 cajas |
| Casquetete | 10 unidades |

### 6.2 Ducha de Emergencia

| Equipo | Especificación |
|--------|---------------|
| Ducha lavaojos | Combinada, activación pedal/codo |
| Ubicación | Cerca de salida |
| Señalización | Visible, reflectante |

---

## 7. CUMPLIMIENTO NORMATIVO

### 7.1 Normativas Aplicables

| Norma | Descripción |
|-------|-------------|
| ISO 15189:2022 | Requisitos de calidad |
| ISO 15190:2020 | Requisitos de seguridad |
| ISO 35001:2019 | Gestión riesgo biológico |
| CDC/NIH BMBL 6th | Guía de bioseguridad |
| WHO LBM 4th | Manual bioseguridad |

### 7.2 Certificaciones Requeridas

| Certificación | Descripción |
|--------------|-------------|
| **BSC** | NSF/ANSI 49 (anual) |
| **Autoclave** | Validación IQ/OQ/PQ |
| **Ventilación** | Certificación de flujo |
| **Laboratorio** | Autorización sanitaria |

---

## 8. PRESUPUESTO ESTIMADO (Arquitectura)

| Capítulo | Importe (€) | Observaciones |
|----------|-------------|-------------|
| **Obra civil** | 80.000 | Albañilería, estructuras |
| **Acabados** | 35.000 | Suelos, paredes, techos |
| **Carpintería** | 15.000 | Puertas, ventanas |
| ** señalización** | 5.000 | Normativa |
| **TOTAL ARQUITECTURA** | **135.000** | |

---

## 9. NOTAS IMPORTANTES

1. **Este documento es conceptual** - Requiere desarrollo por arquitecto colegiado
2. **Antes de construcción** - Verificar legislación local autonómica
3. **Licencia de apertura** - Consultar con autoridad sanitaria
4. **Proyecto técnico** - Debe ser firmado por arquitecto
5. **Ejecución** - Debe ser dirigida por Apareador

---

*Documento conceptual para desarrollo por profesional*
*VeriTest.LAB - Laboratorio Microbiología BSL-2*
*Versión 1.0 — Abril 2026*