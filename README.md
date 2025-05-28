# Tetris en Ensamblador 8086

Este proyecto implementa el clásico juego de Tetris utilizando lenguaje ensamblador para la arquitectura Intel 8086. El juego fue desarrollado en el entorno **EMU8086** y puede ejecutarse mediante el emulador **DOSBox**.

---

## 🛠️ Pasos para Crear un Archivo `.EXE` en EMU8086

### 1. Abrir EMU8086
Inicia el programa **EMU8086 IDE**.

### 2. Cargar el archivo `.asm`
- Ve a `File → Open`.
- Selecciona tu archivo ensamblador (por ejemplo `tetris.asm`).

### 3. Compilar el programa
- Haz clic en el botón **Compile** (ícono del rayo o presiona `F5`).
- Si hay errores, se mostrarán en la parte inferior. Corrígelos y vuelve a compilar.

### 4. Generar el archivo `.EXE`
- Ve al menú `Compile → Make EXE File` o `Build EXE`.
- Esto creará un archivo `.exe` en la carpeta del proyecto.

### 📁 Ubicación del archivo `.exe`
Por defecto, EMU8086 guarda el ejecutable en:
C:\emu8086\MyBuild\


También puede estar en la misma carpeta donde abriste el archivo `.asm`.

Si no sabes dónde quedó, puedes buscarlo escribiendo `tetris.exe` en el Explorador de archivos.

---

## ▶️ Cómo Ejecutar el .EXE en DOSBox

1. Abre **DOSBox**.
2. Monta la carpeta donde está tu `.exe` como unidad virtual en DOSBox:

```dos
mount C C:\emu8086\MyBuild
C:
tetris.exe
¡Disfruta del juego!
