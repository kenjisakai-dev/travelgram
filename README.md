# 📸 Travelgram

Um perfil de viagem responsivo inspirado no Instagram, criado para mostrar fotos e experiências de viagem da Isabela Torres.

🌐 **[Ver o site ao vivo](https://kenjisakai-dev.github.io/travelgram/)**

## 🌟 Sobre o Projeto

O Travalgram é uma página web que simula um perfil de rede social focado em viagens, apresentando:

- **Perfil pessoal** com foto, biografia e estatísticas de viagem
- **Galeria de fotos** com imagens de destinos ao redor do mundo
- **Design responsivo** que se adapta a diferentes tamanhos de tela
- **Interface limpa** e moderna inspirada nas redes sociais

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e layout
- **Google Fonts** - Tipografia (Poppins)

## 🎨 Recursos de CSS

### Flexbox

- Utilizado para layout do header, navegação e elementos do perfil
- Classes utilitárias como `.flex`, `.items-center`, `.gap-1`
- Responsivo com `flex-direction` que muda de column para row em telas maiores

### CSS Grid

- Implementado na galeria de fotos para organização das imagens
- Layout responsivo: 1 coluna no mobile, 4 colunas no desktop
- Grid automático que se adapta ao conteúdo

### Responsividade

- **Mobile First**: Desenvolvido primeiro para dispositivos móveis
- **Breakpoint**: `@media (width >= 1280px)` para telas desktop
- **Elementos adaptativos**:
  - Menu mobile vs desktop
  - Layout de colunas no perfil
  - Grid de fotos responsivo

## 📱 Características Responsivas

### Mobile (< 1280px)

- Layout em coluna única
- Menu simplificado apenas com ícones
- Grid de fotos em uma coluna
- Perfil em formato vertical

### Desktop (≥ 1280px)

- Layout em colunas
- Menu completo com texto
- Grid de fotos em 4 colunas
- Perfil em formato horizontal

## 🗂️ Estrutura de Arquivos

```
travalgram/
├── index.html             # Página principal
├── assets/
│   ├── icons/             # Ícones SVG
│   └── images/            # Fotos da galeria
└── styles/
    ├── index.css          # Arquivo principal de estilos
    ├── global.css         # Estilos globais e reset
    ├── utilities.css      # Classes utilitárias
    ├── header.css         # Estilos do cabeçalho
    ├── profile.css        # Estilos da seção perfil
    ├── photo.css          # Estilos da galeria
    └── footer.css         # Estilos do rodapé
```

## 🎯 Funcionalidades

- ✅ Design responsivo para mobile e desktop
- ✅ Galeria de fotos organizada com Grid
- ✅ Navegação intuitiva com Flexbox
- ✅ Perfil completo com estatísticas de viagem
- ✅ Otimização de fontes com Google Fonts
- ✅ Textos alternativos (alt) em todas as imagens para acessibilidade

## 🚀 Como Executar

1. Clone ou baixe o projeto
2. Abra o arquivo `index.html` em seu navegador
3. Redimensione a janela para testar a responsividade

## 👨‍💻 Desenvolvedor

Projeto desenvolvido com foco em:

- Boas práticas de HTML semântico
- CSS moderno com Flexbox e Grid
- Design responsivo mobile-first
- Acessibilidade web

---

_"Explorando cantinhos fascinantes do nosso planeta"_ 🌍✈️
