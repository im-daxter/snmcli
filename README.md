# WiFi Connect Script 📶

Um utilitário simples em Shell Script para facilitar a conexão em redes Wi-Fi via terminal, utilizando o `nmcli` (Network Manager).

## 🚀 Funcionalidades
* Verifica dispositivos de rede gerenciados.
* Ativa o rádio Wi-Fi automaticamente.
* Lista todas as redes disponíveis em tempo real.
* Interface interativa para digitar o SSID e a senha.

## 📋 Pré-requisitos
Para utilizar este script, você precisa ter o **NetworkManager** instalado e rodando no seu sistema Linux.

```bash
# Exemplo de como verificar se você tem o nmcli instalado
nmcli --version

🛠️ Como usar

    Clone o repositório ou baixe o arquivo:
    Bash

    git clone https://github.com/seu-usuario/nome-do-repo.git
    cd nome-do-repo

    Dê permissão de execução ao script:
    Bash

    chmod +x wifi_connect.sh

    Execute o script:
    Bash

    ./wifi_connect.sh

📝 Exemplo de Uso

Ao rodar o script, ele listará as redes e pedirá os dados:

    SSID: O nome da rede Wi-Fi.

    Senha: O prompt do nmcli abrirá pedindo a credencial de forma segura.

👤 Autor

Desenvolvido por im-daxter.
