---
layout: page
title: "Example Exercise"
permalink: https://sanderrenes.github.io/econExcercises/exampleExercise
body_class: exercise-page
---
Embedding in GitHub is giving layout issues, so please open the exercise in a new window. 

<button id="open-exercise" style="padding: 12px 24px; font-size: 1.2em; background-color: #4CAF50; color: white; border: none; border-radius: 5px; cursor: pointer;">
  Open Exercise in New Window
</button>

<script>
document.getElementById("open-exercise").onclick = function() {
  // Open a new window with reasonable defaults
  const win = window.open("", "_blank", "noopener,noreferrer,width=1200,height=800");
  // Write HTML that makes the iframe fill the window
  win.document.write(`
    <html>
      <head>
        <title>Grasple Exercise</title>
        <style>
          html, body {
            height: 100%;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background: #f4f4f4;
          }
          iframe {
            width: 100vw;
            height: 100vh;
            border: none;
            display: block;
            background: #fff;
          }
        </style>
      </head>
      <body>
        <iframe height="560" src="https://embed.grasple.com/exercises/fb6f746a-60e0-40a2-8aee-ab1d82ae2c25?id=95769" title="Grasple Exercise 95769" width="100%" allow="clipboard-read; clipboard-write"></iframe>
      </body>
    </html>
  `);
};
</script>
