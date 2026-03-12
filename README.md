NEO-Shell — LS-NS Interpreter
> **Logic Components Corp** · *Interpreted scripting firmware for microcontrollers*
![NEO-Shell Poster](main/IMAGES/NEO_POSTER.png)
---
What is it?
LS-Neo Shell is a minimal interpreted programming language designed to run small pieces of NEO-Shell code directly on a microcontroller, eliminating the need for a full compilation cycle. There is no compile step — the interpreter lives in the microcontroller's memory and executes commands immediately, saving both development time and the overhead of flashing new firmware for every change.
---
Where can it be used?
NEO-Shell was designed primarily for research, laboratory and development environments, thanks to its built-in control over microcontroller I/O ports and dedicated commands for PWM signal management.
Its simplicity and pseudo-Basic syntax with C-derived elements also make it a practical tool for educational contexts — an approachable environment for learning the fundamentals of microcontroller programming.
---
Pros & Cons
✅ Advantages
Fast iteration — no compilation from PC to microcontroller. The interpreter is already installed in memory, so code runs immediately after typing.
Fault-tolerant execution — unlike many languages and interpreters, a malformed or unrecognised command does not halt the program. NEO-Shell will report the offending command and continue executing the rest of the code.
⚠️ Disadvantages
Speed — being an interpreted language, the processing speed and response time of each individual command can be slow. This makes NEO-Shell unsuitable for applications where timing is critical.
Limited instruction set — the available commands are intentionally minimal and not designed for professional-grade applications that require a full-featured programming language.
---
Updates & Roadmap
🚀 NEO-Shell Simulator — DEMO 1
Release date: 13/03/2026
The first public demo of NEO-Shell is now available. It includes:
A terminal executable for Windows 64-bit (32-bit not supported)
The NEO-SIM circuit simulator demo
Command reference documentation in English, Japanese and Italian
A small boot demo that runs automatically when the simulator starts
📦 Coming soon — Work in Progress
Scheduled releases from 13/04/2026 to 13/05/2026:
Program	Description
NEO-Shell Installer	Compiler/flasher targeting ATmega 1284P
NEO-SIM	Full GUI simulator with graphical workbench and block-based visual programming
NEO-IDE	PC ↔ MCU terminal interface with integrated code editor
---
Links & Contacts
🌐 Website & online simulator: lukeprojects04
📸 Instagram: @lukeProject04
📧 Email: lukeprojects04@gmail.com
---
<sub>NEO-Shell · Logic Components Corp · 2024–2026</sub>
