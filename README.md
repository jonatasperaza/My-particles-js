<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=e83d84&height=120&section=header"/>
<div>
# Tutorial Particles.js

Este é um tutorial básico sobre como usar a biblioteca particles.js em seu projeto.

## Passo 1: Incluir a biblioteca particles.js

Primeiro, você precisa incluir a biblioteca particles.js em seu projeto. Você pode fazer isso adicionando o seguinte script em seu arquivo HTML:

```html
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
```
## Passo 2: Criar um div

Em seguida, você precisa criar um div em seu arquivo HTML onde você deseja que as partículas apareçam. Por exemplo:

```html
<div id="particles-js"></div>
```
## Passo 3: Configurar as opções de parâmetros da biblioteca

```js
particlesJS("particles-js", {

    particles: {
        number: {
            value: 15,
            density: {
                enable: true,
                value_area: 300,
            },
        },

        color: {
            value: "#ffffff",
        },
        shape: {
            type: "triangle",
        },
        opacity: {
            value: 0.8,
            random: true,
            anum: {
                enable: true,
                speed: 1,
                opacity_min: 0.1,
                sync: false,
            },
        },
        size: {
            value: 5,
            random: true,
            anim: {
                enable: true,
                speed: 4,
                size_min: 0.3,
                sync: false,
            },
        },

        line_linked: {
            enable: true,
            distance: 150,
            color: "#ffffff",
            opacity: 0.4,
            width: 1,
        },

        move: {
            enable: true,
            speed: 2,
            direction: "none",
            random: false,
            straight: false,
            out_mode: "bounce",
            bounce: false,
        },
    },
    interactivity: {
        detect_on: "canvas",
        events: {
            onhover: {
                enable: true,
                mode: "repulse",
            },
            onclick: {
                enable: true,
                mode: "push",
            },
            resize: true,
        },
    },

    retina_detect: true,

});
```
## Passo 4 Estilizar o div

Finalmente, você precisa estilizar o div que você criou para que as partículas ocupem toda a tela. Você pode fazer isso adicionando o seguinte CSS em seu arquivo CSS:

```css
#particles-js {
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: #b61924;
  background-image: url("");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
}
```
</div>

<img style="margin-top:10px" width=100% src="https://capsule-render.vercel.app/api?type=waving&color=e83d84&height=120&section=footer"/>
