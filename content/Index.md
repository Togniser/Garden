---
publish: true
title: Fields of research
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

<div data-auto-card-link-depth="-1" class="auto-card-link-container"><a href="https://beampress.it" class="auto-card-link-card external-link"><div class="auto-card-link-main"><div class="auto-card-link-title">Dalla valle dell'orto</div><div class="auto-card-link-host"><span>beampress.com</span></div></div><img draggable="false" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYCFJa4fO06Ge9dqCu0O04BHLUnqdSm9zmkg&amp;s" class="auto-card-link-thumbnail" /></a></div>

Ego
