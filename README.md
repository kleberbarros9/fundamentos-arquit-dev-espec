# Exercício de Fundamentos e Arquitetura para desenvolvimento web

## Prof.: Daniel Brandão

## Estudante: Kleber Barros

### Requisitos

- Copiar uma página da web qualquer, realizando modificações
- Realizar um pull request
- Adicionar o professor como colaborador

### Site Original


[portal g1](https://g1.globo.com/politica/blog/daniela-lima/post/2023/09/28/ex-delator-acusa-moro-no-stf-de-usa-lo-para-investigar-desembargadores-juizes-e-ministros-do-stj.ghtml#:~:text=Os%20autos%20mostram%20que%2030,ele%20envolve%20pessoas%20com%20foro.)

<p align="center">
    <img src="./src/img/site-original.png" alt="site original" height=512px>
</p>



### Site copiado



[Deploy do site copiado](https://kleberbarros9.github.io/fundamentos-arquit-dev-espec/)

<p align="center">
    <img src="./src/img/site-copia-new.png" alt="site cópia" height=512px>
</p>



###  Trechos de código do site copiado


Implementando acesso ao vídeo ao clicar na foto.

```html
        <a href="https://www.youtube.com/watch?v=acBgONy3uoc">
            <img src="./static/img/daniela.png" alt=""width="80%" height="80%">    
        </a>
```


Uso de divs, classes, estilos e acesso simulado à link imitando página original

```html

<div class="link-g1">
    <ul>
        <li><a style="color: red; 
            text-decoration: none"
            href="https://g1.globo.com/politica/blog/daniela-lima/post/2023/09/26/em-novos-votos-moraes-mostra-que-militares-ofereceram-ate-estacionamento-para-radicais.ghtml">
            Em novos votos, Moraes mostra que militares ofereceram até estacionamento para radicais</a></li>
    </ul>
</div>
```


