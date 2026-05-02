---
name: Duty & Discipline
colors:
  surface: '#fff8f7'
  surface-dim: '#f0d4d0'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ef'
  surface-container: '#ffe9e6'
  surface-container-high: '#ffe2de'
  surface-container-highest: '#f9dcd9'
  on-surface: '#271816'
  on-surface-variant: '#5b403d'
  inverse-surface: '#3e2c2a'
  inverse-on-surface: '#ffedea'
  outline: '#8f706c'
  outline-variant: '#e4beba'
  surface-tint: '#b91d20'
  primary: '#a20513'
  on-primary: '#ffffff'
  primary-container: '#c62828'
  on-primary-container: '#ffe0dd'
  inverse-primary: '#ffb4ac'
  secondary: '#8b5000'
  on-secondary: '#ffffff'
  secondary-container: '#ff9800'
  on-secondary-container: '#653900'
  tertiary: '#00557a'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e9d'
  on-tertiary-container: '#d1eaff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#93000e'
  secondary-fixed: '#ffdcbe'
  secondary-fixed-dim: '#ffb870'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#693c00'
  tertiary-fixed: '#c8e6ff'
  tertiary-fixed-dim: '#88ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#fff8f7'
  on-background: '#271816'
  surface-variant: '#f9dcd9'
typography:
  h1:
    fontFamily: Work Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Work Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  h3:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  container-max: 1200px
---

## Brand & Style

O sistema de design foi concebido para projetar autoridade técnica e confiabilidade humanitária. A narrativa visual equilibra o rigor institucional de uma força de emergência com a acessibilidade de um portfólio profissional.

O estilo adotado é o **Corporate / Modern**, utilizando uma estética limpa e funcional que prioriza a legibilidade e a hierarquia de informações. A interface evita ornamentos desnecessários, focando em estruturas sólidas que transmitem a prontidão e a estabilidade inerentes à profissão de bombeiro. O objetivo emocional é inspirar confiança tanto em recrutadores quanto na comunidade, apresentando o profissional como um pilar de segurança e competência técnica.

## Colors

A paleta é fundamentada no "Vermelho Operacional", uma cor de alta visibilidade que sinaliza urgência e comando. O "Laranja de Alerta" é utilizado estrategicamente para chamadas de ação e elementos de destaque secundários, garantindo uma conexão visual imediata com equipamentos de segurança.

O uso do Cinza Escuro (#212121) para textos e superfícies de contraste oferece a sobriedade necessária para equilibrar as cores vibrantes. O Branco puro é a base da interface, garantindo o respiro visual e a estética moderna e "clean" solicitada.

## Typography

Para os títulos, utilizamos o **Work Sans**. Sua estrutura robusta e geométrica confere um tom de voz direto e autoritário, facilitando a leitura rápida de conquistas e qualificações.

Para o corpo de texto, o **Inter** foi selecionado por sua neutralidade e excelência técnica em telas. Sua legibilidade superior garante que relatórios de incidentes, certificações e descrições detalhadas sejam consumidos sem fadiga visual. O uso de etiquetas em caixa alta (labels) reforça a natureza institucional da documentação de um profissional de segurança pública.

## Layout & Spacing

Este design system utiliza um **Fixed Grid** de 12 colunas para desktops, centralizado em um container de 1200px, transicionando para um layout fluido em dispositivos móveis. O ritmo espacial é baseado em um sistema de grade de 8px, garantindo consistência matemática entre todos os componentes.

O espaçamento é generoso (48px a 80px entre seções) para manter a clareza e o foco, evitando a sensação de desordem ou caos — o oposto do que se espera de um ambiente controlado por um profissional de emergência.

## Elevation & Depth

A hierarquia visual é estabelecida através de **Tonal Layers** e **Low-contrast outlines**. Em vez de sombras pesadas e dramáticas, utilizamos bordas finas (1px) em cinza claro para delimitar áreas de conteúdo sobre o fundo branco.

Para elementos que exigem interação, como cartões de projetos ou certificados, aplica-se uma sombra de ambiente extremamente difusa (Y: 4px, Blur: 12px, Opacidade: 5% de preto) para sugerir elevação sem comprometer a sobriedade do design. O foco deve ser a estrutura, não o efeito visual.

## Shapes

O sistema de formas adota o nível **Soft** (4px / 0.25rem). Esta escolha é estratégica: cantos vivos (0px) podem parecer excessivamente agressivos ou datados, enquanto cantos muito arredondados (Pill-shaped) transmitem uma informalidade lúdica inadequada para o setor de segurança.

O arredondamento sutil comunica modernidade e precisão técnica, mantendo a seriedade do portfólio.

## Components

### Buttons
Os botões primários utilizam o Vermelho (#C62828) com texto em branco e peso semibold. O estado de hover deve escurecer levemente a cor de fundo. Os botões secundários utilizam bordas em cinza escuro com fundo transparente, focando na discrição.

### Cards
Utilizados para exibir experiências profissionais e certificações. Devem ter um fundo branco, borda sutil de 1px e padding interno de 24px. Ícones de segurança (hidrantes, capacetes) devem ser posicionados no canto superior esquerdo para categorização rápida.

### Chips & Badges
Para sinalizar competências (ex: "APH", "Salvamento em Altura", "Combate a Incêndio"). Devem usar o Laranja (#FF9800) com baixa opacidade de fundo (10%) e texto na cor total para garantir legibilidade e destaque sem competir com o botão principal.

### Input Fields
Campos de formulário de contato devem ser minimalistas, com bordas inferiores acentuadas ou contornos finos, utilizando o Inter para o texto digitado. O foco do campo deve ser indicado pelo Vermelho primário.

### Icons
A iconografia deve ser de peso médio, linear e técnica. Ícones específicos de segurança devem ser usados para guiar o usuário pelas seções de especialidades, sempre acompanhados de rótulos claros em português.