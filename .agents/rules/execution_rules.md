---
trigger: always_on
description: Reglas estrictas de ejecución, flujo de Git y herramientas para DevSwitchboard
---

# Reglas de Ejecución y Flujo de Trabajo

## 1. Control de Versiones (Git)
- **Jamás encadenar `git add` y `git commit`**: Ejecutar siempre como pasos secuenciales separados, verificando previamente con `git status`.
- **Prohibición de `git push`**: NUNCA ejecutar `git push` hacia ningún remoto salvo orden expresa y directa del usuario.
- **Commits atómicos y progresivos**: Agrupar únicamente archivos relacionados con cada hito o refactor.

## 2. Autonomía y Uso de Herramientas
- **Tests y Lectura**: No pedir confirmación al usuario para ejecutar tests automatizados ni para leer archivos del proyecto.
- **Herramientas Nativas**: Priorizar siempre las herramientas nativas del agente (`view_file`, `grep_search`, `find_by_name`, `list_dir`) sobre scripts en la terminal de PowerShell.
