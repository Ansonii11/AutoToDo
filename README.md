# AutoToDo

> [!IMPORTANT]
> Esta extensión es solo un fork de **Todo4VCode** con implementaciones de automatización y gestión inteligente de tareas. Para usar el original vaya a [https://github.com/yurier98/ToDo4VCode.git](https://github.com/yurier98/ToDo4VCode.git)

Deje de ahogarse en listas de tareas interminables. **AutoToDo** es una extensión de gestión de tareas profesional para VS Code que le ayuda a organizar las tareas de su proyecto según su verdadero impacto, asegurando que siempre se concentre en lo que más importa.

## 🤖 Priorización Inteligente y Automatización

A diferencia de otros gestores de tareas, **AutoToDo** incluye un motor de cálculo de prioridad que decide por usted qué es lo más urgente:

- **Auto Priority**: Use el botón de "Auto Priority" para calcular la importancia de una tarea basándose en:
  - **Impacto (1-5)**: Qué tanto valor aporta la tarea.
  - **Dificultad (1-5)**: Qué tan compleja es de realizar.
  - **Tiempo Requerido**: Horas estimadas para completar.
  - **Fecha de Entrega**: Tiempo restante antes del deadline.
- **Ranking Dinámico**: Cuando agrupa sus tareas por prioridad, el sistema les asigna un puesto (1º, 2º, 3º...) calculado algorítmicamente para que sepa exactamente por dónde empezar dentro de cada categoría.

## 🚀 Técnica MoSCoW

Seguimos utilizando la probada técnica MoSCoW para categorizar tareas manualmente:

- **Must (M)**: Tareas críticas no negociables.
- **Should (S)**: Tareas importantes que deberían hacerse pero no son vitales.
- **Could (C)**: Tareas "agradables de tener" si sobra tiempo.
- **Won't (W)**: Tareas reconocidas como no prioritarias por ahora.

## 🛠 Cómo Usar

1. **Abrir la barra lateral**: Haga clic en el icono de tareas en la Barra de Actividad.
2. **Añadir una Tarea**: Escriba el nombre, configure una prioridad (o use Auto Priority) y añada descripción o fecha opcional.
3. **Gestionar**: Arrastre y suelte tareas en el modo Kanban o use el menú contextual para actualizar estado y prioridad.
4. **Enfocarse**: Vea sus tareas de alta prioridad pendientes de un vistazo.

## ⚙️ Configuración

Puede personalizar el comportamiento de la extensión en los ajustes de VS Code:

- `autotodo.hideCompleted`: Ocultar o mostrar tareas completadas.
- `autotodo.defaultPriority`: Establecer la prioridad predeterminada para nuevas tareas.

## 💻 Desarrollo e Instalación

### Modo Desarrollo

1. Clone el repositorio.
2. Ejecute `npm install` (o use `pnpm` / `bun` si lo prefiere).
3. Presione `F5` para abrir el **Extension Development Host**.

### Instalación Permanente (VSIX)

1. Instale `vsce`: `npm install -g @vscode/vsce`.
2. Empaquete: `vsce package`.
3. Instale el archivo `.vsix` generado a través de la vista de Extensiones de VS Code.

---
