# FIP-MDF — Site Institucional

Este repositório apresenta o site institucional da **FIP-MDF**, uma empresa de tecnologia sustentável especializada em soluções integradas de filtragem, neutralização e reaproveitamento de subprodutos na produção de MDF/MDP. O objetivo é comunicar quem somos, nossas soluções e como nos conectar.

## 🌟 Sobre a FIP-MDF

A FIP-MDF nasceu da união de cinco visionários — Alice, Jéssica, Maria Eduarda, Gabriel e Hiury — com a missão de inovar no setor de engenharia e sustentabilidade industrial. Transformamos resíduos e poluentes gerados na produção (pó de madeira, formaldeído e compostos fenólicos) em insumos reutilizáveis e de alto valor econômico, reduzindo emissões e protegendo a saúde ocupacional.

## 🚀 O que entregamos

- **Projetos e fabricação** de equipamentos para tratamento e filtragem de particulados e gases
- **Suporte técnico** e consultoria aplicada a processos industriais
- **Compromisso** com sustentabilidade e conformidade regulatória
- **Soluções integradas** que transformam desafios ambientais em oportunidades de inovação

## 🔧 Produtos e Tecnologias

- **Filtro Ciclônico FIP-MDF** — Separação eficiente de particulados
- **Lavador de Gases Modular** — Neutralização de gases tóxicos
- **Filtro de Carvão Ativado Industrial** — Remoção final de VOCs e fenóis

## 🎨 Funcionalidades do Site

### ✅ Implementações Recentes

- **Layout responsivo** com design moderno e acessível
- **Galeria de projetos interativa** com modal de visualização e zoom
- **Sistema de modal com zoom** para explorar detalhes das imagens
- **Seção "Sobre Nós"** com logo centralizado e informações da equipe
- **Formulário de contato direto** integrado com EmailJS para envio de emails
- **Otimizações visuais** com logo redimensionado e centralizado
- **Estrutura semântica** com meta tags para SEO e redes sociais
- **Separação de estilos CSS** por competência (socios.css, galeria.css)
- **Ajuste de consistência visual** das imagens da equipe

### 📧 Sistema de Contato

O formulário de contato utiliza **EmailJS** para envio direto de emails, eliminando a necessidade de abrir aplicações externas. Para ativar:

1. Configure as credenciais EmailJS em `index.html`:
   - `SERVICE_ID` — ID do serviço EmailJS
   - `TEMPLATE_ID` — ID do template de email
   - `PUBLIC_KEY` — Chave pública da conta

2. O sistema inclui feedback visual para o usuário durante o envio

### 🖼️ Galeria Interativa

- **Modal de visualização**: Clique em qualquer imagem para abrir em tela cheia
- **Controles de zoom**: Botões de aumentar/diminuir zoom, reset e scroll do mouse
- **Navegação intuitiva**: Arraste a imagem quando com zoom aplicado
- **Responsividade total**: Funciona perfeitamente em dispositivos móveis
- **Efeitos visuais**: Hover com brilho e indicador de zoom

## 📁 Estrutura do Projeto

```
FIP-MDF/
├── index.html          # Página principal com estrutura semântica
├── index.css           # Estilos responsivos e variáveis CSS
├── socios.css          # Estilos específicos da seção de sócios
├── galeria.css         # Estilos da galeria e modal de imagens
├── imgs/
│   ├── produto/        # Imagens de produtos e logo
│   │   ├── logo.png    # Logotipo oficial da FIP-MDF
│   │   └── [renderizações dos equipamentos]
│   └── socios/         # Fotos da equipe fundadora
│       ├── equipe.svg  # Imagem SVG da equipe
│       └── [fotos individuais dos sócios]
└── README.md           # Este arquivo
```

## 🌐 Como Acessar

**Site publicado:** [https://pedroscfa.github.io/FIPMDF/](https://pedroscfa.github.io/FIPMDF/)

O site é automaticamente publicado via **GitHub Pages** a partir da branch `main`. Qualquer commit na branch principal atualiza o site em poucos minutos.

### Configuração do GitHub Pages
1. Acesse `Settings` → `Pages` no repositório
2. Source: `Deploy from a branch`
3. Branch: `main`
4. Pasta: `/root`

## 👥 Equipe Fundadora

- **Alice Vasques Rodrigues** — Diretora de Inovação
- **Hiury de Oliveira Lima** — Diretor de Tecnologia  
- **Jessica Martins Lino** — Diretora de Operações
- **Maria Eduarda Rocha Teixeira** — Diretora de Sustentabilidade
- **Gabriel Ferreira Lopes** — Coordenador de Projetos

## 🔄 Histórico de Alterações

### Versão Atual (v2.0)
- ✅ **Modal de imagens interativo** com sistema de zoom e navegação
- ✅ **Separação de estilos CSS** em arquivos por competência
- ✅ **Ajuste de consistência** no tamanho das imagens da equipe
- ✅ **Remoção de estilos inline** e organização em classes CSS
- ✅ **Otimização de performance** com lazy loading e animações suaves
- ✅ **Melhorias de acessibilidade** e responsividade

### Versão Anterior (v1.0)
- ✅ Substituição da grade de fotos dos sócios por logo centralizado
- ✅ Integração do EmailJS para envio direto de emails
- ✅ Otimização do tamanho e centralização do logo
- ✅ Melhoria na responsividade e acessibilidade
- ✅ Adição de feedback visual no formulário de contato

### Melhorias Técnicas
- **CSS responsivo** com breakpoints otimizados
- **Variáveis CSS** para consistência visual
- **Lazy loading** nas imagens para performance
- **Estrutura semântica** para SEO
- **Acessibilidade** com skip links e ARIA labels
- **JavaScript modular** para funcionalidades interativas

## 📞 Contato

- **E-mail:** Fipmdf.contato@gmail.com
- **Instagram:** [@fipmdf](https://www.instagram.com/fipmdf/)
- **Site:** [fipmdf.github.io](https://pedroscfa.github.io/FIPMDF/)

## 📄 Direitos e Uso

Conteúdo e imagens destinados à apresentação institucional da FIP-MDF. Todos os direitos reservados.

---

**FIP-MDF** — Transformando resíduos em recursos, inovação em sustentabilidade.
