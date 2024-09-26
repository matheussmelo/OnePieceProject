# Projeto de Análise de Dados de One Piece

## Bem-vindo! 

![](luffy.jpg)


Esse é o repositório onde estão todos os códigos criados para a análise. 

Os dados referentes ao **número**, **título**, **quantidade de votos** e **avaliação média** de cada episódio foram extraído com WebScrapping pelo script ['1. WebScrapping.ipynb'](https://github.com/matheussmelo/OnePieceProject/blob/main/1.%20WebScrapping.ipynb), utilizando BeautifulSoup e Selenium, do site [IMDb](https://www.imdb.com/title/tt0388629/episodes/?ref_=tt_eps_sm). Após o WebScrapping, foi gerada a planilha ['episodes.xlsx'](https://github.com/matheussmelo/OnePieceProject/blob/main/episodes.xlsx) para guardar os dados dos episódios.

Com informações adicionais do site da [IGN](https://br.ign.com/one-piece-2/95364/feature/one-piece-guia-de-sagas-arcos-e-episodios-fillers), complementei os dados pelo próprio Excel com o *tipo* e *arco* de cada episódio, salvando em ['episodes_final.xlsx'](https://github.com/matheussmelo/OnePieceProject/blob/main/episodes_final.xlsx).

A análise completa pode ser vista no script ['2. EDA.ipynb'](https://github.com/matheussmelo/OnePieceProject/blob/main/2.%20EDA.ipynb). O foco principal foi foi entender e explorar padrões e/ou características relacionadas à quantidade de votos e a avaliação média dos telespectadores para os diferentes tipos de episódio e arcos.

As análises foram inteiramente feitas com **Python**, **Jupyter Notebooks** e **Plotly**.

#### Resumo das análises:

- Considerando tipos de episódio:
    - O anime possui 1117 episódios e uma esmagadora porcentagem dos episódios apresenta conteúdo relevante para a narrativa principal do anime (92% dos episódios). 
    - Episódios canônicos têm maiores votações e avaliações em comparação aos fillers e semi-fillers. Isso é esperado nos animes, pois episódios canônicos são compostos inteiramente pela narrativa principal e atraem mais os fãs.
    - Há uma enorme quantidade de outliers de votação de episódios canônicos, que se destacaram por conta da quantidade de telespectadores que votaram esporadicamente.
    - 14 episódios canônicos foram avaliados com a nota máxima, equivalente à nota 9.7. Todos os episódios são emblemáticos, pertencentes aos arcos de Thriller Bark, Arquipélago de Sabaody, Marineford, Whole Cake, País de Wano e Egghead.  
    - O episódio 1062 além de ter a avaliação máxima, também possui a quantidade de votos mais alta de todas. A quantidade de votos equivale à aproximadamente 62x a mediana dos episódios canônicos.
    - Vale notar que, Egghead é o último arco que ainda está em lançamento e já possui avaliação 9.7 cinco vezes, dando a entender que os fãs estão gostando.
    - O arco de Egghead, ainda em lançamento, já obteve avaliação 9.7 cinco vezes, sugerindo boa recepção dos fãs ao decorrer atual do anime.
    - Episódios Canônicos e Semi-Filler apresentam uma forte correlação positiva entre quantidade de votos e avaliações.
    - Os episódios relevantes pra história do anime apresentam uma tendência de aumento na quantidade de votos e avaliações, além de apresentar picos mais frequentes e altos nos valores nos últimos arcos. Isso sugere que a qualidade dos episódios e/ou da história pode estar melhorando e resultando nesses picos, pois os telespectadores estão gostando e estão votando positivamente nos episódios de destaque.
    - Enquanto isso, fillers sugerem estar ocorrendo com menor frequência, tendo maiores intervalos entre seus lançamentos.

- Considerando os arcos:
    - O anime possui 50 arco, onde os maiores são: País de Wano (192 episódios), Dressrosa (118 episódios) e Whole Cake (95 episódios). Dentre os 50, 33 (66% do total) apresentam conteúdo relevante pra narrativa princiapal, compostos por episódios canônicos, canônicos/semi-filler, canônicos/filler e canônicos/semi-filler/filler. Enquanto isso, há 13 arcos Filler (26% do total).
    - O arco com a maior quantidade de votos é País de Wano com 1.045.199 votos. Depois dele, há Marineford com 228.411 votos e Whole Cake com 202.555 votos. Já sobre a avaliação mediana de cada arco, Marineford foi o melhor com nota 9.2, seguido de País de Wano com 8.7 e Egghead com 8.6. Notou-se que, arcos menos votados e pior avaliados são arcos filler ou semi-filler.
    - Observou-se uma forte correlação entre a quantidade de episódios e a soma total de votos por arco, com coeficiente equivalente à 88.6%. Isso sugere que, o caso do arco de País de Wano ter muitos episódios e também muitos votos não é algo exclusivo. Sobre a quantidade de episódios e a avaliação mediana por arco, houve uma moderada correlação, com coeficiente igual a 69%. 
    - Por fim, foi visto uma forte correlação entre a quantidade total de votos e a avaliação mediana por arco, equivalente à 86.2%.

## Espero que goste!

Caso tenha interesse, aqui estão **minhas redes de contato**:

Linkedin: https://www.linkedin.com/in/matheussmelo1702/

E-mail: matheusmelo1702@gmail.com 
