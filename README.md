# Luanda Viva — Site Frontend

Projeto estático em HTML e CSS para promover o turismo e a cultura de Luanda.
Inclui páginas de navegação, destinos, cultura e contacto, com secções visuais ricas e layout responsivo.

## Objetivo do projeto

- Apresentar Luanda como destino turístico.
- Destacar atrações, cultura e experiências locais.
- Fornecer um canal de contacto simples e acessível.

## Páginas

- `index.html`: Entrada principal do projeto (redireciona/introduz o site).
- `home.html`: Página inicial com destaque visual e chamadas de ação.
- `destinos.html`: Lista de destinos com cartões informativos.
- `cultura.html`: Agenda cultural, destaque de património e detalhes da cultura local.
- `contacto.html`: Formulário de contacto e secção de áudio.

## Estrutura do projeto

```
Front_blog/
├── index.html
├── home.html
├── destinos.html
├── cultura.html
├── contacto.html
├── styles.css
├── css/
│   ├── animations.css
│   ├── audio-section.css
│   ├── base.css
│   ├── components.css
│   ├── destination-cards.css
│   ├── footer.css
│   ├── hero.css
│   ├── navigation.css
│   ├── reset.css
│   ├── responsive.css
│   ├── utilities.css
│   └── variables.css
├── images/
│   ├── hero-skyline.png
│   ├── ilha-de-luanda.jpg
│   ├── fortaleza-sao-miguel.jpg
│   ├── mussulo-praia.jpg
│   ├── cultura-tradicional.jpg
│   ├── fundoAudio.png
│   ├── icon.png
│   └── ...
└── Áudio/
    └── semba.mp3
```

## Como executar localmente

Este projeto é estático, não precisa de servidor.

1. Abra `index.html` no navegador.
2. Navegue pelas páginas pelo menu superior.

Opcional: se quiser um servidor local simples, use qualquer servidor estático.

## Organização de estilos

- `styles.css` é o ponto de entrada e importa todos os módulos em `css/`.
- `variables.css` define cores, fontes e espaçamentos globais.
- `base.css` e `reset.css` garantem consistência visual.
- Módulos como `hero.css`, `navigation.css`, `footer.css` controlam secções específicas.
- `responsive.css` trata o comportamento em telas menores.

## Imagens e áudio

As imagens e o áudio estão organizados nas pastas `images/` e `Áudio/`.
Se substituir imagens, mantenha os mesmos nomes para preservar os links existentes.

### Imagens principais

| Ficheiro                | Uso principal |
|-------------------------|---------------|
| `hero-skyline.png`      | Hero e Open Graph |
| `ilha-de-luanda.jpg`    | Cartão de destino |
| `fortaleza-sao-miguel.jpg` | Cartão de destino |
| `mussulo-praia.jpg`     | Cartão de destino |
| `cultura-tradicional.jpg` | Cultura / áudio |
| `fundoAudio.png`        | Secção de áudio |
| `icon.png`              | Ícone e favicon |

### Áudio

- `Áudio/semba.mp3`: trilha usada na secção “Sons de Luanda”.

## Personalização rápida

- Cores e fontes: edite `css/variables.css`.
- Conteúdo das páginas: edite os ficheiros HTML diretamente.
- Cartões de destinos: ajuste os blocos `.destination-card` em `destinos.html`.

## Notas

- O formulário de `contacto.html` é estático (sem backend).
- O layout é responsivo e funciona em mobile e desktop.
