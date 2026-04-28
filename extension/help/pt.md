---
layout: bare
title: Spanish Reader Extensão - Guia do usuário
lang: pt
---

# Spanish Reader - Guia do usuário

> Version: v1.0.0

## Introdução

Spanish Reader é uma extensão de navegador feita para quem aprende espanhol. Ela adiciona anotações de pronúncia e marcas de separação silábica às palavras em espanhol em páginas da web e em PDFs, com suporte aos sotaques latino-americano e da Espanha. Também inclui dicionário ao passar o mouse, texto em voz (TTS) e tradução — para ajudar você a aprender a pronúncia do espanhol com mais facilidade.

---

## Principais recursos

- **Whole Page Pronunciation Mode** — Adicione anotações de pronúncia a todas as palavras em espanhol na página com um clique
- **Syllable Breaks** — Mostre divisão silábica e ênfase para cada palavra
- **Hover Dictionary** — Passe o mouse sobre as palavras para ver definição, pronúncia e botão de alto-falante; escolha Dictionary, Tooltip ou Off
- **PDF Reader** — Leitor PDF integrado com anotações, dicionário, leitura e tradução; suporta arrastar e soltar, carregar por URL e detecção automática de PDF
- **Latin American & Spain Accents** — Alterne entre pronúncia latino-americana (es-419) e da Espanha (es-ES)
- **Text-to-Speech** — Clique no botão de alto-falante para ouvir a pronúncia no sotaque selecionado
- **Selection Speech with Karaoke Effect** — Selecione texto em espanhol: aparece uma barra compacta com ler e traduzir; a leitura destaca palavra por palavra em tempo real
- **Selection Translation** — Selecione texto, clique em traduzir para tradução instantânea via Bing Translate ou Google Translate
- **Keyboard Shortcuts** — Acesso rápido aos recursos principais com atalhos personalizáveis

---

## Como usar

### Passo 1: Instalar a extensão

Instale **Spanish Reader** na [Chrome Web Store](https://chromewebstore.google.com/) ou carregue localmente no modo de desenvolvedor.

### Passo 2: Abrir uma página web

Acesse uma página com conteúdo em espanhol.

### Passo 3: Ativar a pronúncia

Clique no ícone da extensão na barra de ferramentas. Ative «Enable Pronunciation» e depois «Whole Page Mode» para anotar todas as palavras na página.

### Passo 4: Ver a pronúncia

Passe o mouse sobre as palavras para ver dicas de pronúncia. Clique no ícone de alto-falante para ouvir. Syllable Breaks mostram a estrutura da palavra (ex.: «com·pu·ta·do·ra»).

### Passo 5: Ler e traduzir o texto selecionado

Selecione texto em espanhol com o mouse. Perto da seleção aparece uma barra compacta com dois botões:
- **🔊 Speak** — Lê o texto em voz alta com destaque palavra por palavra estilo karaokê
- **🌐 Translate** — Mostra um balão de tradução inline abaixo da barra

> **Dica:** Clique no ícone da extensão para abrir as configurações e ajustar sotaque, velocidade da fala, modo de hover, motor de tradução e mais.

---

## Whole Page Pronunciation Mode

Com o Whole Page Pronunciation Mode ativado, cada palavra em espanhol recebe uma anotação de pronúncia acima, em ruby text.

A extensão ajusta automaticamente a altura da linha para evitar sobreposição com o texto.

---

## Syllable Breaks

Com «Show syllable breaks» ativado, cada palavra mostra sua divisão silábica:

- Sílabas são separadas por ponto médio (·)
- A sílaba tônica segue as regras de acento do espanhol
- Palavras com acento escrito (á, é, í, ó, ú) têm sempre o acento na sílaba marcada

Ajuda quem estuda a entender:
- Onde colocar ênfase ao falar
- Como as palavras se quebram no fim de linha
- A estrutura rítmica do espanhol

---

## Hover Dictionary

A extensão inclui um dicionário ao passar o mouse. Nas configurações você escolhe o modo:

| Mode | Comportamento |
|------|---------------|
| **Dictionary** | Hover mostra pronúncia + definição + botão de alto-falante |
| **Tooltip** | Hover mostra pronúncia + botão de alto-falante (sem definições) |
| **Off** | Sem efeito ao passar o mouse |

---

## PDF Reader

Spanish Reader inclui um PDF Reader integrado para ler PDFs com anotações, dicionário, leitura e tradução.

### Abrir um PDF

**Método 1: Pelo popup**  
Clique no ícone da extensão e em «Open PDF Reader». Arraste um PDF ou clique em «Choose File» para abrir um arquivo local. Você também pode colar uma PDF URL.

**Método 2: Menu de contexto**  
Clique com o botão direito em um link `.pdf` e escolha «Open PDF with Spanish Reader».

**Método 3: Detecção automática**  
Com «PDF Smart Detection» ativado nas configurações, a extensão redireciona automaticamente URLs `.pdf` para o leitor integrado.

### Recursos do PDF Reader

- **Pronunciation Annotations** — Todos os recursos de pronúncia funcionam no texto do PDF
- **Click Dictionary** — Clique em uma palavra para ver a definição
- **Selection Toolbar** — Selecione texto para falar, traduzir ou copiar
- **Sidebar** — Sumário e miniaturas de página
- **Search** — Busca de texto no PDF
- **Themes** — Temas de leitura Dark, Light e Sepia
- **Zoom** — Vários níveis, incluindo Auto, Page Fit e Page Width

---

## Tradução

Selecione texto na página e use a tradução para obter resultados na hora.

**Método 1: Barra de seleção**  
Selecione texto e clique em 🌐 translate na barra.

**Método 2: Menu do botão direito**  
Selecione texto, clique com o direito e escolha «Translate Selection».

**Método 3: Atalho de teclado**  
Selecione texto e pressione `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Motores de tradução:**
- **Bing Translate** (padrão) — Microsoft Translator
- **Google Translate** — Google

Ambos suportam **108** idiomas de destino.

---

## Atalhos de teclado

| Atalho | Mac Shortcut | Ação |
|--------|--------------|------|
| `Alt+Shift+I` | `Ctrl+Shift+I` | Ligar/desligar anotações de pronúncia |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Ler o texto selecionado |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduzir o texto selecionado |

> **Dica:** Personalize os atalhos no Chrome em `chrome://extensions/shortcuts`.

---

## Guia de configurações

| Configuração | Descrição |
|----------------|-----------|
| **Enable Pronunciation** | Interruptor principal das anotações de pronúncia |
| **Whole Page Mode** | Mostra pronúncia sobre todas as palavras em espanhol |
| **Accent** | Escolha sotaque latino-americano ou da Espanha |
| **Show syllable breaks** | Exibe marcas de divisão silábica |
| **Hover Mode** | Comportamento ao passar o mouse: Dictionary (pronúncia + definições + áudio), Tooltip (pronúncia + áudio) ou Off |
| **Sentence Speech Rate** | Velocidade da leitura de frases |
| **Translation Engine** | Bing Translate ou Google Translate |
| **Target Language** | Idioma de destino da tradução |
| **PDF Smart Detection** | Redireciona automaticamente PDF URL para o leitor integrado |

---

## Perguntas frequentes

**P: Por que não funciona em algumas páginas?**  
R: Por segurança, extensões não rodam em páginas especiais como `chrome://`, configurações do navegador ou Chrome Web Store.

**P: Sem som no texto em voz?**  
R: Verifique o volume do sistema e se os pacotes de voz em espanhol estão instalados.

**P: A tradução não funciona?**  
R: A tradução precisa de Internet. Se o Bing Translate falhar, tente Google Translate nas configurações.

---

## Links relacionados

- [Política de privacidade](../privacy-policy)
- [Suporte e feedback](../support)

---
