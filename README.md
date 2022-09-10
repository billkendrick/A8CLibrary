![image info](./A8CLibRefBanner.png)

# A8 C Window Library
Atari 8 Bit Text Mode Windowing Library written in C (CC65).

This is a text mode windowing library complete with window controls and modern gadgets (widgets).  The gadgets allow you to build input forms that use buttons, radio buttons, input strings (with scrolled lengths and type restrictions), check boxes, progress bars, etc.  This allows you to build applications with "modern"-ish interfaces.  

The windowing system preserves the contents under a window, but is not z-order based (by design).  It is up to you to open and close windows in the correct order.  Complete sample programs are included, as well as full API documentation.

I originally wrote this in Action! language for the Atari 8 bit starting around 2015.

I ran into some limitations with the Action! version in a project regarding memory space and function paramater size when compiled into a standlone executable.  This prompted the conversion into C.   I considered several C implementations on the Atari 8 bit itself, then settled on CC65 to use modern development tools and target the A8 platform.

License: GNU General Public License v3.0

See the LICENSE file for full license information.
