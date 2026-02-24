# MetaAula
Recursos educacionais para promover metacognição, resiliência acadêmica e gerenciamento de trauma educacional. Framework para professores universitários ajudarem estudantes a desenvolver estratégias de aprendizado sustentáveis em um contexto meta-pós-moderno.

## Sobre este Projeto

Este repositório contém materiais para uma aula introdutória universitária que desconstrói o mito do "aluno perfeito" e oferece estratégias metacognitivas para o sucesso acadêmico. Desenvolvida inicialmente para a UERJ (Universidade do Estado do Rio de Janeiro), mas aplicável a qualquer contexto de ensino superior, esta apresentação aborda os desafios contemporâneos enfrentados pelos estudantes utilizando uma perspectiva meta-pós-moderna.

### Objetivos Educacionais

- Desmistificar expectativas irrealistas sobre a vida acadêmica
- Apresentar ferramentas metacognitivas para melhorar o aprendizado
- Abordar o trauma acadêmico e estratégias de superação
- Discutir a importância da perseverança diante de desafios
- Refletir sobre o uso estratégico da tecnologia no contexto educacional

## Conteúdo do Repositório

### [Apresentação Principal](https://oangelo.github.io/MetaAula/)

- `index.html` - Arquivo principal (carrega as seções dinamicamente via fetch)
- `/sections` - Cada seção da apresentação em seu próprio arquivo HTML:
  - `01-abertura.html` — Bem-vindos à Aula Perfeita™
  - `02-filosofia.html` — Evolução do Pensamento Educacional
  - `03-tecnologia-ia.html` — Dimensão Tecnológica: IA na Educação
  - `04-trauma-academico.html` — O Trauma Acadêmico
  - `05-recursos-fundamentais.html` — Tempo, Sono e Metacognição
  - `06-ferramentas-mudanca.html` — Ferramentas para Mudar
  - `07-ambiente-grupo.html` — Você, Seu Ambiente e Seu Grupo
  - `08-perseveranca.html` — Estratégias Práticas de Perseverança
  - `09-consolidacao.html` — Consolidação e Compromisso
- `/dist` - Arquivos do framework reveal.js
- `/plugin` - Plugins do reveal.js
- `/img` - Imagens utilizadas na apresentação

### Materiais Complementares

- `planilha-tempo-semanal.html` - Ferramenta de planejamento semanal para estudantes (formato A4)
- `/recursos` - Referências bibliográficas e ferramentas de estudo complementares
- [`roteiro.md`](roteiro.md) - Roteiro narrativo completo da apresentação (guia de conteúdo)
## Como Utilizar

### Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Para modificações: conhecimentos básicos de HTML e CSS

### Visualizando a Apresentação

1. Clone o repositório:

```bash
git clone https://github.com/oangelo/MetaAula.git
cd MetaAula
```

2. Inicie um servidor HTTP local (necessário porque as seções são carregadas via fetch):

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

3. Acesse `http://localhost:8000` no navegador.

4. Use as setas do teclado para navegar entre os slides.

> **Nota:** A apresentação também está disponível online via GitHub Pages em [oangelo.github.io/MetaAula](https://oangelo.github.io/MetaAula/), sem necessidade de servidor local.

### Adaptando para Seu Contexto

A apresentação foi projetada para ser facilmente adaptável:

1. Modifique a seção "Contextualização Institucional" com dados específicos da sua instituição
2. Atualize as estatísticas para refletir realidades locais 
3. Adicione exemplos relevantes para seus estudantes e disciplina

## Filosofia Educacional

Esta apresentação é fundamentada numa abordagem meta-pós-moderna da educação, reconhecendo que:

- O conhecimento é construído coletivamente e está em constante evolução
- A jornada de aprendizado não é linear, mas repleta de altos e baixos
- As experiências educacionais anteriores influenciam profundamente a capacidade atual de aprendizado
- A metacognição (pensar sobre como pensamos e aprendemos) é uma habilidade fundamental

## Contribuições

Contribuições são bem-vindas! Se você utilizou esta apresentação e fez adaptações ou melhorias, considere:

1. Abrir um pull request com suas alterações
2. Compartilhar feedback sobre a experiência de uso
3. Sugerir novos recursos ou abordagens

---

> "O que define seu sucesso acadêmico não é sua primeira nota, mas sua resposta a ela."
