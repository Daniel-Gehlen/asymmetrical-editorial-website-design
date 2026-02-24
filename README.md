# DESIGN ASSIMÉTRICO / EDITORIAL

---

# 🎨 Assymetric - Design Assimétrico / Editorial

![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![CSS Shapes](https://img.shields.io/badge/CSS_Shapes-advanced-ff69b4)
![Responsivo](https://img.shields.io/badge/responsivo-sim-success)

## 📋 Sobre o Projeto

Este é um protótipo funcional de um site com **Design Assimétrico / Editorial**, desenvolvido a partir de um diagrama ASCII art. O projeto demonstra um layout que quebra a simetria tradicional, com elementos sobrepostos e tipografia como destaque principal, típico de revistas digitais, sites de moda e estúdios criativos.

### 🎯 Características do Design

- Layout assimétrico e não-linear
- Tipografia expressiva como protagonista (título de 120px)
- Elementos sobrepostos e rotacionados
- Imagens com formatos não convencionais (poligonais)
- Texto fluindo ao redor de elementos com shape-outside
- Citações em destaque com aspas decorativas
- Hierarquia visual dinâmica

## 🏗️ Estrutura do Site

```
+--------------------------------------------------+
|                    TÍTULO GRANDE                  |
|                EM DESTAQUE                        |
+------------------------+-------------------------+
|                        |                         |
|   [IMAGEM GRANDE]      |  TEXTO SOBREPOSTO      |
|                        |  COM ESTILO             |
|                        |                         |
+------------------------+-------------------------+
|     +----+                                        |
|     |    |  Texto flui ao redor                   |
|     +----+  da imagem em formato                   |
|            diferente                              |
|                                                   |
|  +----------+  +----------+                       |
|  | Citação  |  | Imagem   |                       |
|  | em       |  | pequena  |                       |
|  | destaque |  |          |                       |
|  +----------+  +----------+                       |
+--------------------------------------------------+
```

## ✨ Funcionalidades Implementadas

### Cabeçalho Editorial

- ✅ Título "ASSYMETRIC MAGAZINE" com letter-spacing
- ✅ Edição e data (VOL. 24 — FEBRUARY 2026)
- ✅ Design minimalista e elegante

### Título Grande em Destaque

- ✅ Tipografia massiva de **120px** (ASSYMETRIC)
- ✅ Subtítulo de **60px** em itálico vermelho
- ✅ Letter-spacing negativo para impacto visual
- ✅ Alinhamento assimétrico com padding-left

### Área Principal Assimétrica

- ✅ **Imagem grande** (📷) com gradiente vermelho-laranja
- ✅ Moldura dupla com bordas internas
- ✅ **Texto sobreposto** em card flutuante
- ✅ Sombra deslocada (-10px, 10px) para efeito assimétrico
- ✅ Título com span em itálico
- ✅ Link "Leia mais" com underline animado

### Seção com Texto Flutuante


- ✅ **Imagem poligonal** com `clip-path: polygon(0 0, 100% 0, 85% 100%, 0% 100%)`
- ✅ `shape-outside` para texto fluir ao redor do formato
- ✅ **Letra capitular** de 70px no primeiro parágrafo
- ✅ 3 parágrafos com texto editorial sobre design assimétrico

### Cards Laterais Assimétricos

- ✅ **Citação em destaque** com rotação de -1 grau
- ✅ Aspas grandes (60px) como elemento decorativo
- ✅ Borda lateral vermelha de 5px
- ✅ Sombra deslocada (8px, 8px) mantendo assimetria
- ✅ **Imagem pequena** com rotação de +1 grau
- ✅ Tag "MODA" com fundo semitransparente

### Elementos Inferiores

- ✅ Texto em **2 colunas** com CSS columns
- ✅ Coluna-rule de 1px entre colunas
- ✅ Título com `column-span: all` atravessando colunas
- ✅ **Mini-galeria** com 4 imagens
- ✅ Thumbnails com sombras deslocadas (3px, 3px)
- ✅ Efeito hover nas miniaturas

### Rodapé Editorial

- ✅ Copyright da revista
- ✅ Links: SOBRE, ARQUIVO, NEWSLETTER, CONTATO
- ✅ Design escuro com links em laranja
- ✅ Hover nos links muda para branco

### Interatividade

- ✅ Todos elementos clicáveis com alertas
- ✅ Efeito scale(1.02) no hover de imagens
- ✅ Transições suaves em todos elementos interativos

## 🎨 Paleta de Cores

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| Vermelho Coral | `#ff6b6b` | Destaques, acentos, bordas |
| Laranja Suave | `#ff9f7c` | Gradientes, hover |
| Preto | `#1a1a1a` | Fundo do ASCII, textos principais |
| Cinza Escuro | `#444444` | Texto corrido |
| Cinza Claro | `#fafafa` | Fundo de citações |
| Turquesa | `#4ecdc4` | Imagem flutuante |
| Azul Claro | `#45b7d1` | Gradiente secundário |
| Verde Água | `#a8e6cf` | Imagem pequena |

## 📱 Responsividade

O layout assimétrico se adapta mantendo a essência:

- **Desktop (1200px+):** Layout completo com assimetria
- **Tablet:** Ajustes de tamanhos e espaçamentos
- **Mobile (< 768px):**
  - Título reduz para 60px (principal) e 30px (subtítulo)
  - Seções empilhadas verticalmente
  - Imagem flutuante menor (100px × 150px)
  - Texto em coluna única
  - Cards laterais abaixo do texto

## 🔗 Links e Navegação

Todos os elementos interativos são clicáveis com feedback visual:

| Elemento | Ação (alerta) |
|----------|---------------|
| Imagem grande | "Imagem grande clicada - abrir galeria" |
| Link "Leia mais" | "Artigo completo (demonstração)" |
| Imagem flutuante | "Imagem flutuante clicada" |
| Citação | "Citação em destaque: Design Thinking" |
| Imagem pequena | "Galeria de moda - edição de fevereiro" |
| Mini-galeria (4) | "Imagem X - Coleção/Editorial" |
| Links rodapé | "Sobre/Arquivo/Newsletter/Contato" |

## 🚀 Como Executar

1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Explore o layout assimétrico e as interações
4. Redimensione a janela para ver a responsividade

## 💻 Tecnologias Utilizadas

- **HTML5 semântico** - Estrutura editorial clara
- **CSS3 Avançado:**
  - `shape-outside` e `clip-path` para formatos não retangulares
  - `float` com shape-outside para texto contornar imagem
  - `columns` para layout em múltiplas colunas
  - `transform: rotate()` para assimetria nos cards
  - `::first-letter` para letra capitular de 70px
  - `::before` para aspas decorativas
  - Sombras deslocadas para efeito assimétrico
  - Gradientes lineares nas imagens
  - Transitions para interações suaves
- **JavaScript mínimo** - Efeitos de hover scale
- **Design responsivo** - Media queries estratégicas
- **Tipografia expressiva** - Georgia, Times New Roman

## 📊 Técnicas Específicas Implementadas

| Técnica | Aplicação | Código |
|---------|-----------|--------|
| Shape Outside | Texto flui ao redor da imagem | `shape-outside: polygon(...)` |
| Clip Path | Formato poligonal na imagem | `clip-path: polygon(...)` |
| Letra Capitular | Primeira letra em destaque | `::first-letter { font-size: 70px; float: left; }` |
| Colunas CSS | Texto em 2 colunas | `columns: 2; column-gap: 40px;` |
| Rotação | Cards assimétricos | `transform: rotate(-1deg);` |
| Sobreposição | Card flutuante | `margin-top: 50px; box-shadow: -10px 10px 0...` |
| Drop Shadow | Sombras deslocadas | `box-shadow: 15px 15px 30px rgba(...)` |

## 📌 Casos de Uso

Este template é ideal para:

- **Revistas digitais** - Conteúdo editorial com personalidade
- **Sites de moda** - Estética sofisticada e vanguardista
- **Estúdios criativos** - Portfólios autorais e experimentais
- **Blogs de design** - Conteúdo visual com hierarquia
- **Publicações de arte** - Experimentação tipográfica
- **Agências de publicidade** - Cases criativos
- **Editoras** - Apresentação de livros e autores

## 🧩 Diferenciais do Projeto

- ✅ **Assimetria real** - Não apenas grid quebrado, mas sobreposições e rotações
- ✅ **Tipografia como protagonista** - Título de 120px com subtítulo contrastante
- ✅ **Imagem com formato personalizado** - Polygon clipping com shape-outside
- ✅ **Elementos sobrepostos** - Card flutuante com margem negativa visual
- ✅ **Citação estilizada** - Aspas decorativas de 60px e rotação sutil
- ✅ **Multi-colunas verdadeiras** - Layout editorial com column-span
- ✅ **ASCII art demonstrativo** no topo da página
- ✅ **Todos elementos clicáveis** com feedback visual e auditivo (alertas)

## 🧪 Validação do ASCII Art

| Elemento ASCII | Implementação |
|----------------|---------------|
| TÍTULO GRANDE EM DESTAQUE | ✅ Hero title 120px/60px |
| [IMAGEM GRANDE] | ✅ Large image com 📷 |
| TEXTO SOBREPOSTO COM ESTILO | ✅ Overlay text card |
| Texto flui ao redor da imagem | ✅ Floating image com shape-outside |
| Citação em destaque | ✅ Quote card rotacionado |
| Imagem pequena | ✅ Small image card |

## 👨‍💻 Autor

Desenvolvido como demonstração de design assimétrico/editorial baseado em diagrama ASCII art por Daniel Gehlen.

---

## 📝 Notas de Versão

### v1.0.0 (24/02/2026)

- ✅ Implementação completa do design ASCII art
- ✅ Tipografia massiva de 120px em destaque
- ✅ Imagem com shape-outside e clip-path funcionais
- ✅ Cards assimétricos com rotação (-1deg e +1deg)
- ✅ Texto em 2 colunas com column-span
- ✅ Letra capitular de 70px no primeiro parágrafo
- ✅ Mini-galeria com 4 imagens interativas
- ✅ Todos elementos clicáveis
- ✅ Design responsivo testado em 3 breakpoints

### Próximas Melhorias (Sugestões)

- [ ] Animações de entrada para elementos (fade-in)
- [ ] Mais variações de formatos de imagem (círculos, triângulos)
- [ ] Modo escuro/claro toggle
- [ ] Conteúdo dinâmico via JavaScript
- [ ] Efeitos parallax suaves no scroll
- [ ] Tipografia variável com ajustes dinâmicos

---

**📅 Última atualização:** 24 de Fevereiro de 2026
