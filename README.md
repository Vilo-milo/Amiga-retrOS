# retrOS

retrOS 1.0 (Kickstart)
=====================

Welcome to retrOS, a fan-made desktop operating system based on Debian
GNU/Linux 13, styled after the look and feel of AmigaOS. retrOS brings the
Workbench back to life with a retro CRT boot splash, an Amiga-style desktop
theme, and a library of Amiga-inspired wallpapers.

This is a side project. retrOS is built on the shoulders of giants and is
provided as-is, with no warranty. Most things work exactly the same as on
Debian, so any Debian documentation applies here too.

--------------------------------------------------------------------
Getting started
--------------------------------------------------------------------

  * Log in at the LightDM greeter. Your desktop uses the Xfce desktop
    environment with the "Amiga" window-manager theme and a Workbench-style
    GTK theme (chunky bevels, pixel font, blue titlebars).

  * To switch wallpapers: right-click the desktop -> Desktop Settings ->
    choose one of the wallpapers in /usr/share/backgrounds/retrOS, or
    right-click the desktop -> Workspace wallpapers.

  * Open a terminal with the terminal icon in the panel (top-right), or
    from the applications menu.

  * If you install additional software, use apt exactly as on Debian:

        sudo apt update && sudo apt install <package>

--------------------------------------------------------------------
About the look
--------------------------------------------------------------------

  * Boot: a Workbench-blue splash screen with a rainbow pixel-art logo and
    a segmented progress bar (Plymouth theme "retrOS").
  * Login: a matching Workbench-blue greeter.
  * Desktop: Xfce with the Amiga window theme, Workbench GTK widgets, and a
    monospace font for that 1985 terminal feel.
  * Wallpapers: all artworks in /usr/share/backgrounds/retrOS are by 8080
    (https://8080.itch.io/). Please support them if you enjoy the art.

--------------------------------------------------------------------
Credits and thanks
--------------------------------------------------------------------

  * AmigaOS and Workbench: the look we all love (fan-made homage, no
    affiliation with or endorsement by Amiga Inc. or Hyperion Entertainment).
  * Base system: the Debian Project (https://www.debian.org/).
  * Desktop environment: the Xfce project (https://xfce.org/).
  * Wallpapers: 8080 (https://8080.itch.io/).
  * Built with help from opencode AI (https://opencode.ai/).

--------------------------------------------------------------------
Troubleshooting
--------------------------------------------------------------------

  * Most problems can be fixed the same way as on Debian. Search for your
    error message along with "Debian 13" and you will usually find the fix.
  * This is a side project and may not receive regular updates. For
    interactive help, opencode AI is included on the system and can walk
    you through most troubleshooting steps.

Enjoy, and thanks for trying retrOS!
- The creator.
