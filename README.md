# Assembly Hangman Game

This project is an implementation of the classic Hangman game written in assembly language using MASM (Microsoft Macro Assembler). The game features graphical representations of the hangman and provides interactive gameplay through the command prompt.

## Features

- **Graphical Hangman Representations**: Visual updates of the hangman based on the number of remaining lives.
- **Interactive Gameplay**: Users can guess letters to try to figure out the hidden word.
- **Random Word Selection**: The game selects a word randomly from a predefined list at the start of each game.

## Prerequisites

Before you can run this Hangman game, you'll need:

- **MASM32 SDK**: The Microsoft Macro Assembler (MASM) provides a complete development environment for assembling and debugging assembly language programs for the x86 (IA-32) architecture.
- **A compatible Editor**: Any text editor that can save plain text files, such as Notepad++, Visual Studio Code, or Sublime Text.

## Installation

### Step 1: Install MASM32 SDK

Download and install the MASM32 SDK from the official website or a trusted source. This SDK contains the necessary assembler, linker, and libraries required to compile and link your assembly programs.

### Step 2: Clone the Repository

```bash
git clone <https://github.com/yourusername/assembly-hangman.git](https://github.com/mujtabasaqib19/Hangman-Game-in-Assembly-Language>
cd assembly-hangman
```

### Step 3: Open and Assemble the Code

1. Open the `.asm` file in your editor.
2. Use the MASM32 tools to assemble and link the code. Typically, this can be done via a batch script or manually in the command prompt as follows:

```bash
ml /c /Zd /coff hangman.asm
link /SUBSYSTEM:CONSOLE hangman.obj
```

This will create an executable named `hangman.exe`.

## Usage

Run the game by navigating to the directory containing your compiled executable and executing it:

```bash
hangman.exe
```

Follow the on-screen prompts to play the game.

## Acknowledgments

- Thanks to the developers and contributors of the MASM32 SDK.
- The gaming community for their continuous inspiration and support.

## Feedback and Contact

- Feel free to give feedback and contact on email mujtabasaqib654@gmail.com

