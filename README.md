# Code Snippets for MCJE Shaders

## mcje-shader-snippets

mcje-shader-snippets is a vecode extension that provides lots of code snippets for Minecraft Java Edition shaderpack developing. It provides amlost all attributes, uniforms and macros in Optifine documention, makes shader developers write shader imports extreme quickly.

## Dependencies

This extension depends on [GeforceLegend](https://github.com/GeForceLegend)'s [GLSL Syntax for VS Code](https://github.com/GeForceLegend/vscode-glsl) to provides basic syntax highlighting and GLSL code snippets.

## Features

This extension provides a complete snippet sets from first word to a full statement. For example, this extension can provide `uniform` at first, then provide `sampler2D` and `sampler2DShadow` when typing `s` after uniform, and provide all available buffers at the same time.

Almost full code snippets for Minecraft Java Edition shaderpack developing. Each snippet includes single name (e.g. `colortex0`) and full import code (e.g. `uniform sampler2D colortex0;`) and even comment variant if available(e.g. `/* SHADOWRES:1024 */`).

Shader features added in recent Optifine updates (e.g. `/* RENDERTARGETS: 1,2,7,12 */`) are also included in this extension.
