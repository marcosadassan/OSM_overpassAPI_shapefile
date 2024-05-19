# Obter Dados Geográficos com OpenStreetMap (OSM) usando Python

Este projeto utiliza a Overpass API para acessar os dados do OpenStreetMap (OSM) e salvar em shapefile. O script Python fornecido realiza as seguintes operações:

1. Define a área de interesse através de coordenadas de latitude e longitude.
2. Realiza uma consulta à Overpass API para obter dados de rodovias dentro da área de interesse.
3. Cria um GeoJSON com os resultados da consulta.
4. Converte o GeoJSON para um GeoDataFrame.
5. Expande as tags em colunas no GeoDataFrame.
6. Salva os dados como um Shapefile.
7. Cria um mapa interativo com os dados utilizando a biblioteca Folium.

## Como usar o script

Primeiro, certifique-se de que todas as bibliotecas necessárias estão instaladas, listadas em `requirements.txt`.

O arquivo `OSM_get_raw_data.ipynb` contem um notebook com os comandos.

O script irá salvar os dados como um Shapefile na pasta 'output'. Além disso, ele irá gerar um mapa interativo que será exibido na sua janela do navegador.

## Visualizando o Mapa

O mapa gerado pelo script é interativo e será aberto em uma nova janela do navegador. Ele utiliza a biblioteca Folium para criar o mapa e exibir os dados. As rodovias são coloridas de acordo com o seu tipo: vermelho para rodovias primárias, azul para rodovias secundárias e cinza para todos os outros tipos de rodovias.

## Contribuições

Contribuições para este projeto são bem-vindas! Se você encontrar um bug ou tiver uma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Links Úteis

- [Artigo base no LinkedIn](https://www.linkedin.com/in/marcosaadassan/)
- [Site oficial do OpenStreetMap](https://www.openstreetmap.org/)
- [Como contribuir para o OpenStreetMap](http://openstreetmap.pt/como-participar/)
- [Doações para a Fundação OpenStreetMap](https://supporting.openstreetmap.org/donate/)