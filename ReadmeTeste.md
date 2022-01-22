primeiro dia, vamos começar com a primeira parte do seu site, então vamos fazer o menu por cima do nosso site, ele tem o que? tem o nome do nosso produto, e as sessões do nosso site.

Quando começamos a codificar um site, temos que "quebrar" ele na nossa
cabeça, temos três partes. O Header/Home/About/Services/Contact/Footer
(colocar uma foto ilustrativa)

primeiro nós vamos colocar uma tag header, com o id de header
<header id="header">
    
</header>

depois vamos colocar um nav (colocar o porque do que colocar nav
com a class container (class, colocamos quando sabemos vamos colocar
outra coisa))
<header id="header">
    <nav class="container">
    
    </nav>
</header>


<a class="logo" href="#">delivery<span>book</span>.</a>
        <!-- menu -->
        <div class="menu">
          <ul class="grid">
            <li><a class="title" href="#home">Início</a></li> 
            <li><a class="title" href="#about">Sobre</a></li>
            <li><a class="title" href="#services">Serviços</a></li>
            <!-- <li><a class="title" href="#testimonials">Depoimentos</a></li> -->
            <li><a class="title" href="#contact">Contato</a></li>
          </ul>
        </div>
        <!-- /menu -->
        <div class="toggle icon-menu"></div>
        <div class="toggle icon-close"></div>


Bônus: seta/dark