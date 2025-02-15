# previcaoMeteorologicaPlaca

Estação Meteorológica Conectada com BitdogLab

Nos últimos dias, trabalhei em um projeto de estação meteorológica conectada utilizando IoT e a placa BitdogLab . O objetivo foi criar um sistema que monitorasse temperatura, umidade e pressão atmosférica, exibindo os dados localmente e enviando-os para a nuvem. Como não possuo sensores físicos no momento, implementei um modo de simulação para gerar os dados e testar a conectividade.

Componentes Utlizados:

Placa BitdogLab (Raspberry Pi Pico W)
LEDs para indicar o status do sistema.
Protoboard, jumpers e fonte de alimentação.

Funcionamento:
O site recebe os dados, que são retornavel da API e manda o coletamento de dados da umidade relativa do ar para placa
Processamento:
O django é responsavel d
Indicação por LEDs
LED Verde acende quando a umidade relativa do ar estiver acima de 60%
O LED vermelho acende quando a umidade relativa do ar estiver abaixo de 60%

- Video mostando o Projeto:
  - link: https://drive.google.com/file/d/1MQD56P4z2ZalT8FPe93a5cQWwpbhNEtL/view?usp=sharing

