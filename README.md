# Synapse:A tagless Reaction Test 

A lightning-fast, 10-level reaction time tester 

This project completely bypasses standard DOM elements (like `<div>`, `<button>`, or `<p>`). Instead, the entire user interface, game loop, and state machine are rendered directly onto a single HTML5 `<canvas>` using Vanilla JavaScript.

##  Features

* **Zero Structural Tags:** Built exclusively with `<html>`, `<head>`, `<body>`, `<script>`, `<style>`, and `<canvas>`.
* **10-Level Progression:** Targets get increasingly ruthless, dropping from 500ms down to a frame-perfect 180ms.
* **Canvas-Rendered UI:** All text, colors, and layout are mathematically drawn onto the canvas context.
* **Procedural Audio:** Sound effects (beeps and buzzes) are generated entirely through code using the Web `AudioContext` API—no `<audio>` tags or external MP3s required.
* **Retro Aesthetics:** Uses the JS Font Loading API to force-load the Silkscreen pixel font directly into the canvas memory.

