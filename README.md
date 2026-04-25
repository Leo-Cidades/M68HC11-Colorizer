# M68HC11 Colorizer

<img width="871" height="871" alt="image" src="https://github.com/user-attachments/assets/6c25fc69-fe3a-41c6-be59-2f9501288781" />

# Español

Extensión de resaltado de sintaxis para código del Microprocesador  
M68HC11 en Visual Studio Code.

Resalta:
- Mnemónicos
- Instrucciones branch y jump
- Labels del lado izquierdo
- Referencias a labels del lado derecho
- Directivas
- Operandos según el modo de direccionamiento
- Instrucciones de subrutinas
- Instrucciones de stack

También agrega:
- Plegado de bloques por `ORG`
- Plegado de bloques por labels

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

## Qué colorea

- Directivas como `p68H11`, `p68HC11`, `ORG` y `END`
- Mnemónicos normales
- Instrucciones de branch y jump
- Labels definidos a la izquierda
- Referencias a labels a la derecha
- Instrucciones de subrutinas como `JSR`, `BSR` y `RTS`
- Referencias y definiciones de subrutinas con color propio
- Instrucciones de stack como `PSHA`, `PSHB`, `PSHX`, `PSHY`, `PULA`, `PULB`, `PULX`, `PULY`, `TSX`, `TXS`, `LDS`, `STS`, `INS` y `DES`
- Operandos según el modo de direccionamiento:
  - Inmediato
  - Directo
  - Extendido
  - Indexado
  - Relativo

## Funciones extra

- Plegado de bloques por `ORG`
- Plegado de bloques por labels
- Mejor separación visual entre labels normales y subrutinas

---

# English

Syntax highlighting extension for Visual Studio Code for the M68HC11 microprocessor.

It highlights:
- Mnemonics
- Branch and jump instructions
- Left-side labels
- Right-side label references
- Directives
- Operands by addressing mode
- Subroutine instructions
- Stack instructions

It also adds:
- Code folding for `ORG` blocks
- Code folding for label blocks

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

## What it highlights

- Directives such as `p68H11`, `p68HC11`, `ORG`, and `END`
- Regular mnemonics
- Branch and jump instructions
- Left-side labels
- Right-side label references
- Subroutine instructions such as `JSR`, `BSR`, and `RTS`
- Subroutine references and definitions with a dedicated color
- Stack instructions such as `PSHA`, `PSHB`, `PSHX`, `PSHY`, `PULA`, `PULB`, `PULX`, `PULY`, `TSX`, `TXS`, `LDS`, `STS`, `INS`, and `DES`
- Operands based on addressing mode:
  - Immediate
  - Direct
  - Extended
  - Indexed
  - Relative

## Extra features

- `ORG` block folding
- Label block folding
- Better visual distinction between regular labels and subroutines
