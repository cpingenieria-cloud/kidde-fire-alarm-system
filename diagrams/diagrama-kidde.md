# Diagrama de sistema Kidde

```mermaid
flowchart LR
    subgraph Area[Área protegida]
        D1[Detector humo]
        D2[Detector calor]
        D3[Estación manual]
    end

    subgraph Panel[Panel de control]
        P1[Controlador principal]
        P2[Fuente de alimentación]
        P3[Batería respaldo]
    end

    subgraph Alarma[Señalización]
        A1[Sirena]
        A2[Luz de evacuación]
        A3[Notificación remota]
    end

    D1 --> P1
    D2 --> P1
    D3 --> P1
    P2 --> P1
    P3 --> P1
    P1 --> A1
    P1 --> A2
    P1 --> A3
