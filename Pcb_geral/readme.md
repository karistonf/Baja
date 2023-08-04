# Descrição da placa geral

## A placa geral será responsável por coletar estes dados:

Relacionando os sensores usados com o protocolo para leitura do sensor

* Velocidade -> Sensor Indutivo -> porta digital
* Sensor de combustível -> Sensor reed switch (desenvolvido pela nossa equipe) -> porta analógica
* Célula de carga -> Analógica
* Sensor de temperatura motor -> Analógica
* Acelerômetro e giroscópio -> I2C
* Sensor de temperatura CVT -> I2C
* GPS -> Serial
* Sensor de pressão do fluido de freio -> * falta escolher o sensor para definir *
* Radio Frequência -> SPI 

## O que foi feito

3/ago

* Foi implementado proteção contra excesso de corrente e tensão contrária.
* Adicionado os conectores para os sensores e dispositivos externos, posicionados, e serigrafia indicando corretamente as conexões.
* Foi arrumado a posição dos componentes do can
* Inseriu-se um conector tipo borne para conectar ao chicote do veículo

## Coisas à fazer

3/ago

* Colocar optoacoplador
* Exemplo de comunicação para GPS, e quais pinos conectar
* Confirmar pinos para comunicação I2C
* Exemplo e confirmar pinos para conectar a fita de led
* Usar fita de led 12V
* Verificar se a ligação do mosfet
* reduzir o tamanho do regulador de tensão de 5V (se dimensionado o consumo de corrente)
* desenhar o contorno da placa, e caixa para proteção




