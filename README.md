# Reto 2026 - QA - E2E Tests (Ithaka & Nettra)

Repo de **pruebas End-to-End (E2E)** para los dos proyectos del Reto:
- **Ithaka**
- **Nettra**

La idea es mantener **un repo por tipo de prueba** (API / E2E / Performance / IA).  
Dentro de cada repo se separa por proyecto (Ithaka / Nettra).

## Estructura

- `pages/` Page Objects (POM)
  - `pages/base_page.py` base común reutilizable
  - `pages/ithaka/` páginas específicas de Ithaka
  - `pages/nettra/` páginas específicas de Nettra
- `tests/ithaka/` tests E2E de Ithaka
- `tests/nettra/` tests E2E de Nettra
- `data/` datos de prueba por proyecto
- `docs/` documentación útil (flujos críticos, notas, links)
- `reports/` reportes
- `scripts/` helpers
