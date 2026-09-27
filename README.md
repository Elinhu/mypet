# mypet

Landing page de uma campanha de vacinação de pets, conscientizando sobre a importância da vacina e reunindo informações de cronograma, veterinários parceiros e uma ficha de inscrição.

Este projeto é uma remasterização do **My-pet_Vacinas**, criado originalmente em 2021. A ideia aqui não é reinventar o projeto, e sim seguir o esqueleto e o conteúdo que já existiam, corrigindo o código e atualizando o design.

## Status

Em andamento. O `index.html` atualmente cobre:

- [x] Header / Navegação
- [x] Hero
- [ ] Sobre
- [ ] Cronograma
- [ ] Veterinários
- [ ] Testemunhos
- [ ] Dúvidas (FAQ)

As seções marcadas como pendentes ainda não foram escritas no HTML, mesmo já tendo estilos previstos no CSS.

## Stack

HTML, CSS e JavaScript puros — sem framework e sem etapa de build. Basta abrir o `index.html` no navegador (ou servir a pasta com qualquer servidor estático) para visualizar.

## Estrutura de pastas

```
mypet/
├── index.html
├── ficha.html
├── 404.html
├── assets/
│   ├── css/
│   │   ├── global.css   # reset, tokens e componentes base
│   │   └── style.css    # estilos específicos de cada seção
│   ├── js/
│   │   └── script.js
│   └── img/
│       ├── icons/       # ícones de UI e logo
│       └── img          # imagens do projeto
└── docs/                # material de referência (Figma, briefing, style guide)
```

## Design

- Sistema de cor monocromático, gerado a partir de uma cor base em [uiColors](https://uicolors.app/), usando os valores pares da escala.
- Tipografia: **Outfit**, e **DM Sans** seguindo a escala padrão do Figma.
- Botões com tamanho único fixo.

## Notas

Projeto em remaster contínuo — partes do código e do conteúdo original de 2021 ainda estão sendo revisadas aos poucos.
