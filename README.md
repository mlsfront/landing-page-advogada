# Landing Page - Advogada | Cálculos Trabalhistas, Perícia Judicial e PJe-Calc

Landing page institucional de página única (_one-page_) criada para apresentação profissional e captação de clientes de uma advogada especializada em **cálculos trabalhistas**, **perícia judicial**, **assistência técnica**, **PJe-Calc**, **revisão e impugnação de cálculos** e **revisão PASEP**.

O projeto é composto por **um único arquivo HTML** com CSS e JavaScript embutidos; sem dependências, sem build, sem backend. Basta abrir no navegador ou publicar em qualquer hospedagem estática.

---

## 🎯 Objetivo

Oferecer uma presença digital sóbria, elegante e profissional que:

- Apresente os serviços técnicos da advogada de forma clara
- Transmita credibilidade e domínio técnico (especialmente em PJe-Calc e revisão de cálculos)
- Facilite o contato direto via **WhatsApp** e formulário
- Funcione perfeitamente em **desktop, tablet e celular**
- Respeite o **Provimento nº 205/2021 da OAB** (sem promessa de resultado, sem mercantilização)

---

## 🧩 Estrutura da página (11 seções)

| # | Seção | Descrição |
|---|-------|-----------|
| 1 | **Hero** | Apresentação principal com headline, CTAs e card lateral de serviços |
| 2 | **Serviços** | Grid com 6 cards: cálculos, perícia, assistência técnica, PJe-Calc, revisão e PASEP |
| 3 | **Diferenciais** | 6 pontos numerados: rigor técnico, sigilo, prazos, linguagem acessível, atendimento nacional, suporte |
| 4 | **Metodologia** | Timeline em 5 etapas, do primeiro contato ao suporte pós-entrega |
| 5 | **PJe-Calc** | Bloco destacado (fundo escuro) com os recursos do sistema do CNJ |
| 6 | **Revisão & Impugnação** | Layout em duas colunas explicando o serviço e o que contempla |
| 7 | **O que o cliente recebe** | 6 entregáveis: planilha, parecer, laudo, minuta, resumo e suporte |
| 8 | **Sobre** | Apresentação profissional com foto, formação e tags de especialidade |
| 9 | **Revisão PASEP** | Seção específica com análise, identificação de diferenças e cálculo para ação |
| 10 | **FAQ** | Acordeão com 7 perguntas frequentes |
| 11 | **Contato** | Formulário (integrado ao WhatsApp) + canais diretos + CTA final + rodapé |

Além disso, inclui:

- **Botão flutuante de WhatsApp** em todas as telas
- **Menu fixo** com navegação suave entre seções
- **Faixa CTA** antes do contato
- **Rodapé** com aviso de conformidade OAB e links rápidos

---

## ✨ Recursos técnicos

- **Um único arquivo:** (`index.html`) com HTML, CSS e JS embutidos
- **Sem dependências externas:** não requer Node, npm, build ou frameworks
- **Responsivo (mobile-first):** breakpoints em 960px, 900px, 860px, 800px, 640px e 600px
- **Animações de entrada:** suaves via `IntersectionObserver`
- **FAQ acordeão:** acessível (abre/fecha com clique)
- **Formulário:** que monta uma mensagem formatada e abre o WhatsApp
- **Fontes:** carregadas via Google Fonts (_Playfair Display_ + _Inter_)
- **SEO básico:** title, meta description e Open Graph
- **Sem rastreamento:** por padrão (Analytics/Pixel podem ser adicionados)

---

## 🗂️ Estrutura de arquivos

```
.
├── index.html      # Site completo (HTML + CSS + JS)
└── README.md       # Este arquivo
```

Nenhum outro arquivo é necessário. Imagens, favicon e arquivos adicionais podem ser colocados na raiz ou em subpastas (`/assets`, `/img`).

---

## 🚀 Como usar

### 1. Visualizar localmente
Baixe o `index.html` e abra no navegador (duplo clique). Pronto.

### 2. Publicar no GitHub Pages
1. Crie um repositório e envie o `index.html` e o `README.md`.
2. Vá em **Settings → Pages**.
3. Em _Source_, escolha **Deploy from a branch** → `main` → `/ (root)`.
4. Salve. Em alguns instantes o site estará em:
   `https://seu-usuario.github.io/nome-do-repo/`

### 3. Publicar em outra hospedagem
Também funciona sem alterações em **Netlify**, **Vercel**, **Cloudflare Pages**, **Hostinger**, **KingHost** ou qualquer servidor que sirva arquivos estáticos.

---

## 🛠️ Personalização (checklist)

Antes de publicar, substitua os valores entre colchetes e placeholders:

| O que trocar | Onde está |
|---|---|
| `[Nome]` | Logo (header), hero, seção "Sobre", rodapé |
| `[Nome da Advogada]` | Seção "Sobre", rodapé |
| `55DDDNUMERO` | Todos os links `wa.me` (header, hero, CTAs, form, botão flutuante) |
| `contato@seudominio.adv.br` | Seção "Contato" e rodapé |
| `OAB/[UF] nº [número]` | Seção "Sobre" e rodapé |
| `[Foto profissional aqui]` | Bloco `.about-photo` na seção "Sobre" |
| `+10 anos`, `100%`, `Brasil` | Bloco `.hero-trust` no hero |
| `[X] anos` | Seção "Sobre" |

**Formato do WhatsApp:** número no padrão internacional, sem espaços ou símbolos.  
Exemplo: `5511987654321` (55 + DDD + número).

---

## 🎨 Identidade visual

- **Paleta:** azul-marinho (`#0f1c33`), dourado (`#c8a15a`), grafite e branco
- **Tipografia:** _Playfair Display_ (títulos) + _Inter_ (corpo)
- **Estilo:** sóbrio, elegante, com detalhes dourados discretos
- **Layout:** grid centralizado com largura máxima de 1140px

As cores e fontes podem ser ajustadas nas variáveis CSS em `:root` no topo do arquivo.

---

## 📱 Compatibilidade

- Chrome, Firefox, Safari, Edge (versões modernas)
- iOS Safari e Chrome Android
- Não requer JavaScript habilitado para exibir o conteúdo (apenas para interações)

---

## ⚖️ Conformidade com a OAB

O conteúdo foi redigido respeitando o **Provimento nº 205/2021 do Conselho Federal da OAB**, que disciplina a publicidade na advocacia. Em especial:

- Não há promessa de resultado
- Não há captação de causa ou mercantilização da profissão
- O rodapé traz aviso de caráter meramente informativo
- O tom é institucional e técnico, não publicitário

---

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
