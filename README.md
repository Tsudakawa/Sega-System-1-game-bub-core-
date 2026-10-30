# Sega-System-1-game-bub-core-
Sega System 1 FPGA Core

An open-source FPGA implementation of the classic Sega System 1 (and System 2) arcade hardware. Originally developed and ported by MiSTer-X (MrX-8B) for the MiSTer FPGA project. 
Z80 CPU Core: T80 CPU core by Daniel Wallner.
Ported to Game Bub by ToadyM

Overview

Introduced in 1983, the Sega System 1 was a seminal arcade system board that powered many of Sega's earliest arcade hits. Powered by a Z80 main CPU, dedicated sound generators, and custom tile/sprite display hardware, it featured hardware sprite flipping, multi-layered tilemap scrolling, and vibrant color palettes for its era.

This FPGA core--originally created by prolific arcade core developer MiSTer-X--faithfully recreates the original hardware at the register level. It provides cycle-accurate timing, accurate sound emulation, and modern quality-of-life enhancements for modern displays and controllers.
Notable Supported Games

The Sega System 1 system board hosted an iconic library of early 1980s classics:

    Pitfall II: Lost Caverns (Arcade Version) - Enhanced Sega arcade port featuring unique visual and audio additions.

    Wonder Boy - The legendary platformer that launched a long-running Sega franchise.

    Choplifter - The side-scrolling military helicopter rescue classic.

    Sega Ninja (Ninja Princess) - Fast-paced action shooter utilizing a distinct 3-button directional combat system.

    Mister Viking - Top-down vertical scrolling shooter.

    Up'n Down - High-speed top-down racing and jumping game.

    Flicker / Teddy Boy Blues / My Hero - Essential Sega action-arcade staples.

Key Core Features and Options

In addition to accurate video, CPU, and audio timing, this core includes several quality-of-life options designed for modern displays and controllers:
Tate-Mode and D-Pad Orientation

    Tate-Mode Support: For games originally designed for vertically oriented monitors (e.g., Mister Viking or Up'n Down), the core supports screen rotation for both standard horizontal displays and dedicated vertical arcade setups.

    Tate D-Pad Remapping: When a tate mode game is played,  you have an option to rotate the D-Pad input directions (90 degrees / 270 degrees) so that pressing "Up" on your controller always moves your character "Up" relative to your rotated perspective.

Flexible Button Layout Selection

    Preset Mapping: Toggle between standard arcade control presets (e.g., Type A, Type B) to suit 2-button, 3-button, or fight stick controller layouts.

    Multi-Button Mapping: Map single physical buttons to multi-button combinations (e.g., Button 1 + Button 2 simultaneously) for simplified inputs.

Button 3 on the L or R triggers ( swappable ) (Sega Ninja makes use of this ).

Installation and Setup

    Copy Core Files:

        Place the core .rbf file in the same folder as the corresponding game rom

        and use the .html app to combine and convert those into useable roms.

         Place those roms in a folder on your SDcard


Acknowledgments and License

    Core Author: MiSTer-X (MrX-8B).

    Z80 CPU Core: T80 CPU core by Daniel Wallner.

    Ported to Game bub by Toady M

    Special thanks to the MAME team, arcade preservationists, the MiSTer FPGA contributor community and the Game bub      
    community!
