# 💬 Visualizador de Conversa WhatsApp

Página web estática que lê um arquivo `.zip` exportado pelo WhatsApp e exibe a conversa com visual idêntico ao do aplicativo, incluindo suporte a mídias.

🔗 **[Acessar a página](https://dougmatos.github.io/visualizador-wpp)**

---

## ✨ Funcionalidades

- 📂 **Upload por clique ou arrastar** — basta soltar o ZIP exportado pelo WhatsApp
- 💬 **Visual idêntico ao WhatsApp** — balões coloridos, separadores de data, hora e ticks de leitura
- 🖼️ **Imagens** — exibidas diretamente no balão, com lightbox ao clicar
- 🎬 **Vídeos** — player embutido no balão
- 🎵 **Áudios** — player com barra de progresso e botão play/pause
- 📍 **Localização** — link direto para o Google Maps
- ✏️ **Mensagens editadas** — marcadas com a tag *editada*
- 👥 **Agrupamento de mensagens** — mensagens consecutivas do mesmo remetente são agrupadas, igual ao WhatsApp
- 💾 **Salvar** — exporta a conversa inteira como um único arquivo `.html` autocontido (mídias embutidas em base64), sem precisar de servidor para abrir

---

## 🚀 Como usar

1. Exporte uma conversa no WhatsApp:
   - Abra a conversa → Menu (⋮) → **Mais** → **Exportar conversa**
   - Escolha **Incluir mídia** para exportar fotos, vídeos e áudios junto
2. Acesse a [página](https://dougmatos.github.io/visualizador-wpp)
3. Faça upload do arquivo `.zip` gerado
4. Selecione o seu nome na conversa
5. Navegue pela conversa — use **Salvar** para baixar o HTML autocontido

---

## 🔒 Privacidade

Todo o processamento acontece **100% no navegador**. Nenhum arquivo ou mensagem é enviado para qualquer servidor.

---

## 🛠️ Tecnologias

- HTML + CSS + JavaScript puro (sem frameworks)
- [JSZip](https://stuk.github.io/jszip/) — leitura do arquivo ZIP no browser
