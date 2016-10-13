HTML5 Boilerplate
===================


Introdução
-------------

O HTML5 Boilerplate é um conjunto de arquivos de código aberto, disponível para download que fornecem uma base para criação de qualquer site. O uso do template te permite ganhar velocidade e segurança no desenvolvimento do seu projeto.

O template tem bastante aceitação, desde desenvolvedores iniciantes até os mais experientes, pois fornece uma base front-end completa para codificação de um site rápido e robusto em HTML5. Existe uma opção simplificada que é mais leve e uma outra opção personalizada, onde você poderá selecionar o conjunto de funcionalidades que melhor irá atendê-lo.

Nos últimos anos observou-se que havia muita dependência do Bootstrap, dessa forma surgiram muitos sites semelhantes. O Boilerplate, por sua vez, tem maior flexibilidade, assim, você que possui um conhecimento mais avançado está livre para desenvolver aplicações que atendam melhor às suas necessidades. O Boilerplate foi construído por profissionais da indústria de software, porém, está disponível para toda a comunidade de desenvolvedores. Quando baixado, fornece ao desenvolvedor toda a documentação e licença em formato Markdown duas imagens de espaço reservado, dois arquivos HTML, alguns JavaScript e alguns arquivos de configuração do servidor.


Autores
-------------
O HTML5 Boilerplate foi criado por Paul Irish e Divya Manian, e é um projeto de código aberto que é perfeito para a criação de sites cross-browser que funcionam com navegadores mais antigos, sendo HTML5 pronto.

Paul Irish é desenvolvedor front-end da Google, trabalhando com o Google Chrome, focado na equipe de desenvolvimento Tooling. Segundo ele, o projeto para o HTML5 Boilerplate se arrastou durante dois ano e meio, sendo ativado e reativado neste período, ate que enfim, em meados de 2011 o projeto saiu do papel e foi lançado para a comunidade desenvolvedora.

Divya Manian estudou Engenharia de Computação, em Cingapura. Ela abandonou sua confortável primeira escolha de carreira como desenvolvedor de driver de dispositivo da Motorola para se tornar designer de in-house em uma inicialização e depois ir freelance. No meio de uma crise trimestre de vida, ela decidiu buscar tecnologias web com devoção sincera, levando a projectos de colaboração, tais como HTML5 Boilerplate.

[![](https://4.bp.blogspot.com/-CAgytPaoAho/V_7aHnc4XfI/AAAAAAAAB_A/Glxsjq_vh5wm5lvcI9pyMhy00bwgI5gxQCLcB/s1600/Autor1.jpg)]()

Paul Irish
Front-end Developer

[![](https://3.bp.blogspot.com/-xVza0ScoYM4/V_7aRcgImtI/AAAAAAAAB_s/BJipJE_Pns48DGtKJnv5ZgLIr6C4yAnSQCLcB/s320/Autora.jpg)]()

Divya Manian


Frameworks e Ferramentas
-------------
HTML5 Boilerplate inclui ferramentas muito úteis, as principais são Initializr, Modernizr, e JQuery. Mas também existem outras de menor importância como um Profiling JQuery, Código Google Analytics e funções Javascript para login.

Initializr é um gerador de código baseado no Boilerplate para iniciar um projeto em HTML5. O gerador permite criar um projeto rápido e confiável, porém com um código mais leve, pois não engloba ferramentas raramente usadas com HTML5. Initializr fornece também diversas opções para customizar os templates.

O Initializr permite gerar conteúdos para auxiliar na construção das páginas. Ele também inclui a biblioteca jQuery, uma biblioteca javascript essencial, disponível em forma minimizada ou não.
O arquivo HTML5shiv é responsável por tratar o problema da compatibilidade com versões anteriores do Internet Explorer 8. As novas tags do HTML5 são reconhecidas através da função createElement():

```
document.createElement("header");
```

O Modernizr é um arquivo javascript que dá suporte às funcionalidades HTML5 e CSS3. Ele cria um objeto para cada funcionalidade onde identifica se ela é compatível ou não com o navegador. 

```
if (Modernizr.geolocation){
  // A geolocalização é suportada
}
else {
  // A geolocalização não é suportada
}
```

Ele permite que sejam utilizados estilos alternativos a funcionalidades onde algumas propriedades de CSS3 não sejam compatíveis, adicionando classes CSS condicionais ao HTML.

```
.multiplebgs header {
  /* Backgrounds múltiplos são suportados */
}
.no-multiplebgs header {
  /* Backgrounds múltiplos não são suportados */
}
```

O Modernizr inclui o HTML5shiv, porém, diferente deste, ele é apenas uma ferramenta muito ampla, escolhida por padrão para suporte de compatibilidade do Initializr, ou seja, ele não inclui uma característica faltante, como o HTML5shiv faz com tags.


Evolução
-------------
O HTML5 Boilerplate possui várias releases desde a sua primeira versão lançada, em 2011, a saber, a versão **v1.0** que trouxe as funcionalidades descritas abaixo, segundo o site https://github.com/h5bp/html5-boilerplate/releases?after=v4.0.1, acessado em 09 de outubro de 2016:
- Reescrever o script de construção para torná-lo mais personalizável e flexível.
- Numerosas melhorias .htaccess (incluindo a documentação em linha).
- Mover as configurações de servidores alternativos ao H5BP (HTML5 Boilerplate) configurações de servidor repo.
- Usar um protocolo url que referencie o jQuery e evite avisos de conteúdo misto.
- Otimizar o trecho do Google Analytics.
- Usar atualização de reset CSS recente de Eric Meyer e a redefinição HTML5 Doctor.
- Mais robusto sub/sup estilos CSS.
- Adicionar teclado .focusable classe auxiliar que se estende .visuallyhidden.
- Estilos de impressão: não imprimir de links hash ou JavaScript.
- Adicionar uma redefinição de impressão para filtros de propriedade do IE.
- Remover classe específica condicional-IE9 no elemento html.
- Remover margens a partir de listas dentro de elementos nav.
- Remover YUI profiling.

Após a versão v.1.0 de lançamento, o H5BP sofreu várias melhorias, transformadas em releases de lançamento para o uso de toda a comunidade de desenvolvedores, interessados em aperfeiçoar sites e criar novos sites que a ferramenta apresenta.
Abaixo uma tabela com todas as releases lançadas para o H5BP. As principais mudanças serão descritas posteriormente.

Versão  | Mudanças expressivas? | Ano
------  | --------------------- | ----
v.1.0   | Versão inicial        | 2011
v.2.0   | Sim                   | 2011
v.3.0   | Sim                   | 2012
v.3.0.1 | Não                   | 2012
v.3.0.2 | Não                   | 2012
v.4.0   | Sim                   | 2012
v.4.0.1 | Não                   | 2012
v4.0.2  | Não                   | 2012
v4.0.3  | Não                   | 2013
v4.1.0  | Não                   | 2013
v4.2.0  | Sim                   | 2013
v4.3.0  | Sim                   | 2013
v5.0.0  | Sim                   | 2015
v5.1.0  | Não                   | 2015
v5.2.0  | Não                   | 2015
v5.3.0  | Não                   | 2016

A seguir, observa-se o gráfico de adições e deleções no código, desde sua primeira versão em 2011.
![](https://i.imgur.com/2NUMK1P.png)
Fonte: https://github.com/h5bp/html5-boilerplate/graphs/contributors

E o gráfico seguinte demonstra a quantidade de contribuidores do projeto ao longo dos anos, a partir de 2011.
![](https://i.imgur.com/C45dIcB.png)

É possível notar, analisando os dois gráficos, que o projeto contou com grande contribuição em seu início e, ao chegar em 2013, dois anos após seu início, estabilizou e chega perto de sua versão atual. O HTML5 Boilerplate se manteve estável e sem grandes mudanças até então, em 2016, o que indica que é um template seguro e com boa aceitação entre seus usuários.

Abaixo a descrição das principais melhorias em cada uma das versões, que trouxeram consideráveis mudanças e relevância ao H5BP:

**v.2.0**:
- Alteração no CSS começando a basear-se no normalize.css em vez de reset.css;
- Adição do prompt de script de quadro do Google Chrome para os usuários do IE6;
- Simplificação os comentários html condicionais para navegadores modernos e adicionar uma classe oldie;
- Adição do site de velocidade de rastreamento para o Google Analytics;
- Atualização para jQuery 1.6.2;
- Atualização para Modernizr 2.0 Complete;
- Maior agilidade na construção de processos;
- Adição de opções de script de construção para ferramentas CSSLint, JSLint, JSHint.
- Muitas melhorias .htaccess, incluindo: desabilitar a pesquisa no diretório, suporte melhorado para todas as versões do Apache, as regras de compressão HTTP mais robustos e extensos;
- Remoção do handheld.css, por ter uma baixa qualidade em suporte a dispositivos;

**v.3.0**:
- Melhorias no .htaccess;
- Melhorias no design do erro 404;
- Simplificação na estrutura da pasta JS.
- Alteração nos nomes de classe a fim de atingir várias faixas e não algumas versões específicas do Internet Explorer;
- Atualização de CSS para incluir as últimas alterações na normalize.css e melhores padrões tipográficos;
- Atualização para Modernizr 2.5;
- Remoção do Respond.js;
- Ativação por padrão do rastreamento de velocidade do site explícita para o Google Analytics.

**v.4.0.**:
- Melhorias na configuração do Apache;
- Adicionar licença MIT (a saber, a licença MIT é uma permissão, concedida gratuitamente a qualquer pessoa que obtenha uma cópia de um respectivo software e documentação associada para lidar com o software sem restrições e sem limitações, usufruindo dos direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e / ou vender cópias do software, sendo que a pessoa que utiliza o software está sujeita a um conjunto de regras);
- Separação do normalize.css dos demais CSS;
- Melhoria na proteção do console.log;
- Renomear arquivos CSS e renomear arquivos JS e subdiretórios.

**v.4.2.0**:

- Remoção do Google Analytics protocol checks;
- Atualização para Normalize.css 1.1.1.
- Configurações de atualização do Apache para incluir as últimas alterações na .htaccess;
- Utilização de uma URL relativa para o script modelo 404.

**v.4.3.0**:
- Atualização para Servidor Apache Configs 1.1.0;
- Atualização para o Google Analytics Universal;
- Atualização para jQuery 1.10.2;
- Atualização para Normalize.css 1.1.3;

**v.5.0.0**:
- Atualização para o servidor Apache Configs v2.11.0;
- Adicionar centralização vertical para iframe;
- Atualização para Normalize.css 3.0.2.;
- Atualização para Modernizr 2.8.3.;
- Redesign da página 404.


Estrutura
-------------

O template possui uma estrutura padrão que pode ser alterada. 

[![](https://2.bp.blogspot.com/-dMwPJCf2tk4/V_7aJamKgfI/AAAAAAAAB_c/35LIqCrz0CkXtZM7uHTAaPbboMvj7i6DwCLcB/s320/estrutura.jpeg)]()

Figura 1: template HTML5 Boilerplate

###CSS
O diretório deve conter todos os arquivos CSS do seu site, por padrão ele já inclui alguns arquivos iniciais.

Em relação aos estilos de impressão, o HTML5 Boilerplate pode ser considerado “ecologicamente consciente”. Ao preparar uma página para impressão,  reduz o número de páginas, remove as cores de fundo, sombras e altera fontes em tons de cinza, permitindo uma economia no uso da tinta da impressora.

O arquivo main.css se baseia no HTML5 Doctor com uma série de padrões inteligentes e melhorias. Classes comuns muito úteis estão declaradas, como .clearfix .hidden e .visuallyhidden. 

```
.hidden {
    display: none !important;
}

.visuallyhidden {
    border: 0;
    clip: rect(0 0 0 0);
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px;
}

.visuallyhidden.focusable:active,
.visuallyhidden.focusable:focus {
    clip: auto;
    height: auto;
    margin: 0;
    overflow: visible;
    position: static;
    width: auto;
}

.clearfix:before,
.clearfix:after {
    content: " "; /* 1 */
    display: table; /* 2 */
}

.clearfix:after {
    clear: both;
}
```

Bem como estilos de impressão, estilos de mídia paginada e design responsivo.

```
@media only screen and (min-width: 35em) {
    /* Style adjustments for viewports that meet the condition */
}

@media print,
       (min-resolution: 1.25dppx),
       (min-resolution: 120dpi) {
    /* Style adjustments for high resolution devices */
}
```

Na figura abaixo é possível identificar as propriedades de responsividade de um site gerado com HTML5 Boilerplate, acessado através de dispositivos com telas de dimensões diferentes.

[![](https://2.bp.blogspot.com/-Q51_GUL4wN4/V_7aI8uigZI/AAAAAAAAB_Q/3Pc7Gk6RI3wnsnAfiCPL5iZkI1MTgfYAQCLcB/s320/Nexus5.png)]()

Figura 2: Página acessada através do dispositivo Nexus 5

[![](https://2.bp.blogspot.com/-YVkLPQBOZEM/V_7aKcB6l-I/AAAAAAAAB_k/Rou1vRkYJoIPKeVp14MZIZtuqHh4HmjtACLcB/s320/ipad.png)]()

Figura 3: Página acessada através do dispositivo iPad

[![](https://2.bp.blogspot.com/-Z8-oibrvVfQ/V_7aMe9H9OI/AAAAAAAAB_o/AG_6jCgXaEUaplZfR5i24UtFUw0BkT1xgCLcB/s320/notebook.png)]()

Figura 4: Página acessada através do dispositivo um notebook de 14”


###JS

No diretório JS, podem ser armazenados arquivos JS, bibliotecas e plugins; ele também possui arquivos com código pré existente que servirá de apoio no início do desenvolvimento. Como citado antes, é utilizado o jQuery para manipular o JS do projeto de forma simples. O jQuery é uma biblioteca amplamente utilizada em vários locais justamente pela simplicidade e pelo comum uso.

[![](https://2.bp.blogspot.com/-9IaJK-pamfI/V_7aJ2VC9mI/AAAAAAAAB_g/zyCf7i62bII19RHVt1odqa5PKKjvLZrWwCLcB/s320/html5%2Bmarcas%2Bcorp.jpg)]()

Figura 5: Membros corporativos do jQuery - uma biblioteca código aberto amplamente utilizada

####main.js

É um arquivo para fazer referência ao seu código JavaScript. Como citado no GitHub, para projetos maiores, é possível utilizar um módulo carregador de JavaScript como Require.js, que é um módulo otimizado para se utilizar no navegador e pode ser usado em outros ambientes JS, para carregar quaisquer outros scripts que o usuário precise que seja executado.

####plugins.js

Esse arquivo pode ser usado para conter todos os plugins necessários, desde os próprios plugins do jQuery e outros fora dele. Uma forma de uso é colocar os plugins do jQuery dentro de um (function ($) {...}) (jQuery), fechado para garantir que eles estão no cobertor de segurança do jQuery.
Por padrão, o arquivo plugins.js contém um pequeno script para evitar erros do console em navegadores que não possuem um. O script funciona de forma que primeiro verifica se dado método do console está disponível, se não estiver, o script fará o método ter o valor de uma função vazia, o que impede, dessa forma, que o navegador rode algum erro.

####vendor

Esse diretório pode ser usado para conter toda biblioteca third party, ou seja, fora do jQuery, que será utilizada para o projeto.

####Página de erro

Sabe-se que é impossível evitar que erros aconteçam durante a navegação em um site. O mais comum deles é o erro 404, gerado quando uma página requisitada não foi encontrada devido a links desatualizados, páginas que mudam de lugar ou são excluídas. Ao se deparar com esse e outros diversos erros, muitos usuários tendem a abandonar o site. 

Uma página de erro personalizada, com aparência mais amigável é de grande importância, pois incentiva ao usuário continuar no site para tentar repetir a ação ou continuar navegando para buscar uma nova alternativa. Pensando nisso, o template fornece uma página de erro com um estilo básico que poderá ser customizado.

O arquivo 404.html fornece uma configuração básica. Ao abrir a tela sem alterar o arquivo você irá se deparar com a seguinte mensagem:


[![](https://2.bp.blogspot.com/-Ylk1QPmOlcg/V_7aHDHVMyI/AAAAAAAAB-8/ys8xGBnIX84qMDtHMnguyqzQ1VtiR5UaQCLcB/s320/404.png)]()

Figura 6: Página de erro 404

####Index

O index, como nós sabemos, é uma página padrão do template, e através desse padrão criamos todas as outras páginas. No GitHub do HTML5 Boilerplate, é possível localizar o modelo index em que ele é trabalhado, como é possível ver a seguir:

```
<!doctype html>
<html class="no-js" lang="">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title></title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <link rel="apple-touch-icon" href="apple-touch-icon.png">
        <!-- Place favicon.ico in the root directory -->

        <link rel="stylesheet" href="css/normalize.css">
        <link rel="stylesheet" href="css/main.css">
        <script src="js/vendor/modernizr-2.8.3.min.js"></script>
    </head>
    <body>
        <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->

        <!-- Add your site or application content here -->
        <p>Hello world! This is HTML5 Boilerplate.</p>

        <script src="https://code.jquery.com/jquery-{{JQUERY_VERSION}}.min.js"></script>
        <script>window.jQuery || document.write('<script src="js/vendor/jquery-{{JQUERY_VERSION}}.min.js"><\/script>')</script>
        <script src="js/plugins.js"></script>
        <script src="js/main.js"></script>

        <!-- Google Analytics: change UA-XXXXX-Y to be your site's ID. -->
        <script>
            window.ga=function(){ga.q.push(arguments)};ga.q=[];ga.l=+new Date;
            ga('create','UA-XXXXX-Y','auto');ga('send','pageview')
        </script>
        <script src="https://www.google-analytics.com/analytics.js" async defer></script>
    </body>
</html>

```

É um código sucinto que facilita a compreensão do usuário e já inclui algumas funcionalidades do HTML5 Boilerplate, como a inserção dos arquivos JavaScript para a manipulação do jQuery (plugins.js e main.js, das linhas 25 à 28) e também os arquivos CSS. Na linha 15, após os arquivos CSS é possível também verificar a inserção do Modernizr.
Apesar de todo amplo uso do HTML5 Boilerplate, o comentário no index, das linhas 18 a 20, indicam falta de suporte para certos tipos de navegadores, contando com uma prevenção de erro e um aviso para o projetista que desejar usar o Internet Explorer.

####Ícones
O HTML5 Boilerplate fornece uma lista de arquivos com uma base pré-fixada de ícones que podem ser utilizados pelo desenvolvedor ou substituídos por outros ícones nas construções web. Os ícones de atalho para cada página deverão ser colocados no diretório raiz de cada site. 

O arquivo Favicon.ico e apple-touch-icons (que são eles: apple-touch-icon.png, apple-touch-icon-precomposed.png, apple-touch-icon-57x57-precomposed.png, apple-touch-icon-72x72-precomposed.png e apple-touch-icon-114x114-precomposed.png), são os que armazenam os ícones que poderão ser usados na construção dos sites.

Com H5BP é possível usar os favicons (ou ícones de toque) em diferentes variações de tamanho, qualidade e etc., para smartphones, tablets e outros equipamentos corretamente, sem problemas de adequação de tela.

[![](https://3.bp.blogspot.com/-EFTPRq_sYfk/V_72A7VY5wI/AAAAAAAACAE/gMaIB-9G-484RmExwnwU6G-Cg16CJwMzwCLcB/s320/HTML5-Boilerplate-Favicons_v3.1.png)]()

Figura 7: Tamanhos dos favicons


Sites criados através do HTML5 Boilerplate
-------------

Abaixo, alguns exemplos de sites que utilizam o HTML5 Boilerplate:

- https://www.barackobama.com/ 
- https://www.mercedes-benz.com/en/
- https://data.nasa.gov/

[![](https://3.bp.blogspot.com/-3Hm1IMnbudI/V_7aI_vEREI/AAAAAAAAB_U/d2Ob6PqkEy4NPDUC-ZpzxJVKH2zaXUEDQCLcB/s1600/Site%2Bdo%2BObama.jpg)]()

Figura 8: Página que usa HTML5 Boilerplate

Conforme visto na seção “CSS”, o HTML5 Boilerplate é “ecologicamente consciente” para a impressão, reduzindo o número de páginas, removendo as cores de fundo, sombras e alterando fontes em tons de cinza, permitindo uma economia no uso da tinta da impressora.
Abaixo uma figura que mostra como é a visualização de impressão de páginas de sites criados com o HTML5 Boilerplate:

[![](https://3.bp.blogspot.com/-y0M9XuD6J9s/V_7aJN6dQqI/AAAAAAAAB_Y/E24jdWJ0VyI6pj60tySFPudmSI_ev7mcwCLcB/s1600/Visualizador_site_obama.jpg)]()

Figura 9: Visualização de impressão HTML5 Boilerplate

Podemos ver a grande variedade de páginas com diferentes finalidades que o HTML5 pode atender, e demonstrando muita qualidade no trabalho final:

![](https://i.imgur.com/EEr8GrB.png)

Figura 10: Exemplos diferentes de páginas. Nesta há disponibilidade de várias imagens, em que o usuário as coleciona na sua conta e pode fazer envio.

![](https://i.imgur.com/Exw1X8U.png)

Figura 11: Outra variação de uso do HTML5 para um site de compras.

![](https://i.imgur.com/JcjReMW.png)

Figura 12: Uma página de vídeos HTML5 em código aberto.


Conclusão
-------------
Se tratando de arquitetura, observa-se que o HTML em abriu portas para interfaces independentes de dispositivos e o H5BP, sendo uma ramificação do HTML, herda isto, esta facilidade de transitar em diversos dispositivos com qualidade e sem problemas de conformidade. Observa-se que juntamente com as bibliotecas de componentes de interface gráfica nativas do HTML5 e os acréscimos que a versão Boilerplate trouxe, fornece um modo que independe do dispositivo que será utilizado, para criar interfaces móveis com o Javascript através do JQuery. 

O HTML5 Boilerplate é um sistema interessantíssimo e amplamente utilizados por desenvolvedores web para sites e aplicações. Os recursos trazidos pelo sistema e a qualidade com que é entregue atrai não só a atenção dos desenvolvedores, mas também dos próprios clientes, como podemos visualizar nos vários exemplos.

É importante salientar as constantes melhorias e releases lançadas para o sistema, visto que, apesar de ser considerado de grande qualidade, não é foco parar de melhorá-lo. Um exemplo já citado acima que pode ser referenciado neste caso é o fato do H5BP ter um sistema consciente de impressão que economiza as tintas da impressora, deixando nos modos de impressão apenas conteúdos relevantes nas páginas.


Referências
-------------
BUTTERS, K. An Introduction to HTML5 Boilerplate. Disponível em <https://www.sitepoint.com/introduction-html5-boilerplate/>. Acesso em 09 out 2016.
GRANNELL, C. How to use an HTML boilerplate. Disponível em <http://www.creativebloq.com/web-design/how-use-html-boilerplate-11513798>. Acesso em 09 out 2016.
SILVEIRA, F. Initializr – Comece Seu Projeto HTML5 Em 15 Segundos! Disponível em <http://flaviosilveira.com/2011/initializr-comece-seu-projeto-html5-em-15-segundos/>. Acesso em 09 out 2016.
IRISH, P. HTML5 Boilerplate Hits 2.0! Disponível em: <https://www.paulirish.com/2011/html5-boilerplate-hits-2-0/>. Acesso em 09 out 2016.
HANS, C. HTML5 Boilerplate Favicon PSD-Template. Disponível em https://drublic.de/archive/html5-boilerplate-favicons-psd-template/. Acesso em 12 de Out 2016
