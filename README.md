# Serviços Multimídia e Tráfego (QoS)

Este repositório documenta a implementação e análise de serviços de tempo real realizados no 3º semestre. O foco central é o impacto das métricas de rede (Latência, Jitter e Perda de Pacotes) na experiência do usuário em serviços de voz, vídeo e jogos.

## 🛠️ Ferramentas e Protocolos
* **Análise de VoIP/Vídeo:** SIP, RTP, RTCP, RTSP, IAX2.
* **Emulação de Atraso e Perda:** WANem, Clumsy.
* **Centrais Telefônicas:** Asterisk, FreePBX, Askozia PBX.
* **Streaming & Broadcast:** SHOUTcast, VLC Media Player, OBS Studio.

## 📂 Laboratórios e Análises Técnicas

### 1. Análise de QoS com TeamSpeak
* Avaliação de codecs de voz sob condições de rede instáveis (Satélite, Wireless).
* Correlação entre perda de pacotes e degradação perceptível do áudio.

### 2. Implementação de PABX IP (Askozia)
* Configuração de ramais SIP e interoperabilidade entre Softphones e Telefones IP físicos.
* Implementação de Trunk SIP e segurança (Firewall/NAT) em ambiente MikroTik.

### 3. Infraestrutura Asterisk e FreePBX
* Criação de planos de discagem, grupos de ramais e Correio de Voz.
* Implementação de Unidade de Resposta Audível (URA/IVR) e relatórios de chamadas (CDR).

### 4. Streaming de Áudio com SHOUTcast
* Arquitetura DNAS/DSP para transmissão de rádio online.
* Análise de vazão (Throughput) baseada no bitrate de transmissão.

### 5. Streaming de Vídeo e Protocolos RTSP/HTTP
* Comparação prática entre fluxos Unicast, Broadcast e Multicast.
* Análise de estados do protocolo RTSP (SETUP, PLAY) via Wireshark.

### 6. Tráfego de Jogos e Protocolo UDP
* Estudo da sincronização e latência em jogos de ação (Teeworlds, Doom).
* Impacto da perda de pacotes na física e visualização do jogo em tempo real.
