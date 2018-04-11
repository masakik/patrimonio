# Patrimonio USP

Esta classe busca informações sobre bens patrimoniais que estão publicas na USP.

### Requsitos

Esta classe depende de:

    php-xml
    php-curl

### Instalação

    composer require uspdev/patrimonio

### Uso

    $patrimonio = new dadosUsp;
    $meu_monitor = $patrimonio->fetchNumpat('008.041864');
    print_r($meu_monitor);
    
Tem exemplos na pasta sample
