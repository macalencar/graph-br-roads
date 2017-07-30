# graph-br-roads
Grafo não dirigido e ponderado das capitais brasileiras conectadas às capitais adjacentes por rodovias.

Nós(Capitais): 27
Arestas(Rodovias): 44
Pesos(Distâncias): Em Quilômetros(km)

<p>As arestas/pesos foram obtidas com auxílio da ferramenta <i><b>Google Maps</b>(https://www.google.com.br/maps/)</i> onde, para cada capital Brasileira, buscou-se (na ferramenta) a rota mais curta até as capitais dos estados adjacentes.</p>

Cada nó pelo nome da capital seguido da sigla do estado: <CAPT>-<UF><br>
Os nomes contem caracteres especiais e espaços.<br>
Cada linha do arquivo representa uma rodovia e contém no seguinte formato: <b>ORGIGEM;DESTINO;DISTÂNCIA;</b><br>
Ex.:
Rio Branco-AC;Manaus-AM;1399;
Rio de Janeiro-RJ;São Paulo-SP;447;
Brasília-DF;Belo Horizonte-MG;734;
...

OBS.: A cidade de Macapá-AP possui apenas uma capital adjacente, Belém-PA, porém não há rodovias que conectem as cidade, logo, assummiu o custo da ditância direta entre as cidade acrescido de 1000, ou seja 3290km:
*Macapá-AP;Belém-PA;3290;

