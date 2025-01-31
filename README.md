# 👨🏻‍💻 Pedro Teixeira

**`Desenvolvedor front-end`**

Meu nome é Pedro Teixeira, tenho 25 anos, atualmente moro no Oeste do Paraná. Sou apaixonado por tecnologia e estou constantemente em busca de aprendizado e evolução nesse mundo dinâmico que é a programação. Atualmente, estou cursando Engenharia de Software, aprimorando meus conhecimentos para contribuir com a comunidade.


### 🤖 Linguagens e Tecnologias
<img align="left" alt="HTML" title="HTML" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg"/>
<img align="left" alt="CSS" title="CSS" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg"/>
<img align="left" alt="JavaScript" title="JavaScript" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg"/>

<br/>
<br/>

### 📊 Estatísticas

<p>
  <img align="left" alt="GitHub Stats" height="177" style="padding-right: 10px;" src="https://github-readme-stats.vercel.app/api?username=xpedrotx&show_icons=true&theme=tokyonight&include_all_commits=true&locale=pt-br"/>
  <img align="left" alt="GitHub Stats" height="177" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xpedrotx&theme=tokyonight&layout=compact&custom_title=Tecnologias&langs_count=9"/>
</p>

<!-- Efeito de digitação -->
<script>
    document.addEventListener("DOMContentLoaded", function() {
        const textArray = ["Pedro Teixeira", "Desenvolvedor Web", "Criador de Conteúdo"];
        let index = 0;
        let charIndex = 0;
        let typingElement = document.getElementById("typing");
        let isDeleting = false;

        function type() {
            let currentText = textArray[index];
            if (isDeleting) {
                typingElement.innerHTML = currentText.substring(0, charIndex--);
            } else {
                typingElement.innerHTML = currentText.substring(0, charIndex++);
            }

            if (!isDeleting && charIndex === currentText.length + 1) {
                isDeleting = true;
                setTimeout(type, 1000);
            } else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                index = (index + 1) % textArray.length;
                setTimeout(type, 500);
            } else {
                setTimeout(type, isDeleting ? 50 : 100);
            }
        }

        type();
    });
</script>
