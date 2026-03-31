# Chronos Pomodoro 🍅

Projeto desenvolvido como parte das práticas 01 a 20 da disciplina de Frontend do IESB Oeste.

## 🛠️ Tecnologias

- React 19
- TypeScript
- Vite
- CSS Modules
- Lucide React (ícones)

## 🎨 Personalizações realizadas

Este projeto segue a estrutura e lógica do repositório do professor, com as seguintes alterações visuais:

### Paleta de cores
- Substituição da cor primária **verde** (`#0da170`) por **violeta/roxo** (`#7c3aed`)
- Toda a escala de cinzas foi reajustada para tons com leve matiz arroxeado
- Variáveis de cor como `--primary`, `--primary-light`, `--primary-dark` foram recalibradas

### Tipografia
- Adicionada a fonte **Orbitron** (Google Fonts) para elementos de display: logo, timer e headings
- Adicionada a fonte **Nunito** para o corpo do texto — mais legível e amigável
- Substituição da `system-ui` padrão do original

### Outros detalhes visuais
- Fundo com `radial-gradient` sutil partindo do topo para dar profundidade
- Botões com `linear-gradient` e `box-shadow` roxa
- Timer (`CountDown`) com `text-shadow` luminoso
- Links do `Footer` com transição de cor ao hover
- `MenuLink` com leve `transform: translateY` ao hover
- Emoji 💜 no footer em vez de 💚

## 🚀 Como rodar

```bash
npm install
npm run dev
```

## 📁 Estrutura de componentes

```
src/
├── styles/
│   ├── theme.css       # variáveis CSS personalizadas
│   └── global.css      # reset e estilos globais
├── components/
│   ├── Container/      # wrapper de layout centralizado
│   ├── Logo/           # logo com ícone TimerIcon
│   ├── Menu/           # navegação com ícones
│   ├── CountDown/      # display do timer
│   ├── Cycles/         # pontos indicadores de ciclos
│   ├── DefaultInput/   # input reutilizável com label
│   ├── DefaultButton/  # botão reutilizável com ícone
│   ├── Heading/        # título tipográfico
│   └── Footer/         # rodapé com links
└── App.tsx             # composição principal
```
