# Organização do MarketArt

Este arquivo registra a estrutura do projeto e a divisão atual de responsabilidades do grupo.

## Estrutura

```text
trabalho 1.0/
├── index.html
├── pages/
│   ├── cadastro.html
│   ├── carrinho.html
│   ├── configuracoes.html
│   ├── categorias.html
│   ├── pesquisa.html
│   ├── checkout.html
│   └── notificacoes.html
├── css/
│   ├── style.css
│   └── pesquisa.css
├── javascript/
│   └── script.js
├── img/
│   ├── interface/
│   ├── produtos/
│   └── perfis/
└── docs/
    └── ORGANIZACAO.md
```

## Responsabilidades

### Luiza
- `index.html` — página inicial
- `pages/cadastro.html` — cadastro / compra e venda
- `pages/carrinho.html` — carrinho
- `pages/configuracoes.html` — configurações

### Kaiser7009
- `pages/categorias.html` — categorias
- `pages/pesquisa.html` — pesquisa
- `pages/checkout.html` — finalização da compra
- `pages/notificacoes.html` — notificações

## Convenções

- HTML da página inicial permanece em `index.html`.
- Demais páginas HTML ficam em `pages/`.
- Arquivos CSS ficam em `css/`.
- JavaScript fica em `javascript/`.
- Imagens de interface, produtos e perfis ficam nas respectivas subpastas de `img/`.
- Cada integrante desenvolve prioritariamente seus próprios arquivos para reduzir conflitos.
- Funcionalidades só devem ser descritas como prontas quando estiverem realmente implementadas.

## Observação atual

A página de pesquisa já possui implementação inicial e foi apenas movida para `pages/`, com os caminhos relativos de CSS e imagens ajustados. As imagens referenciadas pela página de pesquisa ainda precisam existir no repositório para serem exibidas corretamente.
