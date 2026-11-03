# Fernanda Narahi Rayas Flores

Rol en el proyecto: README y diagrama
- Desarrollo del modelo whisper de transcripción

flowchart TD
    A([Inicio]) --> B[Preparar el proyecto]
    B --> C[Instalar Whisper]
    C --> D[Cargar audio]
    D --> E[Procesar el audio]
    E --> F[Convertir voz a texto]
    F --> G[Obtener texto transcrito]
    G --> H[Revisar el resultado]
    H --> I{¿Está correcto?}
    I -->|No| J[Realizar ajustes]
    J --> D
    I -->|Sí| K[Guardar transcripción]
    K --> L([Fin])
