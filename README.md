# README #

## Página inicial: ## 
>index.html


O código a baixo mostra a parte das imagens iniciais que fica passando em carrousel:    
```html
     <header id="myCarousel" class="carousel slide">
        <!-- Indicators -->
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>

        <!-- Wrapper for slides -->
        <div class="carousel-inner">

            <div class="item active">
                <div class="fill" style="background-image:url('imagens/Geography_481847_2560x1440.jpg');"></div>

			</div>
            <div class="item">
                <div class="fill" style="background-image:url('imagens/IN-112_8548_Wallpaper_Pais_2560x1600px_2.jpg');"></div>

			</div>
            <div class="item">
                <div class="fill" style="background-image:url('imagens/nasa-wide-high-resolution-wallpaper-download-images-free-beauty-screen-monitor-1920x1080.jpg');"></div>

            </div>
        </div>

        <!-- Controls -->
        <a class="left carousel-control" href="#myCarousel" data-slide="prev">
            <span class="icon-prev"></span>
        </a>
        <a class="right carousel-control" href="#myCarousel" data-slide="next">
            <span class="icon-next"></span>
        </a>
    </header>
```
Explicação de o que é o lacar e como funciona o laboratório, basta editar o texto.

```html
 <div class="row">
            <div class="col-lg-12">
                <h2 class="page-header">O LACAR</h2>
            </div>
            <div class="">
                <p> </p>
                <ul> </ul>
                <p class="text-justify">O Lacar, Laboratório de Cartografia do Instituto de Geociências da Universidade Federal da Bahia, atua através de grupos de pesquisa desde 1989. Suas atividades se iniciam com trabalhos nas comunidades de Tanque de Senzala, Nova Conquista e Barro Vermelho no distrito de Oliveira dos Campinhos em Sto. Amaro(BA),com o projeto Estudo Ambiental do médio Suba?: Vivenciando práticas ambientais, ligado a Atividade Curricular em Comunidade ACC. Esta, voltada a problemática ambiental na busca de alternativas que venham atenuar a degradação dos ambientes mapeados e a qualidade de vida dos moradores. Neste contexto cria-se espaço para o exercício de cidadania. Na área de ensino foram realizadas duas Oficinas de Cartografia: aplicação das geotecnologias nas geociências em 2009 e 2010, oferecidas a 300 alunos de graduação/IGEO, ministradas por bolsistas do Lacar. Com o Projeto Popularização da cartografia e suas novas tecnologias na escola pública em parceria com o Colégio Dona Mora Guimarães e financiado pela Fapesb, envolve diretamente 360 alunos e mil indiretos, entre 2011 e 2013. Os resultados são apresentados em eventos científicos.</p>
            </div>
```



>Neste trecho é onde será modificada as imagens das  participações em eventos
```html
 <div class="row">
            <div class="col-lg-12">
                <h2 class="page-header">Participação em eventos</h2>
            </div>
            <div class="col-md-3 col-sm-5">
                <a href="portfolio-item.html">
                    <img src="imagens/IMG-032.jpg" alt="" width="300" class="img-responsive img-portfolio img-hover">
                </a>
            </div>
            <div class="col-md-3 col-sm-5">
                <a href="portfolio-item.html">
                    <img src="imagens/IMG-040.jpg" alt="" width="295" class="img-responsive img-portfolio img-hover">
                </a>
            </div>
            <div class="col-md-3 col-sm-5">
                <a href="portfolio-item.html">
                    <img src="imagens/IMG-041.jpg" alt="" width="300" class="img-responsive img-portfolio img-hover">
                </a>
            </div>
            <div class="col-md-3 col-sm-5">
                <a href="portfolio-item.html">
                    <img src="imagens/IMG-043.jpg" alt="" width="300" class="img-responsive img-portfolio img-hover">
                </a>
            </div>


        </div>
```

## Página de apresentação: ## 
>apresentacao.html

Nesta página basta mudar o conteúdo, onde estar escrito: <b>Aqui vai a descrição</b>.
```html
 <div class="tab-content">
            <div role="tabpanel" class="tab-pane active" id="home">
               <b>Aqui vai ficar a descri��o da Apresenta��o <br></b>
                Ao contr�rio do que se acredita, Lorem Ipsum n�o � simplesmente um texto rand�mico. Com mais de 2000 anos, suas ra�zes podem ser encontradas em uma obra de literatura latina cl�ssica datada de 45 AC. Richard McClintock, um professor de latim do Hampden-Sydney College na Virginia, pesquisou uma das mais obscuras palavras em latim, consectetur, oriunda de uma passagem de Lorem Ipsum, e, procurando por entre cita��es da palavra na literatura cl�ssica, descobriu a sua indubit�vel origem. Lorem Ipsum vem das se��es 1.10.32 e 1.10.33 do "de Finibus Bonorum et Malorum" (Os Extremos do Bem e do Mal), de C�cero, escrito em 45 AC. Este livro � um tratado de teoria da �tica muito popular na �poca da Renascen�a. A primeira linha de Lorem Ipsum, "Lorem Ipsum dolor sit amet..." vem de uma linha na se��o 1.10.32.

                O trecho padr�o original de Lorem Ipsum, usado desde o s�culo XVI, est� reproduzido abaixo para os interessados. Se��es 1.10.32 e 1.10.33 de "de Finibus Bonorum et Malorum" de Cicero tamb�m foram reproduzidas abaixo em sua forma exata original, acompanhada das vers�es para o ingl�s da tradu��o feita por H. Rackham em 1914.
            </div>
            <div role="tabpanel" class="tab-pane" id="profile">
                <b>Aqui vai ficar a descri��o do Objetivo <br></b>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris semper pulvinar enim. Proin tristique lobortis purus sit amet faucibus. Proin faucibus, purus a aliquet finibus, tellus dui feugiat velit, vel egestas mauris sem sed tellus. Vivamus pretium sem eget est dapibus scelerisque. Morbi consectetur eros eu lacus tincidunt vulputate. Donec at blandit nibh, sit amet efficitur tortor. Quisque tincidunt bibendum dolor, quis scelerisque lacus bibendum eget. Phasellus non ligula tincidunt, pretium orci eget, vulputate augue. Donec pretium tincidunt risus, vitae interdum leo facilisis ac.

                Donec interdum leo nec leo finibus lacinia. Sed rutrum dignissim nibh at mattis. Morbi sagittis lacus est, a malesuada dolor pulvinar vitae. Cras vitae ipsum pretium, varius lacus eu, fermentum sapien. Nulla ultricies massa libero, non vulputate ex tincidunt id. Ut pellentesque vel sem vitae egestas. Fusce mi turpis, elementum sit amet aliquam id, pretium sagittis risus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Suspendisse libero ipsum, sollicitudin eu nibh facilisis, pulvinar tincidunt nibh. Nam suscipit varius purus, accumsan vehicula magna efficitur nec. Nullam ullamcorper aliquam dui. Morbi tincidunt dolor non dictum fermentum. Ut semper ac justo ut efficitur. Donec vel sem in diam posuere posuere. In eget ligula nisi. Donec eget dui ac enim scelerisque pretium at sed lorem.
            </div>
            <div role="tabpanel" class="tab-pane" id="messages">
                <b>Aqui vai ficar a descri��o da Miss�o <br></b>
                Duis quis aliquet ex, fringilla efficitur orci. Donec urna diam, congue non suscipit ut, accumsan eget velit. Mauris scelerisque mauris ante, vitae vestibulum lectus auctor ut. Sed tristique nisl a erat placerat, eget gravida augue molestie. Maecenas sit amet vulputate lacus, eu vehicula lorem. Cras non rutrum purus. Sed purus justo, lobortis sed cursus quis, malesuada ac ante. Integer nulla mi, posuere in accumsan sit amet, posuere id risus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Vivamus vel volutpat felis, eget dignissim ante. Aliquam efficitur metus sed tellus auctor pharetra.

                Praesent semper ipsum pharetra congue sagittis. Ut bibendum ante mi, ut egestas turpis scelerisque eget. Duis elit metus, accumsan vitae dapibus nec, posuere a metus. Nam lobortis, erat et aliquet congue, metus sapien laoreet nisi, et congue risus ipsum id erat. In rutrum fringilla nibh, sit amet blandit nisi sollicitudin ut. Praesent aliquam, velit ut rhoncus porttitor, turpis mauris pretium risus, eget faucibus urna eros eget nunc. Morbi imperdiet vel nisi ut euismod. Mauris pretium urna vel ante fringilla bibendum. Suspendisse mi enim, vehicula sit amet magna at, porta efficitur odio. Vestibulum vel mauris ex. Suspendisse scelerisque arcu nec nisi lacinia efficitur ut vitae odio. Phasellus auctor euismod ex, at blandit lacus congue in. Curabitur enim tellus, luctus ut mauris eu, facilisis volutpat enim. Nulla id placerat mi. Ut sed orci in turpis sagittis varius molestie nec lorem. Phasellus lacinia ipsum in auctor consectetur.
            </div>
            <div role="tabpanel" class="tab-pane" id="infra">
                <b>Aqui vai ficar as imagens <br></b>

            </div>
            <div role="tabpanel" class="tab-pane" id="settings">...</div>
        </div>
```

## Página de artigos,congresso,outros: ## 

> * artigos.html
> * eventos.html 
> * Outras-publicações.html


Para adicionar um artigo basta copiar o código abaixo, e modificar os nomes e imagens que julgar necessário:
```html
 <div class="row">
            <div class="col-md-5">
                <a href="portfolio-item.html">
                    <img class="img-responsive img-hover" src="imagens/mapa_turistico_ssa.jpg" alt="">
                </a>
            </div>
            <div class="col-md-5">
                <h3>Mapa Turístico da Cidade de Salvador/BA</h3>
                <h4></h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laudantium veniam exercitationem expedita laborum at voluptate. Labore, voluptates totam at aut nemo deserunt rem magni pariatur quos perspiciatis atque eveniet unde.</p>
                <a class="btn btn-primary" href="publica/mapa_turistico_ssa.pdf" target="_blank">Visualizar- PDF</i></a>
            </div>
        </div>
```

## Página de Projetos ## 

> * concluidos.html
> * andamento.html



Para adicionar um <b>PROJETO</b> basta copiar o código abaixo, e escrever a descrição onde diz <b>AQUI VAI A DESCRIÇÃO</b>
```html
 <div class="panel panel-default">
                <div class="panel-heading" role="tab" id="headingOne">
                    <h4 class="panel-title">
                        <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                            <i class="more-less glyphicon glyphicon-plus"></i>

                        </a>
                    </h4>
                </div>
                <div id="collapseOne" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne">
                    <div class="panel-body">
                        <b>Aqui vem a descrição do projeto <br></b>
                        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
                    </div>
                </div>
            </div>
```

## Página de Cursos ## 

> *  ` extensao.html `
> * ` Outros_cursos.html `
> * ` mini.html `



Para adicionar um <b>CURSO</b> basta copiar o código abaixo, e escrever a descrição onde diz <b>COLOQUE A DESCRIÇÃO DO CURSO AQUI</b>.

```html
 <div class="col-md-4 img-portfolio">
                <a href="portfolio-item.html">
                    <img class="img-responsive img-hover" src="http://placehold.it/700x400" alt="">
                </a>
                <h3>
                    <a href="portfolio-item.html">Nome do Curso (1)</a>
                </h3>
                <p><b>Coloque a descrição do Curso aqui</b>,<br>consectetur adipiscing elit. Nam viverra euismod odio, gravida pellentesque urna varius vitae.</p>
            </div>
```
Para adicionar a imagem basta colocar o caminho da imagem no atributo ` src ` como estar abaixo:

> ``` <img class="img-responsive img-hover" src="http://placehold.it/700x400" alt=""> ```
