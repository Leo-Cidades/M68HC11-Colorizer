# Español

Extensión de resaltado de sintaxis para código del Microprocesador 
M68HC11 en Visual Studio Code.

Resalta:
- Mnemónicos
- Instrucciones branch
- Labels del lado izquierdo
- Referencias a labels del lado derecho
- Directivas
- Operandos según el modo de direccionamiento

## Instalación

### Instalar desde VSIX
1. Descarga el archivo `.vsix` de la extensión.
2. Abre Visual Studio Code.
3. Ve a la vista de extensiones.
4. Haz clic en los tres puntos `...` en la esquina superior derecha.
5. Selecciona **Install from VSIX...**
6. Elige el archivo `.vsix`.
7. Recarga la ventana si es necesario.

## Uso

La extensión reconoce archivos con extensiones como:
- `.asm`
- `.a68`
- `.hc11`
- `.msa`

Si VS Code no detecta el lenguaje automáticamente:
1. Abre el archivo.
2. Haz clic en el selector de lenguaje en la esquina inferior derecha.
3. Selecciona **M68HC11**.

Nota: Para que los comentarios cambien de color, agregar ';' delante de ellos.

## Qué colorea

- Directivas como `ORG` y `END`
- Mnemónicos normales
- Instrucciones de branch
- Labels definidos a la izquierda
- Referencias a labels a la derecha
- Operandos según el modo de direccionamiento

---

# English

Syntax highlighting extension for Visual Studio Code for the microprocessor M68HC11.

It highlights:
- Mnemonics
- Branch instructions
- Left-side labels
- Right-side label references
- Directives
- Operands by addressing mode

## Installation

### Install from VSIX
1. Download the extension `.vsix` file.
2. Open Visual Studio Code.
3. Go to the Extensions view.
4. Click the `...` menu in the top-right corner.
5. Select **Install from VSIX...**
6. Choose the `.vsix` file.
7. Reload the window if needed.

## Usage

The extension recognizes files such as:
- `.asm`
- `.a68`
- `.hc11`
- `.msa`

If VS Code does not detect the language automatically:
1. Open the file.
2. Click the language selector in the bottom-right corner.
3. Select **M68HC11**.

Note: To make the comments change color, add ';' in front of them.

## What it highlights

- Directives such as `ORG` and `END`
- Regular mnemonics
- Branch instructions
- Left-side labels
- Right-side label references
- Operands based on addressing mode
