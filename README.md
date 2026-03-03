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
```

## 🛠️ Como usar

1. Clone o repositório:
```bash
git clone https://github.com/im-daxter/snmcli.git
cd snmcli
```
  
Dê permissão de execução ao arquivo:
  
```bash
chmod +x wifi_connect.sh
```

Execute o script:
```bash
./snmcli
```

## 📝 Como funciona

O script executa os seguintes passos:

    • Lista as interfaces de rede para confirmar se o Wi-Fi está disponível.

    • Garante que o rádio Wi-Fi esteja ligado (nmcli r wifi on).

    • Escaneia e mostra as redes próximas.

    • Solicita o nome da rede (SSID) e a senha de forma segura através do parâmetro --ask.

## 👤 Autor

Desenvolvido por **im-daxter**.
