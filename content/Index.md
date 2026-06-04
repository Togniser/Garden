---
publish: true
title: Fields of research
created: 2026-05-25T12:20:37.375+02:00
modified: 2026-06-04T17:02:00.713+02:00
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

> [!info]- Sono Ser
> Questo è il testo nascosto all'interno del callout.
> Può contenere anche elenchi o più paragrafi.

```telescopic id="reading"
* I'm
* reading
  * reading a lot of
    * Nietzsche,
    * Wittgenstein,
		 * hosting functions,
	 * and, go on longs walks,
	   * building [[thoughts/work|open-source project]],
	    * this [pan](https://example.com)
```

<body>
  <div id="text-container"></div>

  <script>
    const content = `
  * I 
    * Yawning, I
  * made tea`;
    const node = createTelescopicTextFromBulletedList(content);
    const container = document.getElementById("text-container");
    container.appendChild(node);
  </script>

</body>
