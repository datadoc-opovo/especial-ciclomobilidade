# Malha cicloviária para quem?

A menos de um ano para completar uma década, a extensão cicloviária de Fortaleza se estabelece como uma das mais longas do País. Porém, ainda com desigualdades de distribuição, problemas de fiscalização e manutenção da infraestrutura.

Portanto, é fundamental que o jornalismo apure, investigue e busque respostas para questões que permeiam políticas públicas, tais como seu orçamento, execução e distribuição, afinal essas ações impactam diretamente a sociedade. É controle social. 

Neste repositório, estão disponíveis os dados utilizados, os códigos e os arquivos gerados para a série de reportagens "Malha cicloviária para quem?", que aborda aspectos da infraestrutura voltada para ciclistas nas ruas e avenidas da capital cearense. 

As matérias, produzidas pela Central de Jornalismo de Dados do Jornal **O POVO** (DATADOC), começaram a ser publicadas no dia 19 de setembro de 2022, com a divulgação do primeiro episódio no O POVO Mais, plataforma multistreaming do Jornal **O POVO**.


| EP | Data de publicação | Reportagem |Bases utilizadas | Arquivos gerados | 
| -------- | -------- | -------- | -------- | -------- |
| 01     | 19/09/2022     | [Na Capital, apenas 7% das vias dos bairros com menor IDH têm malha cicloviária](https://mais.opovo.com.br/interativos/cicloviaria-fortaleza/episodio-01.php)     | [Pasta com as bases originais](https://github.com/datadoc-opovo/especial-ciclomobilidade/tree/main/episodio-1/bases_originais)     | [Datasets criados a partir das análises](https://github.com/datadoc-opovo/especial-ciclomobilidade/tree/main/episodio-1/arquivos_gerados)     |
| 02     | Previsto para 26/09/2022      | Em breve     | Em breve     | Em breve     |

---

## EPISÓDIO 1

### Nas regiões de maior desenvolvimento humano de Fortaleza, cerca de 20% do total de ruas e avenidas têm malha cicloviária, enquanto essa infraestrutura corresponde a apenas 6,6% das vias dos bairros de menor IDH da Capital

Há décadas, a população de Fortaleza — principalmente trabalhadores de bairros de baixa renda — arrisca a vida ao deslocar-se cotidianamente de bicicleta e disputar o espaço da rua com automóveis. Assim, a demanda por infraestrutura cicloviária pela Cidade não é recente.

Em 2013, os quilômetros de ciclovias e ciclofaixas pintados pela Capital começaram a aumentar, e a política de mobilidade, com o incentivo ao uso da bicicleta, passou a chamar atenção nacionalmente.

Mas como está distribuída a malha cicloviária de Fortaleza? O principal achado da análise deste primeiro episódio aponta para a concentração da infraestrutura cicloviária em bairros de Índice de Desenvolvimento Humano (IDH) médio, alto e muito alto, quando vista proporcionalmente à malha viária de cada bairro.

Para chegar a esse resultado, a Central DATADOC analisou a proporção da malha cicloviária em relação à malha viária de cada bairro da Capital. Em seguida, os bairros foram agrupados por faixa de IDH.

![Gráfico da evolução temporal da proporção de ruas e avenidas de Fortaleza com sistema cicloviário, por faixa de IDH](/imagem/grafico_markdown.png)

### Fonte e coleta de dados:

- [Malha cicloviária de Fortaleza](https://www.google.com/maps/d/u/1/viewer?mid=1eqNX-fl3ENPC8_1tqzbRDYZFQmA&ll=-3.7712495577429186%2C-38.50590144121097&z=12);
- [Bairros de Fortaleza - 2019](https://mapas.fortaleza.ce.gov.br/);
- [Eixos viários de Fortaleza](https://mapas.fortaleza.ce.gov.br/);
- [Pavimentação das vias de Fortaleza](https://mapas.fortaleza.ce.gov.br/);

### Arquivos gerados

***Dataframes***

- `dataset_bairros_eixo_cicloviario_idh.csv`: Base com informações sobre infraestrutura cicloviária do bairro com a respectiva classificação do Índice de Desenvolvimento Humano (IDH);
- `dataset_bairros_eixo_cicloviario_idh.geojson`: Mesma base anterior, mas em arquivo geojson;
- `malha_cicloviaria_idh_ano.csv`: Extensão da malha cicloviária por ano;
- `pavimentacao_por_idh.csv`: Pavimentação das vias pela respectiva classificação de IDH dos bairros.

***Visualizações***

- Mapbox com exploração visual de dados sobre a malha cicloviária dos bairros de Fortaleza
- [Evolução temporal da proporção das ruas e avenidas de Fortaleza-CE contempladas no sistema cicloviário, por faixa de IDH](https://public.flourish.studio/visualisation/10533922/)
- [Proporção Sem Pavimentação dos eixos viários de Fortaleza, por faixa de IDH](https://public.flourish.studio/visualisation/10533526/)

---

## EPISÓDIO 2

*Em breve*

---

### Como utilizar:

Para executar o notebook com a coleta e processamento dos dados, é necessário um ambiente com *Python3* e dependências que podem ser instaladas via [Pip](https://pypi.org/project/pip/):

```
!pip install googlemaps
!pip install geopandas
!pip install unidecode
```

---

### A central DATADOC

A Central de Jornalismo de Dados do O POVO (DATADOC) alia tecnologia e técnicas diversas de análises de dados para produzir um jornalismo de precisão para que você forme sua opinião com segurança. Nosso objetivo é fazer com que todos tenham acesso aos dados utilizados nas notícias que produzimos.

A DATADOC é composta por uma equipe de três jornalistas (sendo uma infografista), uma desenvolvedora front-end e um cientista da computação que coletam, enriquecem e disponibilizam as bases e códigos de cada reportagem para um jornalismo transparente e baseado em evidências.

---

#### 🔥📰👩🏻‍💻 Se você gostou do nosso material, apoie assinando o OP+ e acompanhando o nosso trabalho.

#### 📝📨 Para feedback, dúvidas ou sugestões: [datadoc@opovodigital.com](mailto:datadoc@opovodigital.com)

---

🦠💉 Confira também outras produções recentes da central DATADOC: A matéria  ***Covid-19: Uma criança de 0 a 4 anos de idade morreu por semana no Ceará*** mostrou como a doença causada pelo novo coronavírus impactou os menores de 5 anos, até então os únicos sem acesso à vacinação contra a Covid-19, desde o primeiro óbito por Covid-19 registrado no Ceará. A matéria foi feita em parceria com o núcleo de Cotidiano do Jornal O POVO e está [disponível no O POVO+](https://mais.opovo.com.br/reportagens-especiais/2022/07/29/covid-19-uma-crianca-de-0-a-4-anos-de-idade-morreu-por-semana-no-ceara.html).
