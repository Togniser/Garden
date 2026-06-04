---
publish: true
title: Fields of research
created: 2026-05-25T12:20:37.375+02:00
modified: 2026-06-04T17:21:49.579+02:00
---

<head>
  ...
  <script src="https://unpkg.com/telescopic-text/lib/index.js"></script>
  <link
    href="https://unpkg.com/telescopic-text/lib/index.css"
    rel="stylesheet"
  />
</head>

Sta prendendo piede
Ogni tanto uso il pc
Ogni tanto uso i quaderni

<body>
  <div id="text-container"></div>

  <script>
    const content = `
  * I am 
  * SER
	  * Togni Ser
		  * SerT
			  * Stefano Togni
  * , a cartoonist.
	  * , a cartoonist and an architect.
		  * , cartoonist, architect and game designer.`;
    const node = createTelescopicTextFromBulletedList(content);
    const container = document.getElementById("text-container");
    container.appendChild(node);
  </script>

</body>

> [!info]- NULLA REDEMPTIO
> Questo è il testo nascosto all'interno del callout.
> Può contenere anche elenchi o più paragrafi.
