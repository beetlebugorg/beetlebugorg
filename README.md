# Jeremy Collins

I'm a software and DevOps engineer by trade. In my own time I build software and 3D-printed hardware, and I write down how, so you can build them too.

Most of my projects are fast native software in Zig and Go: a slicer for 3D printers ([zslice](https://beetlebug.org/projects/zslice/)), a touch screen and print server for Klipper printers ([Printdeck](https://beetlebug.org/projects/printdeck/)), a Tcl interpreter ([ztcl](https://beetlebug.org/ztcl/)), a Tk replacement ([ztk](https://beetlebug.org/ztk/)), a tiling window manager for macOS ([BoxedIn](https://beetlebug.org/boxedin/)), and a chartplotter for boats ([Lookout Marine](https://beetlebug.org/projects/lookout-marine/)). Before those, I made image servers ([go-dims](https://beetlebug.org/projects/go-dims/) and [mod_dims](https://beetlebug.org/projects/mod-dims/)).

My hardware is 3D printed and designed in code, so each dimension is a named value that you can change.

Each project has a page on [beetlebug.org](https://beetlebug.org/), and each 3D-printed build has a full guide.

## Featured

<table>
<tr><td width="25%" valign="top"><a href="https://beetlebug.org/projects/zslice/"><img src="https://beetlebug.org/img/zslice/profile.webp" alt="zslice" width="120"></a></td><td width="25%" valign="top"><a href="https://beetlebug.org/ztcl/"><img src="https://beetlebug.org/img/ztcl/profile.webp" alt="ztcl" width="120"></a></td><td width="25%" valign="top"><a href="https://beetlebug.org/boxedin/"><img src="https://beetlebug.org/img/boxedin/profile.webp" alt="BoxedIn" width="120"></a></td><td width="25%" valign="top"><a href="https://beetlebug.org/ztk/"><img src="https://beetlebug.org/img/ztk/profile.webp" alt="ztk" width="120"></a></td></tr>
<tr><td width="25%" valign="top"><b><a href="https://beetlebug.org/projects/zslice/">zslice</a></b><br><sub>A slicer for FDM 3D printers, written from scratch in Zig. It slices a 3DBenchy in about 340 ms, and it runs in the browser too.</sub></td><td width="25%" valign="top"><b><a href="https://beetlebug.org/ztcl/">ztcl</a></b><br><sub>A sandboxed Tcl interpreter in Zig, with a bytecode VM, a garbage collector, and an experimental x86-64 JIT that is off by default.</sub></td><td width="25%" valign="top"><b><a href="https://beetlebug.org/boxedin/">BoxedIn</a></b><br><sub>Hyprland-style tiling for macOS, configured in Tcl. It is closed source and free while in preview.</sub></td><td width="25%" valign="top"><b><a href="https://beetlebug.org/ztk/">ztk</a></b><br><sub>An experimental Tk replacement in Zig, on ztcl. The plan is native GPU rendering: Metal on macOS, D3D12 on Windows, and Vulkan on Linux.</sub></td></tr>
</table>

## More software

- [Printdeck OS](https://beetlebug.org/projects/printdeck-os/): The software side of Printdeck: the Klipper host, ported to Go, with a touch screen, in a read-only Linux image for the Raspberry Pi 5.
- [Lookout Marine](https://beetlebug.org/projects/lookout-marine/): A chartplotter that renders official ENC charts at 60 fps, native on six platforms.
- [go-dims](https://beetlebug.org/projects/go-dims/): An image server in Go that resizes, crops, and converts images from the URL.
- [mod_dims](https://beetlebug.org/projects/mod-dims/): The Apache httpd module that resizes, crops, and converts images on request.
- [Tekmetric MCP](https://beetlebug.org/projects/tekmetric-mcp/): Ask Claude about your auto repair shop's Tekmetric data in plain English.

## Hardware

- [Printdeck](https://beetlebug.org/projects/printdeck/): The Printdeck Slate v4: a 5-inch touch screen and print server for Klipper printers, in a case on the desk. A Raspberry Pi 5 runs the Klipper host, ported to Go.
- [Pod for Bittle X Robot](https://beetlebug.org/projects/bittle-x-pi-addon/): A 3D-printed pod for the Petoi Bittle X. It holds a Raspberry Pi Zero 2 W, a PiSugar S battery, an amp, a speaker and a mic.
- [Mini](https://beetlebug.org/projects/bluetooth-speaker/): A Braun-style Bluetooth desk speaker with two 2.5-inch drivers and a printed snap-on grille.
- [Espresso Cup Holder](https://beetlebug.org/projects/espresso-cup-holder/): A two-piece, tool-free cup stand for the Rancilio Silvia Pro X.
- [Pen Plotter](https://beetlebug.org/projects/penplotter/): A table pen plotter from the parts of a Creality CR-10 V3. The stock control box runs new firmware in Go.

<sub>Made from the project data of [beetlebug.org](https://beetlebug.org/).</sub>
