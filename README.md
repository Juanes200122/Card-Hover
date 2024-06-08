# Card-Hover⭐⭐⭐⭐☆

![Banner](image/cap-counter.PNG)
<p align="center" style="color: white;">
    <img src="https://profile-counter.glitch.me/Juanes200122/count.svg" />
</p>


<p>
    <a href="https://www.linkedin.com/in/juan-estaban-ar%C3%A9valo-056bab240/" target="_blank" rel="Linkedin">
      <img src="https://img.shields.io/badge/-@JuanEsteban-0077B5?style=flat-square&amp;labelColor=0077B5&amp;logo=LinkedIn&amp;link=https://www.linkedin.com/in/juan-estaban-ar%C3%A9valo-056bab240/" alt="LinkedIn Badge">
    </a> 
    <a href="https://www.instagram.com/jeacsi.official_022?igsh=MWJ6MHRwcnhoZXVxbQ==" target="_blank" rel="Instagram">
      <img src="https://img.shields.io/badge/-@jeacsi.official_022-purple?style=flat&logo=instagram&logoColor=white&link=https://www.instagram.com/jeacsi.official_022?igsh=MWJ6MHRwcnhoZXVxbQ==" alt="Instagram Badge">
    </a>
</p>
<p>Se ha desarrollado una animación de tarjetas que se ilumina al hacer hover sobre ellas, utilizando JavaScript puro. Esta animación detecta la posición del cursor y aplica un efecto de iluminación gradual en el área debajo del mismo, creando una experiencia visual interactiva y dinámica.</p>

<p>Visualizar trabajo en 
    <a href="https://codepen.io/Juan-Esteban-Ar-valo/pen/rNgMrOP" target="_blank">
        <img src="https://img.shields.io/badge/-CodePen-000000?style=flat&logo=codepen" alt="CodePen">
    </a>
</p>


```bash
    git clone https://github.com/Juanes200122/Card-Hover.git
    cd Card-Hover
```
<div align="right">
    
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
![CodePen](https://img.shields.io/badge/-CodePen-000000?style=flat&logo=codepen)

</div>

## <b> Funcionalidad</b>
<img align="right" src="image/cap-countainer.gif" width="400"/>

```JS
    let cards = document.querySelectorAll(".card");
    
    cards.forEach(card => {
        card.onmousemove = function(e){
            let x = e.pageX - card.offsetLeft;
            let y = e.pageY - card.offsetTop;
    
            card.style.setProperty('--x', x + 'px');
            card.style.setProperty('--y', y + 'px');
        }
    })
```

</br>

## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width ="25"><b> Skills</b>
  - 💻 &nbsp;
    ![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)
  - 🌐 &nbsp;
    ![HTML5](https://img.shields.io/badge/-HTML5-333333?style=flat&logo=HTML5)
    ![CSS](https://img.shields.io/badge/-CSS-333333?style=flat&logo=CSS3&logoColor=1572B6)
