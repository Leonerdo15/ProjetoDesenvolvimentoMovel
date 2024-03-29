# Ultimate Lisbon Guide

**IADE - Faculdade de Design, Tecnologia e Comunicação**

Engenharia Informática — 3.º semestre

Felipe Campelo Sabbado (20191012); Leonardo Lage (20200859)

Projeto Multidisciplinar:
- Projeto de Desenvolvimento Mobile (Pedro Rosa);
- Programação Mobile (João Dias);
- Programação Orientada por Objetos (Miguel Bugalho);
- Bases de Dados (Miguel Boavida);
- Competências Comunicacionais (Alexandra Santos,);
- Matemática Discreta (Rodolfo Bendoyro)

1 de outubro de 2021

## **Resumo**
Aplicação para criação de rotas entre pontos turísticos que irá auxiliar o utilizador no planeamento das suas férias com indicação de locais e informações sobre distâncias, preços, indicação etária, tempo médio de visitação e tempo total do trajeto para melhorar a experiência e o aproveitamento do período de lazer. Também possui a vantagem de indicar os locais conforme o perfil de interesse do utilizador.

**Palavras-chave:** turismo; rotas; caminhos; pontos-turísticos; atrações; Lisboa; restauração; hotelaria.

## **Contexto**
Quando estamos de férias o que menos desejamos é preocupações. Atualmente, cada vez mais pessoas têm períodos reduzidos para passeios, por isso querem aproveitar ao máximo o seu momento de lazer. E a experiência turística pode ser por vezes insatisfatória quando não encontramos os locais desejados ou eles estão fechados, perdemos tempo nas rotas ou acabamos por percorrer longas distâncias a pé por não conhecermos a região. Por vezes os locais turísticos têm-se que pagar e convêm saber o valor. Outras vezes é preciso saber se a atração é indicada para crianças ou se não é demasiado cara. Também é importante a possibilidade de descobrirmos atrações não tão famosas, mas igualmente gratificantes para que as férias se transformem em experiências únicas.

## **Objetivos**
Esta ferramenta visa facilitar a vida de quem quer conhecer uma cidade sem ficar perdido a procurar os pontos turísticos, sem perder tempo entre trajetos ineficientes e agilizar o processo de decisão dos locais de visitação. Permitirá organizar e planear o trajeto para poupar tempo em deslocamentos e aproveitar melhor o passeio e os pontos turísticos escolhidos. Além disso, a aplicação indicará locais próximos aos pontos de interesse do utilizador que poderá alterar o roteiro em tempo real, incluindo ou excluindo pontos turísticos e, assim, permitindo com que ele conheça e desfrute de novas experiências, tendo em conta os seus gostos e preferências. O utilizador terá informações detalhadas sobre o seu trajeto e sobre as atrações escolhidas, permitindo decisões melhores e mais embasadas.

## **Público-alvo**
Pessoas (turistas), estrangeiras ou não, que desejam conhecer atrações sem ficar perdidas a procurar os locais ou que gostam de se planear.

## **Descrição**
Aplicação que cria rotas entre atrações turísticas escolhidas pelo utilizador com o melhor caminho entre elas. Ao se cadastrar, o utilizador criará um perfil indicando as categorias favoritas das atrações e, com isso, terá indicação de locais semelhantes quando for criar o seu roteiro. Em seguida será possível criar o trajeto, selecionando os locais que deseja visitar e a quantidade e idade de pessoas que irão realizar o passeio. Através de uma busca (por nome ou características) serão exibidos os locais com uma imagem ilustrativa e as informações relevantes (descrição, preço, tempo médio de visitação, indicação etária, entre outros). Após selecionar os pontos turísticos a aplicação criará a rota e exibirá um ecrã com um mapa indicando o caminho a ser percorrido e informações do percurso, tais como: tempo, distância e preço.
A aplicação será desenvolvida inicialmente para a cidade de Lisboa, podendo, caso haja disponibilidade, ser ampliada para outras cidades ou mesmo para Portugal inteira.

## **Pesquisa de mercado**
Nenhuma das aplicações pesquisadas tem a possibilidade de criar rotas com os pontos turísticos escolhidos pelo utilizador, função esta a ideia principal deste projeto.

### **Lisbon City Guides, Offline Maps, Tours and Hotels**
_Prós:_ Entre todas as ‘apps’ que utilizamos esta tem a interface mais fácil de utilizar e mais bem organizada. Quando clicamos num monumento em específico podemos ver imagens, uma breve descrição, outros pontos turísticos perto ou similares. É a única, dentre as analisadas, que permite ao utilizador escolher como ponto de partida a sua localização atual ou o primeiro local da rota.<br/>
_Contras:_ As rotas são criadas aleatoriamente e o utilizador só pode escolher como parâmetro de criação o tempo de duração rota. Quando clicamos num monumento em específico podemos ver outros pontos turísticos próximos e semelhantes, porém não podemos adicionar à rota criada.

### **Guia de Lisboa de Civitatis**
_Prós:_ Indicação de um roteiro para visitar Lisboa em 48 horas. Possui bastantes informações sobre as atrações turísticas. Mostra locais onde se pode comprar produtos nacionais como, pastéis, vinhos, queijos, entre outros. Também possui uma aba de atividades.<br/>
_Contras:_ Não permite a criação de um roteiro próprio. Possui poucos pontos turísticos cadastrados por isso tem pouca liberdade de escolha. Sem indicações de atrações semelhantes conforme o perfil do utilizador. Apenas sete das opções que estão na aba de atividades são grátis

### **Lisbon Travel Guide (Ulmon):**
_Prós:_ A primeira vez que utilizamos tem um pequeno tutorial para explicar como a ‘app’ funciona. Tem um vasta escolha de pontos turísticos organizados por recomendações como, lisbon’s best shopping tips, Recommended: “Feiras”, Recommended: Beaches, etc.<br/>
_Contras:_ Pouca informação sobre os monumentos, por exemplo, na página do Mosteiro dos Jerónimos só nos é visível um número de telefone, e-mail e fotos.

## **Guiões de teste**
**Caso 1 - Processo de criação de uma rota:** A página inicial mostra um mapa com marcadores a dizer a posição do utilizador e dos pontos turísticos da cidade, com cores diferentes para cada caso. Na parte superior esquerda haverá um botão que abrirá um menu lateral com algumas opções, dentre as quais a de “Criar Rota”. Ao ser selecionada, esta opção irá abrir outra página onde será possível visualizar uma barra de pesquisa, um botão de filtros e uma lista com atrações indicadas segundo o perfil do utilizador. Cada uma das atrações exibidas na tela possuirá uma foto, uma breve descrição e um botão que poderá ser de incluir, se o local ainda não tiver sido selecionado, ou de excluir, caso contrário. A barra de pesquisa, a medida em que as palavras forem sendo digitadas, filtra a lista de atrações. O botão de filtro terá opções de categoria, preço, distância e classificação etária. Quando clicamos num ponto turístico somos redirecionados para outra página onde poderemos ver imagens, uma breve sinopse, horários, preço e outras atrações próximas. Após selecionar os locais o utilizador pressiona um botão para que a aplicação crie uma rota com o melhor caminho que será desenhada no mapa. Após isso também será exibido um campo com informações importantes do trajeto tais como a distância total, o tempo médio a ser percorrido e o valor total das atrações. E se a pessoa quiser pode começar a sua viagem.

**Caso 2 - Alteração dos pontos turísticos e botão de Pausa:** Durante o passeio, será possível visualizar outros pontos turísticos próximos ao local que o utilizador está a visitar (o raio de indicação pode ser alterado) e incluir ou excluir locais com atualização, em tempo real, da rota com o melhor caminho. Neste mesmo ecrã também existirá um botão para fazer uma pausa para comer ou ir à casa de banho com a aplicação a mostrar locais próximos.

**Caso 3 - Pesquisa por rotas prontas:** No menu da página inicial existirá um botão em que poderá se pesquisar rotas prontas, enviadas por outros utilizadores, para os casos em que não se queira criar a própria rota.

## **Pitch:** 
**Link para o vídeo** - https://youtu.be/DAEeR5r4aHI
