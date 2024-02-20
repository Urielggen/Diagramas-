graph TD
    A[Inicio] --> B{¿Destino decidido?}
    B -->|Sí| C[Elegir fechas de viaje]
    B -->|No| D[Decidir destino]
    C --> E{¿Fechas confirmadas?}
    D --> E
    E -->|Sí| F[Elegir alojamiento]
    E -->|No| G[Revisar calendario]
    F --> H{¿Alojamiento reservado?}
    G -->|Sí| F
    G -->|No| I[Buscar alojamiento]
    H -->|Sí| J[Elegir actividades]
    H -->|No| I
    I --> J
    J --> K{¿Actividades planeadas?}
    K -->|Sí| L[Preparar presupuesto]
    K -->|No| M[Investigar actividades]
    L --> N{¿Presupuesto listo?}
    M --> N
    N -->|Sí| O[Empacar]
    N -->|No| P[Ajustar presupuesto]
    O --> Q{¿Listo para partir?}
    P --> Q
    Q -->|Sí| R[¡Disfrutar del viaje!]
    Q -->|No| S[Revisar lista de empaque]
    S --> O
