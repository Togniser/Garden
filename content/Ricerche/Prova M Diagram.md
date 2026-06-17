---
publish: true
---

```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```

```mermaid
flowchart TB

    A["SERT"] -- No way --> B("Go down!!")

    B --> C{"Let me think"}

    C -- One --> D["Laptop"]

    C -- Two --> E["iPhone"]

    C -- Three --> F["fa:fa-car Car"]
```

flowchart TD

```mermaid
---

config:

  theme: redux

  layout: dagre

---

flowchart TB

    subId[["Eccomi"]] --> roundedId("Non di nuovo!")

    n1["Terribilis est"] --> roundedId

  

    n1@{ img: "https://togniser.github.io/Garden/pasted-image-20260524171922.png", h: 381, w: 270, pos: "b", constraint: "on"}
```

```mermaid
---

config:

  theme: redux

  layout: dagre

---

flowchart TB

    subId[["Eccomi"]]

    n1["This is sample label"]

    n2["This is sample label"]

    n3["This is sample label"]

  

    n1@{ img: "https://togniser.github.io/Garden/pasted-image-20260524171922.png", h: 381, w: 270, pos: "b", constraint: "on"}

    n2@{ img: "https://static.mermaidchart.dev/whiteboard/default-image-shape.svg", h: 200, w: 200, pos: "b"}

    n3@{ img: "https://static.mermaidchart.dev/whiteboard/default-image-shape.svg", h: 200, w: 200, pos: "b"}
```

flowchart TD

   
