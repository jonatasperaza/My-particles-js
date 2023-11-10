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
particlesJS('particles-js',
  
  {
    "particles": {
      "number": {
        "value": 80,
        "density": {
          "enable": true,
          "value_area": 800
        }
      },
      "color": {
        "value": "#ffffff"
      },
      "shape": {
        "type": "circle",
        "stroke": {
          "width": 0,
          "color": "#000000"
        },
        "polygon": {
          "nb_sides": 5
        },
      },
    },
    "interactivity": {
      "detect_on": "canvas",
      "events": {
        "onhover": {
          "enable": true,
          "mode": "repulse"
        },
        "onclick": {
          "enable": true,
          "mode": "push"
        },
        "resize": true
      },
      "modes": {
        "grab": {
          "distance": 400,
          "line_linked": {
            "opacity": 1
          }
        },
        "bubble": {
          "distance": 400,
          "size": 40,
          "duration": 2,
          "opacity": 8,
          "speed": 3
        },
        "repulse": {
          "distance": 200,
          "duration": 0.4
        },
        "push": {
          "particles_nb": 4
        },
        "remove": {
          "particles_nb": 2
        }
      }
    },
    "retina_detect": true
  }

);
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
