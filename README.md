<h1>Animação de carregamento simples</h1>

Implementação css de carregamento

<div>
  <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</div>

[![GitHub Version](https://img.shields.io/github/release/pommering/animation-load?style=for-the-badge)](https://github.com/animate-css/animate.css/releases)
[![Github Star](https://img.shields.io/github/stars/pommering/animation-load?style=for-the-badge)](https://github.com/animate-css/animate.css/stargazers)
[![Github Fork](https://img.shields.io/github/forks/pommering/animation-load?style=for-the-badge)](https://github.com/animate-css/animate.css/network/members)

## Usar
Inclua o código abaixo no css e seja feliz 😄

```css
@keyframes rotate { 
    100% {
        -webkit-transform: rotate(360deg);
        transform: rotate(360deg);
    }
}
```

É apenas incluir a animação no elemento assim:

```css
img {
    animation: rotate 4s linear infinite;
}
```
Aceito em todas as tags

```css
svg {
    animation: rotate 4s linear infinite;
}

div {
    animation: rotate 4s linear infinite;
}
```

## Licença 📃

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
