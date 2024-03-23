# DSC-ITA-2023

Data Science Challenge @ ITA 2023

## Visão Geral

O ELDT (Estimated Landing Time) é o horário previsto para o pouso de aeronaves, essencial para o planejamento do transporte aéreo. Impacta diretamente a alocação de portões, esteiras de bagagens, reabastecimento de aeronaves e a gestão do espaço aéreo. Sua importância reside na melhoria da previsibilidade na aviação, otimizando o uso da infraestrutura aeroportuária e permitindo a introdução de novas tecnologias como drones e eVTOLS.

## Conjunto de Dados

1. `BIMTRA` (Banco de Informações de Movimento de Tráfego Aéreo): Contém informações sobre os movimentos nos aeródromos do Brasil, incluindo hora estimada de decolagem, origem, destino e tempo de voo previsto.

2. `Síntese Radar CAT-62`: Fornece registros a cada 4 segundos para cada aeronave em voo no espaço aéreo brasileiro.

3. Dados metereológicos

   - `METAR`: Telemetria de estações meteorológicas da região dos aeródromos, com informações como temperatura, velocidade do vento e umidade.
   - `Imagens de Satélite Meteorológico`: Disponibilizadas em formato de imagem para identificar condições severas, precipitações e movimento de nuvens, como visto na figura abaixo.
   - `METAF` (Terminal Aerodrome Forecast): Apresenta previsões meteorológicas para a próxima hora.

4. Dados de `ATFM` (Air Traffic Flow Management):
   - `Esperas em Voo`: Informações sobre espera de aeronaves em voo.
   - `Previsão e Histórico de Troca de Cabeceira`: Dados relacionados às mudanças na orientação das pistas de pouso e decolagem.

## Como Executar

`Instalação de Dependências`: Utilize o comando `pip install -r requirements.txt` para instalar as dependências necessárias.

`Coleta de Dados`: Execute o arquivo `get_data` para coletar os dados. Caso necessário, os dados também estão disponíveis no seguinte link: https://drive.google.com/drive/folders/1Xa6QJpGI9sVrfMpXXpxoOfALDOL9NWCU?usp=sharing.

`Execução do Pipeline`: Em seguida, execute o arquivo `pipeline` para realizar as previsões dos modelos.
