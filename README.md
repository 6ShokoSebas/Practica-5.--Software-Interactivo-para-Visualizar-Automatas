# Practica-5.--Software-Interactivo-para-Visualizar-Automatas

# Simulador de Autómatas Finitos en Python

Simulador interactivo de autómatas finitos desarrollado en Python con Tkinter inspirado en JFLAP.

Permite crear, editar, visualizar y simular:

- AFD
- AFND
- AFN-λ

Incluye herramientas de conversión, minimización, simulación visual y exportación/importación de archivos `.jff`.

---

# Características

## Editor visual tipo JFLAP

- Crear estados con clic
- Arrastrar estados (drag & drop)
- Crear transiciones interactivamente
- Loops automáticos
- Eliminación de estados y transiciones
- Estados iniciales y de aceptación
- Visualización dinámica en Canvas Tkinter

---

## Simulación de autómatas

### AFD
- Simulación rápida
- Simulación paso a paso
- Resaltado visual de estados

### AFND
- Simulación visual con múltiples estados activos
- Visualización de conjuntos de estados
- Animación de procesamiento

### AFN-λ
- Cálculo de λ-clausura
- Simulación visual de λ-transiciones
- Resaltado de clausuras activas

---

## Conversión entre autómatas

- AFN-λ → AFND
- AFND → AFD (Construcción de subconjuntos)

---

## Minimización de AFD

- Eliminación de estados inaccesibles
- Detección de estados equivalentes
- Comparación visual entre autómata original y minimizado

---

## Conversión AFD → Expresión Regular

Implementación del algoritmo GNFA mediante eliminación de estados.

---

## Herramientas adicionales

- Tabla de transiciones
- Visualización de grafos
- Operaciones de lenguaje:
  - Prefijos
  - Sufijos
  - Subcadenas
  - Cerradura positiva
  - Cerradura de Kleene

---

# Tecnologías utilizadas

- Python 3
- Tkinter
- XML (`ElementTree`)
- JSON
- NetworkX
- Matplotlib

---

# Instalación

## Clonar repositorio

```bash
git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
cd TU_REPOSITORIO
```

---

## Instalar dependencias

```bash
pip install matplotlib networkx
```

---

# Ejecución

```bash
python simulador_p4.py
```

---

# Uso

## Crear autómata manualmente

1. Abrir pestaña Visualizador JFLAP
2. Seleccionar "Modo Estados"
3. Hacer clic para crear estados
4. Seleccionar "Modo Transiciones"
5. Clic derecho sobre estado origen y destino
6. Ingresar símbolo de transición

---

## Mover estados

Arrastrar con clic izquierdo.

---

## Eliminar elementos

### Estados
- Activar "Modo Borrar"
- Hacer clic sobre el estado

### Transiciones
- Activar "Modo Borrar"
- Hacer clic sobre la transición

---

## Simular cadenas

1. Ingresar cadena
2. Presionar:
   - "Validar Rápido"
   - "Paso a Paso"
   - "Simular"

---

# Compatibilidad con JFLAP

El simulador soporta:

- Importación de archivos `.jff`
- Exportación de `.jff`
- Conservación de posiciones visuales de estados

---

# Capturas

## Editor visual

<img width="700" alt="editor" src="docs/editor.png">

---

## Simulación AFND

<img width="700" alt="afnd" src="docs/afnd.png">

---

## Minimización

<img width="700" alt="min" src="docs/minimizacion.png">

---

# Estructura del proyecto

```text
simulador_p4.py
README.md
docs/
```

---

# Funcionalidades implementadas

- [x] AFD
- [x] AFND
- [x] AFN-λ
- [x] Simulación visual
- [x] λ-clausura
- [x] Minimización
- [x] Conversión AFND → AFD
- [x] Conversión AFN-λ → AFND
- [x] Exportación JFLAP
- [x] Editor visual
- [x] Drag & Drop
- [x] Eliminación de estados
- [x] Eliminación de transiciones
- [x] Loops visuales
- [x] Simulación animada

---

# Posibles mejoras futuras

- Zoom y desplazamiento
- Undo / Redo
- Curvas Bezier avanzadas
- Simulación de PDA
- Máquina de Turing
- Exportación a imagen
- Temas visuales

---

# Autor

Desarrollado como proyecto de Teoría de la Computación / Autómatas Finitos.

---

# Licencia

MIT License
