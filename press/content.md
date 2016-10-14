# Introdução

### Introdução

\begin{figure}[h]
	\includegraphics[scale=0.5]{img/webrtc-logo-horiz-retro-750x140.png}
\end{figure}

**WebRTC** é um projeto livre que fornece a navegadores web e aplicações mobile
capacidade de **Real-Time Communications** (Comunicação em tempo real)
através de _API_s simples.

### Introdução

É uma iniciativa da W3C em conjunto com Google, Mozilla and Opera, entre outros.

O Web Real-Time Communications Working Group foi criado para criar e gerenciar
os padrões do WebRTC.

### Aplicação

Pode ser aplicado para todo tipo de plataforma que requer comunicação de alta qualidade
na web, tais como troca de **mensagens** e transferência de **arquivos**, componentes de
**áudio e vídeo** para vídeo conferências, **comunicação e controle** de equipamentos IoT.

\begin{figure}[h]
	\includegraphics[scale=0.35]{img/firefox-chrome-webrtc.jpg}
\end{figure}

# Arquitetura

### Arquitetura

A nível de browser:

\begin{figure}[h]
	\includegraphics[scale=0.35]{img/webrtc-architecture.png}
\end{figure}

### Arquitetura

WebRTC permite comunicação peer-to-peer (P2P) entre browsers

MAS ainda são necessários **servidores**:

\bigskip

**Para que clientes possam trocar metadados para coordenar a comunicação - isto
é chamado de _Signaling_.**

\bigskip

**Para lidar com _NAT_s (Network Address Translators) e _Firewalls_.**

### Arquitetura

\begin{figure}[h]
	\includegraphics[scale=0.35]{img/jsep.png}
\end{figure}

### Arquitetura

Para evitar redundância e maximizar a compatibilidade com tecnologias já estabelecidas,
métodos e protocolos para fazer _Signaling_ não foram especificados pelos padrões do 
WebRTC.

A lógica por trás disso é que diferentes aplicações podem preferir utilizar diferentes
protocolos, tais como _SIP_ (Session Initiation Protocol - VoIP)
ou _Jingle_ (extensão do XMPP/Jabber - Troca de mensagens de texto)
como protocolos para fazer _Signaling_.

<!-- http://io13webrtc.appspot.com/#44 -->





