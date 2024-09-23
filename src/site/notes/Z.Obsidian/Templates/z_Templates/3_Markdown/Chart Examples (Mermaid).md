---
{"dg-publish":true,"permalink":"/Z.Obsidian/Templates/z_Templates/3_Markdown/Chart Examples (Mermaid)/"}
---

```mermaid
graph LR
  %%==============%%
  %% Declarations %%
  %%==============%%
    A[Indent Paragraph]
    B[Insert Markdown Images]
    C[Insert Rollable Table]
  %%=========%%
  %% Linking %%
  %%=========%%
  %% comment
  A --> B & C
 
  %% subgraph
   https://mermaid-js.github.io/mermaid/#/classDiagram
 classDiagram
  Animal <|-- Duck
  Animal <|-- Fish
  Animal <|-- Zebra
  Animal : +int age
  Animal : +String gender
  Animal: +isMammal()
  Animal: +mate()
  class Duck{
    +String beakColor
    +swim()
    +quack()
  }
  class Fish{
    -int sizeInFeet
    -canEat()
  }
  class Zebra{
    +bool is_wild
    +run()
  }
```

```mermaid
gantt
  dateFormat  YYYY-MM-DD
  title   Adding GANTT diagram functionality to mermaid
  excludes  weekends
  {init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#ff0000'}}}%%
journey
  title My working day
 
  section Go to work
  Make tea: 5: Me
  Go upstairs: 3: Me
  Do work: 1: Me, Cat
 
  section Go home
  Go downstairs: 5: Me
  Sit down: 5: Me
```
