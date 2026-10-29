# Sistema de incendios Kidde

Proyecto de documentación técnica, configuración e implementación de un sistema de alarma contra incendios tipo Kidde.

## Objetivo
Documentar la arquitectura, configuración, instalación, pruebas y mantenimiento de un sistema de detección y alarma contra incendios orientado a entornos empresariales e institucionales.

## Alcance
- Detección de humo y calor
- Panel de control y monitoreo
- Dispositivos de alarma visual y sonora
- Señalización de evacuación
- Integración con supervisión y respuesta
- Procedimientos de instalación, pruebas y mantenimiento

## Componentes principales
- Panel de control
- Detectores de humo
- Detectores de calor
- Sirenas y alarmas
- Estaciones manuales
- Indicadores visuales
- Cableado y accesorios
- Fuente de alimentación
- Baterías de respaldo

## Arquitectura del sistema
El sistema se compone de:
1. Sensores distribuidos en áreas críticas
2. Panel central de control
3. Circuitos de detección y alarma
4. Módulos de supervisión
5. Sistema de notificación y evacuación
6. Procedimientos de respuesta y mantenimiento

## Diagrama general

```mermaid
flowchart TD
    A[Panel de Control Kidde] --> B[Detectores de humo]
    A --> C[Detectores de calor]
    A --> D[Estaciones manuales]
    A --> E[Sirenas y alarmas]
    A --> F[Indicadores visuales]
    A --> G[Fuente de alimentación]
    A --> H[Sistema de monitoreo / central]
