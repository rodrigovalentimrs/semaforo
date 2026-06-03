# Semáforo Interativo

Simulação de um semáforo funcional desenvolvida com HTML, CSS e JavaScript puro.

## Sobre o Projeto

Um semáforo que alterna automaticamente entre as cores vermelha, amarela e verde, com a possibilidade de controle manual pelo usuário. O projeto explora manipulação do DOM, eventos, intervalos de tempo e organização de código com objetos.

## Funcionalidades

- **Modo automático:** o semáforo troca de cor a cada 1 segundo automaticamente ao carregar a página
- **Controle manual:** botões para acionar cada cor individualmente, pausando o modo automático
- **Troca de imagens dinâmica:** cada estado do semáforo é representado por uma imagem própria

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)

## Estrutura do Projeto

```
semaforo/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── img/
    ├── verde.png
    ├── vermelho.png
    ├── amarelo.png
    └── desligado.png
```

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/semaforo.git
   ```
2. Abra o arquivo `index.html` no navegador.

Não há dependências externas — basta abrir no browser!

## Conceitos Praticados

- Manipulação do DOM com `getElementById`
- `setInterval` e `clearInterval` para controle de tempo
- Objetos JavaScript como mapa de funções (`turnOn`)
- Separação de responsabilidades entre HTML, CSS e JS
- Lógica de índice circular para alternância de estados

