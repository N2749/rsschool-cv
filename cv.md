# Nurbolat Davletyarov
![profile photo](./img/photo128.png "me developing")
---
## Contact information
+ email: nurbolat.dav@gmail.com
+ telegram: @n2749
+ rs school discord: Nurbolat (@n2749)
---
## About myself
I'm a second year student at the IITU university. My speciality is information systems. Here I study the masters of project management along with the Java EE stack.

I am passionate about games of any kind, except shooters (always lose), like tetris, chess, and board games.

Now learning web development, because it seemed intresting to me. I have had experiense in several educational and pet projects.

---
## Skills
+ Basics HTML5, CSS3, JavaScript, VueJS
+ Git, GitHub
+ VSCode, Intellij IDEA, WebStorm, 
---
## Projects
+ [CRUD application using Vanila JS + Sweetalert 2](https://github.com/N2749/webFinalProject)
Was responsible for JS Part. Implemented validation, storing in LS, JS animation 
+ [Simple Vue app for final test preparation, written without backend](https://github.com/N2749/vue-simple-test-app)
Contains two pages. One for creating questions, and one to pass them.
+ [Fullstack application Java + Vue](https://github.com/N2749/fis-final-2022)
Was responsible for backend, and frontend except layout and design.

---
## Code example
_Code below zoom in image when it is being focused and zoom out of it otherwise._
```
const bigImg = document.getElementById("bigImage");
const originSrc = bigImg.getAttribute("src");
const box = document.getElementById("container");

box.onmouseover = (event) => {
    let img = event.target.closest("img");
    if (!img) return;
    if (!box.contains(img)) return;
    let newSource = event.target.getAttribute("src");
    bigImg.setAttribute("src", newSource);
};
box.onmouseout = (event) => {
    bigImg.setAttribute("src", originSrc);
};
```
---
## Education
1. №10 school, Almaty 2020.
2. IITU 2020-2024.
    + [Introduction to Web Development (courcera)](https://coursera.org/share/4e0434da15c5767a314414d220bb7dfb)
    + [Linux and git (courcera)](https://coursera.org/share/7902fd00559bc9fdae2416ddbc052bff)
---
## Languages
+ russian: fluent
+ english: upper intermediate