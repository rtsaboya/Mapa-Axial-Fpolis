## Criação dos unlinks
Os unlinks são indicações para o Depthmap sobre quais intersecções não devem ser consideradas. No caso de um viaduto, por exemplo, é interessante indicar que a linha axial de baixo não é conectada com a linha que passa por cima.

No Depthmap isso pode ser criado manualmente usando o botão unlink ou, nos casos mais complexos, eles podem ser criados a partir de um arquivo de texto contendo as coordenadas de cada intersecção a ser ignorada. Esse arquivo texto pode ser baixado nesta página, e os procedimentos a serem seguidos são:

1. No Depthmap, criar um novo arquivo;
1. Importar o DXF com linhas axiais, **sem os unlinks**;
1. Map > Convert drawing map > Axial Map;
1. Map > Import... > Selecionar arquivo de texto fornecido nesta página com os unlinks;
1. Clicar em "Axial Map" no painel à esquerda para ativar novamente o mapa axial (ele deve ficar colorido);
1. Tools > /Axial ... > Convert Data Map Points to Unlinks;
1. Selecionar o nome do arquivo de unlinks na caixa de diálogo;
1. Ao final, checar através do número de conectividade das linhas envolvidas se a conexão com a linha de cima foi realmente removida.