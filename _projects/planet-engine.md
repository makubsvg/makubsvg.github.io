---
title: PlanetEngine
description: A game and multi purpose graphics engine using SDL and OpenGL.
date: 2026-10-28
---

PlanetEngine is my custom engine powering various of my projects including [triangleRTS]({% link _projects/trianglerts.md %}) and tdLab.
It is written in C++ and uses SDL2 and OpenGL.
Some of its key systems are:
- abstractions of opengl with a neat 2d rendering system.
- an ui library with support for buttons, text and number inputs, scrollbars, sliders.
- a system for abstracting input binds.
- text rendering from an atlas texture generated using glyphs from SDL_ttf.

PlanetEngine has evolved from an initial planet rendering demo I made and I added features as needed to it.