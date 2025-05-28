# Video-Downloader
Uma aplicação web full-stack para baixar vídeos de **YouTube**, **Instagram** e **TikTok** de forma simples e rápida.   Frontend em **HTML/CSS/JS puro** e backend em **Node.js + Express** usando **youtube-dl-exec** (ou **yt-dlp**).


## 🛠 Funcionalidades

- **Detecção automática de plataforma** (YouTube, Instagram, TikTok)  
- **Validação de URL** por plataforma, com feedback inline  
- **Spinner de loading** no botão de download  
- **Histórico de downloads** (armazenado em localStorage)  
- **Rebaixar** vídeos diretamente do histórico  
- **Pré-visualização do título** dos vídeos YouTube via oEmbed  
- **Download via fetch+Blob** para forçar “Save As…” sem sair da página  

> Futuras melhorias: modo Dark/Light, responsividade avançada, preview de thumbnail, micro-interações extras.

## 📦 Tecnologias

- **Frontend**  
  - HTML5, CSS3 (Flexbox, variáveis CSS)  
  - JavaScript (ES6+, Fetch API, localStorage)  
- **Backend**  
  - Node.js, Express  
  - youtube-dl-exec (wrapper para yt-dlp ou youtube-dl)  
- **Outros**  
  - localStorage (para histórico)  
  - oEmbed do YouTube para obter título
