# Nano Banana — Pruebas

Repositorio de pruebas y experimentación para el proyecto **Claude Banana**, un agente de ingeniería de prompts para generación de imágenes con IA.

## Qué es Claude Banana

Claude Banana transforma descripciones simples en prompts optimizados para generadores de imágenes por IA. Le dices qué imagen quieres y construye las instrucciones perfectas.

El agente usa una fórmula de 7 componentes para generar prompts detallados compatibles con Gemini, Midjourney, DALL-E y Stable Diffusion.

## Estructura

```
claude-banana/          — Proyecto principal del agente
  knowledge/            — Base de conocimiento: fórmulas, técnicas, dominios
  templates/examples/   — 25 plantillas de prompts parametrizadas
  presets/              — Presets de marca y estilo en JSON
  scripts/              — Utilidades Python para generación y procesamiento
```

## Uso

```bash
# Iniciar en el directorio del proyecto
cd claude-banana
# Abrir Claude Code y describir la imagen que deseas crear
```

## Nota

Este repo es un entorno de pruebas. Para el proyecto estable, ver el repositorio principal de Claude Banana.
