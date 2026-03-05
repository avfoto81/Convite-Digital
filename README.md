# 🎉 Convite Digital — Maitê 12 Anos

Convite de aniversário digital feito com HTML, CSS e JavaScript. Criado para ser compartilhado via WhatsApp, com confirmação de presença e integração com Google Forms e Google Calendar.

---

## 📁 Arquivos do Projeto

```
convite-digital/
├── index.html               # Página do convite — tudo em um único arquivo
├── convite_img_02.png        # Imagem principal do convite
├── convite-balao-rose.png    # Imagem exibida no preview ao compartilhar no WhatsApp
└── google-maps.png           # Ícone de atalho para o Google Maps
```

---

## ✨ Funcionalidades

### 🖼️ Imagem do Convite
Imagem principal exibida no topo, responsiva e adaptada para celular.

### 📋 Formulário de Confirmação
Permite confirmar a presença de até 4 convidados por envio, com campos de nome e idade para cada um.

### ✅ Botão "Confirmar Presença via WhatsApp"
Ao clicar, duas coisas acontecem:
- Os dados são enviados automaticamente para o **Google Forms**, ficando registrados numa planilha do Google Sheets
- O **WhatsApp** abre com uma mensagem já pronta para o convidado enviar, no formato:
```
Olá! Confirmo presença na festa da Maitê! 🎉
• Nome do convidado — 35 anos
• Nome do convidado — 8 anos
```

### 📅 Botão "Adicionar à minha agenda"
Aparece na tela após o convidado confirmar a presença. Ao clicar, abre o **Google Calendar** com o evento já preenchido — data, hora, local e descrição — pronto para salvar com um clique.

### ❌ Botão "Não poderei comparecer"
Exibe uma mensagem de agradecimento pelo aviso.

### 🗺️ Mapa no Rodapé
Ícone clicável que abre o endereço do evento direto no Google Maps.

---

## 📱 Preview no WhatsApp

Ao compartilhar o link do convite no WhatsApp, aparece automaticamente uma prévia com imagem, título e descrição do evento, tornando o convite mais atrativo antes mesmo de abrir.

---

## 🚀 Hospedagem no Vercel

O projeto está hospedado gratuitamente no Vercel. Para atualizar após alguma mudança:

1. Faça as alterações no arquivo
2. Envie para o GitHub:
```bash
git add .
git commit -m "descrição da alteração"
git push
```
3. O Vercel detecta e publica automaticamente.

**URL do projeto:** https://convite-digital-chi.vercel.app/

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estrutura da página
- **CSS3** — visual responsivo para celular
- **JavaScript** — lógica do formulário e integrações
- **Google Fonts** — fonte Merriweather
- **Google Forms + Sheets** — recebe e armazena as confirmações
- **WhatsApp** (wa.me) — confirmação direta por mensagem
- **Google Calendar** — agendamento do evento com um clique
- **Vercel** — hospedagem gratuita

---

## ✏️ Como Personalizar para Outro Evento

| O que alterar | Onde fica no arquivo |
|---|---|
| Nome do aniversariante | Título da página e textos do HTML |
| Data, hora e local | Seção de informações e link do Google Calendar |
| Imagem do convite | Tag `<img>` principal |
| Imagem do preview do WhatsApp | Meta tag `og:image` |
| Número do WhatsApp para receber confirmações | Variável `linkWhats` no JavaScript |
| Prazo de confirmação | Texto em negrito dentro do formulário |

---

## 📄 Licença

Projeto pessoal de uso livre. Desenvolvido com ❤️ para a festa da Maitê.
