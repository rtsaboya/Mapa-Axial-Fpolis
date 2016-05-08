# Mapa Axial Fpolis
Faça o download da pasta completa usando o link "Download ZIP" (ou correspondente em Português).
##Descrição Geral

Mapa axial da Área Conurbada de Florianópolis, incluindo São José, Palhoça, Biguaçu e Florianópolis. Considera barreiras aos veículos (vias com duas pistas, por exemplo, estão representadas por 2 linhas axiais).

Está incluído também um shapefile com as duas medidas mais básicas (Integração e Escolha) calculadas para linhas axiais para o raio global (n) e o raio 3. Pode ser usada diretamente em um SIG para análises iniciais básicas. Análises mais aprofundadas precisam ser recalculadas usando o Depthmap ou a combinação QGIS + Plugin Space Syntaxe Toolkit + Depthmap XNet.

##Créditos

**Mapas axiais de São José e Biguaçu** Bianca Coelho (GranFpolis) em 2015.

**Mapas axiais de Palhoça e Florianópolis** elaborados pelo Grupo de Pesquisa Desenho Urbano e Paisagem (GDUP) - UFSC - 2013: Amanda Carvalho, Gabriel Vespucci, Timóteo Schroeder, Renato Saboya.

**Adaptação para veículos e complementação** por GDUP e Associação dos Municípios da Grande Florianópolis - 2015: Bruna Kronenberger (GDUP), Bianca Coelho (GranFpolis).

Revisão e correções (Florianópolis) por Renato T. de Saboya - 2015-2016.

##Base cartográfica

O mapa foi elaborado sobre as bases cartográficas cadastrais de cada município, posicionadas nas coordenadas corretas no AutoCad. No caso de Florianópolis, a base é a do geoprocessamento da Prefeitura conforme situação em 2012.

A atualização feita em 2015 utilizou a ortofotocarta da SDS a partir de [levantamento realizado entre 2010 e 2012](http://sc.gov.br/mais-sobre-meio-ambiente/384-municipios-da-grande-florianopolis-recebem-o-levantamento-aerofotogrametrico).

##Informações técnicas
###Sistema de projeção
SIRGAS2000 - UTM-22S

Medidas em metros.

## Changelog
v.4.06 - Pequenas adições de linhas axiais feitas no Sambaqui. Uma via relativamente contínua estava desconectada. Seis novas linhas foram criadas. (08/05/2016)

v.4.05 - Pequena correção feita no posicionamento das linhas axiais para adequar-se melhor ao shapefile de lotes de Florianópolis na projeção Sirgas2000. Havia pontos em que as linhas penetravam as barreiras. Linhas axiais de dentro da UFSC, passando pelo estacionamento do CSE, foram removidas. Foi também incluído o shapefile para os unlinks com traços, que pode ser usado no QGIS para indicar linhas que se cruzam no desenho mas não possuem conexão na realidade (por exemplo, viadutos).

v.4.04 - Apesar de o mapa ser mais direcionado aos veículos, o calçadão da Felipe Schmidt foi reconvertido em linha axial pois não parecia uma representação adequada.

v.4.03 - Pequenas correções feitas no mapa axial de Florianópolis - adequação às barreiras ao movimento de veículos e complementação de algumas linhas (ruas) que estavam faltando em Florianópolis.

v.4.02 - Correções feitas a partir do plugin "Space Syntax Toolkit" para os municípios de Palhoça, Biguaçu e São José(Bianca Coelho).

v.4.01 - Correções feitas a partir do plugin "Space Syntax Toolkit" para o Município de Florianópolis (Renato Saboya).