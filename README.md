```mermaid
graph TD
    %% Nodo Principal
    LIDERAZGO["<b>LIDERAZGO</b><br/>(Concepto Central)"]

    %% Eje Articulador
    EJE["<b>EJE ARTICULADOR: LA INFLUENCIA</b><br/>Capacidad de incidir en los demás para alcanzar metas conjuntas"]
    LIDERAZGO --- EJE

    %% Ramas de Perspectivas de Autores
    EJE --> PERSPECTIVAS["<b>PERSPECTIVAS DE AUTORES</b><br/>(Matices de la influencia)"]

    PERSPECTIVAS --> A1["<b>Gómez (2002) & Chiavenato (1993)</b><br/>Comunicación Interpersonal<br/><i>Coordinación de esfuerzos</i>"]
    PERSPECTIVAS --> A2["<b>Davis & Newstrom (2003)</b><br/>Trabajo en Equipo<br/><i>Movilización del entusiasmo</i>"]
    PERSPECTIVAS --> A3["<b>Kotter (1999)</b><br/>Compromiso Voluntario<br/><i>Sin coacción externa</i>"]
    PERSPECTIVAS --> A4["<b>Max Weber</b><br/>Guía Estructurada<br/><i>Conducción hacia metas compartidas</i>"]
    PERSPECTIVAS --> A5["<b>Platón</b><br/>Cultura de Colaboración<br/><i>Apropiación de un proyecto común</i>"]
    PERSPECTIVAS --> A6["<b>John C. Maxwell</b><br/>Ética y Visión<br/><i>Límite frente a la manipulación</i>"]
    PERSPECTIVAS --> A7["<b>Daft (2006)</b><br/>Relación Recíproca<br/><i>Transformaciones y cambios tangibles</i>"]

    %% Ramas de Tensiones y Miedos Asociados
    EJE --> TENSIONES["<b>TENSIONES Y MIEDOS ASOCIADOS</b><br/>(Vulnerabilidades del líder)"]

    TENSIONES --> M1["<b>Falla de conexión</b><br/>Miedo a no influir"]
    TENSIONES --> M2["<b>Desgaste emocional</b><br/>Miedo a la desmotivación del equipo"]
    TENSIONES --> M3["<b>Deriva autoritaria</b><br/>Miedo a imponer o manipular"]
    TENSIONES --> M4["<b>Desorientación</b><br/>Miedo a perder el rumbo"]
    TENSIONES --> M5["<b>Fragmentación grupal</b><br/>Miedo a los conflictos internos"]
    TENSIONES --> M6["<b>Inoperancia</b><br/>Miedo a no lograr resultados"]

    %% Conexión hacia la Síntesis
    PERSPECTIVAS --> SINTESIS["<b>SÍNTESIS Y REFLEXIÓN FINAL</b><br/>Inspirar, comunicar, orientar y transformar.<br/><i>Riesgo principal: distorsión en control o manipulación.</i>"]
    TENSIONES --> SINTESIS

    %% Estilos visuales
    style LIDERAZGO fill:#1f77b4,stroke:#0d47a1,stroke-width:2px,color:#fff
    style EJE fill:#009688,stroke:#004d40,stroke-width:2px,color:#fff
    style PERSPECTIVAS fill:#eceff1,stroke:#455a64,stroke-width:2px,color:#000
    style TENSIONES fill:#fff3e0,stroke:#e65100,stroke-width:2px,color:#000
    style SINTESIS fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px,color:#000
