# Retro.IDE
Integrated Development Environment (IDE) editors, compilers, assemblers, and tools for developing retro software!

# Try again

Retro.IDE proper will mainly be the text and graphic editors that bring together the languages and tools that make up the IDE for developing retro software.  

* Retro.IDE  
  * Source Editors for Assembly, BASIC, C, C#, Java, Pascal, Python (others later)
  * Flowchart editor 
  * Tile editor and layouts
  * Graphic editor for Sprites and Animation.
  * Graphic editor and converter for bitmap graphics (converter to other formats)
  * Graphic editor for sound effects
  * Graphic editor for music

The following sub-projects will be separate stand-alone projects that the Retro.IDE can make use of, amongst others. 

* Sub-Projects
  * Base - Shared code and resources among all projects
  * CPU - Assemblers/Dis-assemblers for retro CPU's + Use existing Assemblers (LWASM, asm6809, Tasm6801, cc65, z88dk + others)
  * Emu - Multi-CPU, multi-target emulation for integrated testing
  * XLang - Multi-Language ASTs, Lexers, Parsers  
  * Tools
    * Retro.HDL - Simulate FPGA code 
    * Retro.Media - Multi-Tape/Disk for retro tape, floppy, and hard-drive formats
  * Compilers
    * Retro.BASIC - Retro BASIC compiler (w/ possible byte-code mode)
    * Retro.C - Use existing retro C compilers (CMOC, cc65, z88dk + others)
    * Retro.JVM - JVM byte-code Ahead-of-Time (AoT) compiler for retro CPU's
    * Retro.NET - .NET CIL byte-code Ahead-of-Time (AoT) compiler for retro CPU's
    * Retro.Pascal - Pascal compiler for retro systems 
    * Retro.STPy - Compiler for Python using Static Types (NOT dynamic!) 