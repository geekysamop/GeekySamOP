### Hi there 👋

<!--
**geekysamop/GeekySamOP** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ... Full stack
- 🌱 I’m currently learning ... Javascript
- 👯 I’m looking to collaborate on ... 
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
![Geekysamop's GitHub stats](https://github-readme-stats.vercel.app/api?username=GeekysamOP&theme=dark&show_icons=true)
<!DOCTYPE html> 
 <html lang="en"> 
  
 <head> 
     <meta charset="UTF-8"> 
     <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
     <title>Page Not Found</title> 
     <link rel="preconnect" href="https://fonts.googleapis.com"> 
     <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
     <link href="https://fonts.googleapis.com/css2?family=Dosis:wght@800&display=swap" rel="stylesheet"> 
     <script src="https://cdnjs.cloudflare.com/ajax/libs/tsparticles/2.9.3/tsparticles.min.js"></script> 
     <script src="https://cdnjs.cloudflare.com/ajax/libs/tsparticles/2.9.3/tsparticles.bundle.js"></script> 
     <script src="https://cdnjs.cloudflare.com/ajax/libs/tsparticles/2.9.3/tsparticles.bundle.min.js"></script> 
     <script src="https://cdnjs.cloudflare.com/ajax/libs/tsparticles/2.9.3/tsparticles.js"></script> 
     <link rel="shortcut icon" href="/favicon.ico" type="image/x-icon"> 
  
     <style> 
         body { 
             background-color: #0c1c38; 
         } 
         canvas{ 
             z-index: -1; 
         } 
         .fourzerofour { 
             display: flex; 
             flex-direction: row; 
             justify-content: center; 
             align-items: center; 
         } 
  
         h1 { 
             position:relative; 
             text-align: center; 
             color: #fff; 
             font-family: "Dosis", sans-serif; 
             font-size: 100px; 
             font-weight: 800; 
             z-index: 0; 
             word-spacing: 5px; 
         } 
         h3{ 
             position:relative; 
             display: flex; 
             flex-direction: row; 
             font-size: 30px; 
             text-align: center; 
             justify-content: center; 
             color: #fff; 
             font-family: 'Dosis',sans-serif; 
         } 
         span{ 
             margin: 0 4px; 
             text-decoration: line-through; 
             text-decoration-color: yellow; 
         } 
  
         #mars { 
             height: 25%; 
             width: 25%; 
             animation: rotate 2s linear infinite; 
             z-index: 1; 
         } 
         #astronaut{ 
             position: absolute; 
             height: 25%; 
             width: 25%; 
             animation: idk 20s linear infinite; 
         } 
         @keyframes idk { 
             0%{ 
                 transform:translate(-500px,300px); 
             } 
             33%{ 
                 transform:translate(-500px,-700px); 
             } 
             66%{ 
                 transform: translate(450px,-650px) rotate(180deg); 
             } 
             100%{ 
                 transform: translate(450px,300px) rotate(180deg); 
             } 
         } 
  
         @keyframes rotate { 
             0% { 
                 transform: rotate(0deg); 
             } 
  
             100% { 
                 transform: rotate(360deg); 
             } 
         } 
     </style> 
  
 </head> 
  
 <body> 
     <canvas id="tsparticles"></canvas> 
     <h1>404</h1> 
     <h3> 
         Look like You'r lost in space, 
     </h3> 
     <h3> 
         The <span>page</span>  not found 
     </h3> 
     <div class="fourzerofour"> 
         <img src="https://tsparticles.github.io/404-templates/space/images/planet.svg" id="mars" alt="mars"> 
         <img src="https://tsparticles.github.io/404-templates/space/images/astronaut.svg" id="astronaut" alt="astronaut"> 
     </div> 
     <div class="stars"></div> 
  
 </body> 
 <script> 
     tsParticles.load("tsparticles", { 
     background: { 
       color: "#0e0d20" 
     }, 
     particles: { 
       number: { 
         value: 200, 
         density: { 
           enable: true, 
           value_area: 800 
         } 
       }, 
       color: { 
         value: "#ffffff" 
       }, 
       shape: { 
         type: "circle" 
       }, 
       opacity: { 
         value: 0.5, 
         random: true 
       }, 
       size: { 
         value: 2, 
         random: true 
       }, 
       move: { 
         enable: true, 
         speed: .1  
       } 
     }, 
     interactivity: { 
       events: { 
         onhover: { 
           enable: false 
         }, 
         onclick: { 
           enable: false 
         } 
       } 
     } 
   }); 
  
 </script> 
  
 </html>