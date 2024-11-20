https://github.com/caiorfer/GS_IOT

https://www.youtube.com/watch?v=dAi0s2Kq14I

https://wokwi.com/projects/415050505847305217

Projeto IoT de Monitoramento de Temperatura e Umidade com ESP32 e ThingSpeak
Descrição
Este projeto monitora as condições de temperatura e umidade de um ambiente utilizando um sensor DHT22 e um ESP32 para leitura e envio de dados. Um LED é ativado para alertar quando as leituras estão fora da faixa segura. Os dados são enviados para o ThingSpeak para visualização em tempo real.

Funcionalidades
Monitoramento em tempo real de temperatura e umidade.
Alerta visual com LED quando os valores estão fora da faixa definida.
Visualização de dados no ThingSpeak com gráficos e painel de controle.
Armazenamento histórico dos dados para análise.
Hardware Utilizado
ESP32
Sensor DHT22 para medir temperatura e umidade
LED para sinalização
Conexão Wi-Fi para envio dos dados
Configuração
1. Configurar o ThingSpeak
Crie uma conta no ThingSpeak.
Crie um canal e adicione os campos:
Campo 1: Temperatura
Campo 2: Umidade
Anote o Channel ID e a API Key do canal para uso no código.
2. Configurar o ESP32
Conecte o DHT22 ao pino 15 do ESP32 e o LED ao pino 13.
Certifique-se de ter as bibliotecas WiFi.h, DHTesp.h e ThingSpeak.h instaladas.

Instruções de Uso
Carregar o código no ESP32.
Conectar o ESP32 à rede Wi-Fi.
Monitorar os dados no painel do ThingSpeak e observar o LED para alertas de temperatura e umidade.
Benefícios
Monitoramento remoto das condições ambientais.
Alertas automáticos com LED para situações fora da faixa segura.
Armazenamento de dados e visualização de tendências em um dashboard.
Conclusão
Este projeto demonstra uma aplicação prática de IoT usando o ESP32 e o ThingSpeak para monitorar condições ambientais. É ideal para monitoramento de ambientes controlados como estufas, salas de servidores ou laboratórios.


Licença
Este projeto é de uso livre para fins educacionais e pode ser modificado conforme necessário.

