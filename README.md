# Baja

## Projeto Baja SAE UEM - Equipe Capibaja
O Projeto Capibaja é um projeto acadêmico que visa a construção de um carro off-road monoposto movido a gasolina. A parte elétrica do veículo é responsável pela coleta de dados do carro e pela interface com o piloto, incluindo o monitoramento de velocidade e rodagem, bem como a saúde dos demais componentes do veículo. Não cabe a elétrica a fabricação de injeção eletrônica.

# Capacidades e objetivos do projeto
## Coleta de dados
* Velocidade (individual por roda) 
* Rodagem
* Temperatura CVT e motor
* Coordenadas de GPS
* Nível de Combustível
* Tensão da bateria
* Pressão nos freios
* E o mais importante, uma fita de led estilosa

# Construção

No projeto Capibaja, adotamos uma abordagem descentralizada para a coleta de dados, utilizando várias pequenas placas denominadas "placas gerais" (você pode obter mais informações sobre elas nos diretórios deste commit). Cada sensor é conectado a um microcontrolador, que por sua vez possui acesso à rede CAN de todo o veículo. Essas placas gerais são específicas para cada sensor e têm a função de ler os dados do sensor e transmitir seu valor na rede CAN.

Além das placas gerais, haverá uma segunda placa PCB, chamamos ela de placa principal, acessível ao piloto. Essa placa contará com uma tela e botões, servindo como interface para exibir os dados do carro em tempo real.

# Placa geral
Por enquanto é um esboço
Essa será a placa que coletara os dados dos sensores

![alt text](https://github.com/karistonf/Baja2023/blob/master/Imagens/placa_geral_1.png?raw=true)

# Placa principal
Essa será a placa que mostrará ao piloto as informações necessárias
![alt text](https://github.com/karistonf/Baja2023/blob/master/Imagens/Captura%20de%20tela%20de%202023-06-22%2023-47-05.png?raw=true)

# À fazer
* Corrigir footprint SD Card, Display 128x64
* Colocar os botões no lado correto


# Adicionar

# Feito
* Can transmissor


[![Ver modelo 3D no Sketchfab](https://img.shields.io/badge/Ver%20Modelo%203D-Sketchfab-blue?style=for-the-badge&logo=sketchfab)](https://sketchfab.com/3d-models/bucha--sensor-temperatura-motor-baja-v-1-body-8e9ac87ca9e7477eb5828cdfb5dba526)


<iframe width="640" height="480"
        src="https://sketchfab.com/models/8e9ac87ca9e7477eb5828cdfb5dba526/embed"
        frameborder="0" allow="autoplay; fullscreen; xr-spatial-tracking"
        allowfullscreen>
</iframe>

[🔗 Visualizar Modelo 3D Interativo](https://SEU_USUARIO.github.io/SEU_REPOSITORIO/)

