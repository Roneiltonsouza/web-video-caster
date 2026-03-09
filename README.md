# Web Video Caster Pro 📺

O **Web Video Caster Pro** é um aplicativo web avançado para espelhamento de tela (*Screen Mirroring*). Ele foi desenvolvido para permitir a transmissão de conteúdo em tempo real entre dispositivos móveis e Smart TVs, utilizando o que há de mais moderno em comunicação web.

## 🚀 Funcionalidades

- **Espelhamento Celular para Celular:** Conexão direta via ID utilizando o protocolo **WebRTC**.
- **Interface Original Preservada:** Design limpo, intuitivo e responsivo.
- **Suporte Multi-Marca:** Seleção rápida para TVs **Samsung, LG, TCL, Roku e Sony**.
- **Modo Escuro (Dark Mode):** Alternância de tema para melhor conforto visual.
- **Conexão Peer-to-Peer:** O vídeo é transmitido diretamente entre os aparelhos através da biblioteca **PeerJS**, garantindo privacidade e menor latência.

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Interface moderna com suporte a variáveis de cores e layouts flexíveis.
- **JavaScript (Vanilla):** Lógica de aplicação pura para máxima velocidade.
- **WebRTC API:** Tecnologia de ponta para transmissão de mídia em tempo real.
- **PeerJS:** Utilizado para a sinalização e aperto de mão (*handshake*) entre os dispositivos sem a necessidade de um servidor de backend complexo.
- **getDisplayMedia:** API nativa dos navegadores para captura de tela de alta definição.

## 📱 Como usar o espelhamento entre celulares

1. **No Celular A (Quem transmite):** - Clique em **"Gerar meu código de conexão"**.
   - Copie o ID que aparecerá na tela.
2. **No Celular B (Quem recebe):**
   - Cole o código recebido no campo de texto.
   - Clique em **"Conectar e Transmitir"**.
3. **Autorização:** - O Celular A deve aceitar a permissão de "Gravação/Captura de Tela" que o navegador solicitará.

## 🔒 Requisitos de Segurança e Funcionamento

Para garantir o funcionamento 100% estável:
- **HTTPS:** O navegador exige uma conexão segura (SSL) para liberar a captura de tela. O projeto está configurado para rodar perfeitamente no **GitHub Pages**.
- **Permissões de Sistema:** Certifique-se de que o navegador tem permissão para acessar a "Captura de Tela" nas configurações do seu Android ou iOS.
- **Navegador:** Recomendado o uso do Google Chrome ou Samsung Internet atualizados.

---
Desenvolvido por [Seu Nome/GitHub User]
