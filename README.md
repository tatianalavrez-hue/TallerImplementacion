# TallerImplementacion
# Proyecto Integrador

## Estrategia de Branching

### Estrategia seleccionada: GitFlow

**Justificación:**

**1. Tamaño del equipo:**  
El equipo está conformado por 2 integrantes. GitFlow define responsabilidades
claras por tipo de rama (feature, release, hotfix), lo que minimiza conflictos
y facilita la colaboración paralela sin interferencias entre desarrolladores.

**2. Complejidad del proceso de release:**  
GitFlow separa claramente el entorno de desarrollo (`develop`) del entorno
productivo (`main`) mediante ramas `release/*`. Esto permite estabilizar el
código antes de cada entrega sin bloquear el desarrollo de nuevas funcionalidades.

### Ramas del proyecto

| Rama | Propósito |
|------|-----------|
| `main` | Código estable en producción |
| `develop` | Integración continua de features |
| `feature/*` | Desarrollo de nuevas funcionalidades |
| `release/*` | Preparación y estabilización de versiones |
| `hotfix/*` | Correcciones urgentes sobre producción |
