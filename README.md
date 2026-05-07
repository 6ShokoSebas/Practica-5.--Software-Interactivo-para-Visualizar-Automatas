# Practica-5.--Software-Interactivo-para-Visualizar-Automatas

## 👥 Autores

- **Gustavo Sebastián Bonilla Ojeda** — 2025630175  
- **Ximena Velázquez Mendoza** — 2024630176  
- **Yoltic Isaí Velázquez Ramos** — 2025230228  

📍 *ESCOM - Instituto Politécnico Nacional*  
📅 *Fecha: 07 de mayo de 2026*  

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

# Tecnologías utilizadas

- Python 3
- Tkinter
- XML (`ElementTree`)
- JSON
- NetworkX
- Matplotlib

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
