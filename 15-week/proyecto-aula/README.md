## Hotel Brisas de la Tatacoa S.A.S.


**Fase:** 0 – Definición

---

## Ficha del proyecto

| Campo | Respuesta |
|---|---|
| **Integrantes** | María Fernanda Arzayus Diaz |
| **Empresa y tipo** | Hotel Brisas de la Tatacoa S.A.S. – Empresa ficticia |
| **¿A qué se dedica?** | Empresa dedicada a ofrecer servicios de alojamiento turístico en Villavieja, Huila. Cuenta con diferentes tipos de habitaciones y recibe reservas a través de distintos canales. |
| **Problema** | El hotel cuenta con información sobre sus reservas, pero no dispone de una herramienta que permita analizarla de manera rápida e integrada. Esto dificulta identificar los periodos de mayor y menor demanda, los tipos de habitación con mejor comportamiento y los canales de reserva que generan mejores resultados. |
**Pregunta de negocio** | ¿En qué temporadas y por qué canales debe el Hotel Brisas de la Tatacoa lanzar promociones para aumentar la ocupación y los ingresos durante el segundo semestre de 2025?
| **KPI principal y fórmula** | **Tasa de ocupación (%)** = (Noches ocupadas / Noches disponibles) × 100 |
| **KPI de apoyo 1** | **Ingreso promedio por reserva** = Ingresos totales / Número de reservas |
| **KPI de apoyo 2** | **Tasa de cancelación (%)** = (Reservas canceladas / Total de reservas) × 100 |
| **Fuentes de datos y formato** | Dataset sintético de reservas hoteleras – formato CSV |
| **Autorización** | No aplica, debido a que la empresa es ficticia. |

---

## Fase 0 – Definición

### Empresa

Hotel Brisas de la Tatacoa S.A.S. es una empresa ficticia ubicada en Villavieja, Huila, dedicada a ofrecer servicios de alojamiento turístico a visitantes de la región. El hotel cuenta con diferentes tipos de habitaciones y recibe reservas mediante distintos canales.

### Problema

El hotel cuenta con información sobre sus reservas, pero no dispone de una herramienta que permita analizarla de manera rápida e integrada. Esta situación dificulta identificar los periodos de mayor y menor demanda, los tipos de habitación con mejor comportamiento y los canales de reserva que generan mejores resultados. Como consecuencia, la empresa puede tomar decisiones poco oportunas sobre disponibilidad, promociones y estrategias comerciales.

### Pregunta de negocio

> ¿Cómo varían la ocupación y los ingresos del hotel según el periodo, el tipo de habitación y el canal de reserva?

| **KPI principal: Tasa de ocupación real (%)** | (Noches ocupadas / Noches disponibles) × 100 |
| **KPI de apoyo 1: Ingreso promedio por reserva** | Ingresos totales / Número de reservas |
| **KPI de apoyo 2: Tasa de cancelación (%)** | (Reservas canceladas / Total de reservas) × 100 |
| **KPI de apoyo 3: Noches perdidas por novedad** | Noches instaladas − Noches disponibles |
| **KPI de apoyo 4: Clientes recurrentes (%)** | (Clientes que regresan / Clientes totales) × 100 |
| **KPI de apoyo 5: Reprocesos por cada 100 reservas** | (Número de reprocesos / Número de reservas) × 100 |

### Fuente de datos

-## Alcance y características del dataset

- **Volumen:** 1.200 registros de reservas sintéticas, correspondientes al periodo enero-diciembre de 2025.
- **Periodo:** enero a diciembre de 2025.
- **Temporadas:** baja, media y alta.
- **Dimensiones de análisis:** calendario, clientes, habitaciones y canales de reserva.
- **Fuente:** datos sintéticos de reservas hoteleras.
- **Herramienta de preparación:** Excel y Power Query.

## Capacidad hotelera

Se tendrá en cuenta la capacidad instalada y la capacidad disponible del hotel. La capacidad disponible será la capacidad instalada menos las habitaciones bloqueadas por mantenimiento, eventos o uso interno.

## Información complementaria

El dataset incluirá:
- Clientes frecuentes identificados mediante códigos.
- Cancelaciones con sus motivos, anticipación y canal.
- Disponibilidad diaria de las habitaciones.
- Reprocesos administrativos con tiempo y costo.
- Calendario con días festivos y temporadas de Colombia.

## Modelo de datos

Se trabajará con las siguientes tablas:
- Fact_Reserva.
- Fact_Disponibilidad_Diaria.
- Fact_Reproceso.
- Dim_Calendario.
- Dim_Habitacion.
- Dim_Cliente.
- Dim_Canal.
- Dim_Tipo_Reproceso.
---
