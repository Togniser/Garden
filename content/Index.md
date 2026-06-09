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
