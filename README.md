<p align="center">
  <img src="dibujo.svg" alt="Texto Cabecera Daniel Moret" width="100%" />
</p>

## Hi there 👋
> My name is Daniel Moret Robledo, I'm a 2nd-year student of Multiplatform Application Development (DAM) - focused on mobile and back-end technologies.

## 🧑‍💻 About Me:
- 📖 I enjoy diving into **Epic Fantasy** ⚔️ and **classic literature** 
- 🎮 I like to **play videogames** 
- 💡 I am **restless** and **curious**, always **discovering new interests** and areas of study

## 📫 Reach Me:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)]([])
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:danielmoretrobledo@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-dannielmrt-5865F2?style=flat-square&logo=discord&logoColor=white)](#)


## 🌟 Highlights:

#### 💡 Problem & Solution
The objective was to design a dynamic header to enhance the professional presentation of this README. The chosen solution was creating a custom animated SVG (Scalable Vector Graphic) for a clean integration, which I considered a better option than other alternatives such as a gif.

#### 🛠️ Key Technologies
- SVG (Scalable Vector Graphics): For the vector image base.

- CSS/SVG Animation: With the tag \<linearGradient> used to create the dynamic color flow and \<animate> tags for effects like the pulsating white circles.

#### ⚙️ Code (Animation)
```svg
    [...]
    <!-- Animación gradiente de color -->
    <linearGradient id="gradiente" x1="0%" y1="0%" x2="100%" y2="25%">
        <stop offset="0%" style="stop-color:#2a7b9b;"/> 
        <stop offset="15%" style="stop-color:#3e9d91;"/>
        <stop offset="50%" style="stop-color:#57c785;"/>
        <stop offset="85%" style="stop-color:#3e9d91;"/>
        <stop offset="100%" style="stop-color:#2a7b9b;"/> 
        
        <animate attributeName="x1" from="-100%" to="200%" dur="6s" repeatCount="indefinite" />
        <animate attributeName="x2" from="0%" to="700%" dur="6s" repeatCount="indefinite" />
    </linearGradient>

<rect [...]
</defs>
<g inkscape:label="Capa 1" inkscape:groupmode="layer" id="layer1">
    <path [...]

    <!-- Circulo animado -->
    <circle cx="100" cy="25" r="2.5" fill="white">
        <animate attributeName="opacity" values="0.6; 0.1; 0.6; 0.3" dur="1.8s" repeatCount="indefinite" />
    </circle>

    <circle cx="400" cy="10" r="3" fill="white">
        <animate attributeName="opacity" values="0.5; 0.1; 0.5; 0.2" dur="3s" begin="1.5s" repeatCount="indefinite" />
    </circle>
    [...]
```

#### ✨ Personal Reflection

I selected this feature mainly because I enjoyed and found curious the design process. It allowed me to use familiar technologies, such as xml, but going deeper into the SVG vector image format. Besides, to apply it to a visual element and integrating CSS functions for animation was interesting to do and learn
 
---
