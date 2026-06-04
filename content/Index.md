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

```cardlink
url: https://beampress.it
title: "Dalla valle dell'orto"
host: beampress.com
favicon: https://it.wikipedia.org/static/favicon/wikipedia.ico
image: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQYCFJa4fO06Ge9dqCu0O04BHLUnqdSm9zmkg&s
```
