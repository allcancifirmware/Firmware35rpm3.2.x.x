## FOWIFI3 35 RPM
**Versão Atual:** 3.2.14

## 📌 Descrição
[a definir]

## 📋 Changelog
### 🔄 Versão 3.2.0.14
- Melhoria estabilidade de envio de dados via Ethernet.
- Busca de horas e minutos mais leve , uma função de busca multifuncional para wifi e para ethernet.
- Redução do tempo de recuo , lento 10s rápido , 30s.
- Redução tempo recua resto (1° etapa lento 10s, rápido 5s) (2° etapa lento 8s, rápido 5s).
- mudança do display de kb para porecentagem na atualização

### 🔄 Versão 3.2.0.13
- Resolvido travamento ao retirar o cabo do modulo rj45
- Tela de monitoramento das boias.
- Melhoria do desempenho na troca de conexão de ethernet|Wifi

### 🔄 Versão 3.2.0.12
- Enviando para o tópico conectado no wifi ou com ethernet
- Remoção do alerta de nivel baixo , aparece o alerta apenas de for nivel crítico
- Resolvido o travamento do esp32 ao se reconectar na internet com o cabo Ethernet
- Desconexão automática do wifi se houver conexão ethernet.

### 🔄 Versão 3.2.0.11
- Atualização OTA via internet cabeada ( Ethernet )
- Envio do tipo de conexão se Wifi ou Cabo Ethernet
- Barra de carregamento da atualização.
- Interrupção imadiata no meio do recruo extra
- Melhoria no intertravamento da execução do RecuaResto
- Reset das credenciais wifimanager ultilizando o método wm.resetSettings();
- Atualização de firmware via cabo Ethernet

### 🔄 Versão 3.2.0.10
- Envio de localização através do wifi para a awsiot
- Envio de dados para aws com ethernet conectado

### 🔄 Versão 3.2.0.9
- Envio da localização no campo "ID"
- Implementação de envio de dados para uma base reserva ( obsoleto )
- correção nivel critico
- na função de limpeza apertar proximo depois do vermelho retorna
- Apertar dois botoes juntos além do tempo  pra alterar algo
- Melhoraria alteração de dosagem.
- Eliminar travamento com repetidor ruim.
- Mostrar o status real do cabo de rede

### 🔧 Versão 3.2.0.8
- Ajuste de dosagem de 6.5 para 5.8
- 1° Padronização de dosagem em 1450
- 2° Padronização de dosagem em 1475
- mistura de 8 em 8 horas
- Ajuste da fração de regulagem do motor para 25

### ⚡ Versão 3.2.0.7
- Atualização via cabo de rede pelo servidor hostinger (entre 11h e 12h)
- Mudança no sinal de conexão com cabo
- Correção de travamento no wifi manager
- Novos menus:
  - Checagem de WiFi e RJ45
  - Confirmação de atualização de tempo de dosagem
- Correção de erro ao salvar dosagem vermelha

### 🚀 Versão 3.2.0.6
- Implementação de recuo lento no início
- Mudança mais rápida de NS
- Remoção de redes WiFi salvas da memória
- WiFi inicia ativo
- Atualização automática às 12:00

### 🔢 Versão 3.2.0.5
- Alteração nos contadores

### 📶 Versão 3.2.0.4
- Função para ativar/desativar WiFi
- Exibição de endereço MAC

### 🔄 Versão 3.2.0.3
- WiFi Manager com NS no final do nome da rede
- Atualização via menu com confirmação
- Contador apenas total
- Mistura 2x ao dia
- Menu RJ45 para baixar atualizações

## ⚙️ Instalação
[a definir]

## 🛠️ Configuração
[a definir]

## 📄 Licença
[a definir]
