# ionic 3

## Start New Project

        $ ionic start nome_do_projeto nome_do _template —a--name “nome_da_app” —id info.thiagobraga.nome_do_projeto

## Add Page

        $ ionic g page nome_da_pagina
        
## Add Plugin (ex: leitor e gerador de Código de barras

        $ ionic cordova plugin add phonegap-plugin-barcodescanner
        $ npm install --save @ionic-native/barcode-scanner

## Add Platform

Cria um diretório com todos os arquivos para rodar naquela plataforma

$ ionic platform add + (plataforma)@(versão) --save (salva no xml) 

### Android
        
        $ionic platform add android@6.1.2 --save

###IOS

        $ionic platform add ios@6.1.2 --save

## State

        //Salva todas as plataformas adicionadas no projeto
        $ ionic cordova platform save 

        //Salva todos os plugins adicionados no projeto
        $ ionic cordova plugins save 

        //Restaura todos os plugins e plataformas do aquivo config.xml projeto
        $ ionic cordova plugins save
        
## Run e Emulate

run -> Serve para rodar a App em um device conectado

### Run

      $ ionic help run
      
#### --livereload

As atualizações que forem feitas no projeto serão reaplicadas no dispositivo conectado

#### --Address

Troca o IP para um personalizado

#### --port

Troca a porta para uma personalizada

#### --Consolelogs

Mostra no shell os logs do console

#### --Serverlogs

Mostra no shell os logs do servidor

#### -debugn|--release

Roda uma versão de debug ou uma de release (padrão) é debug

#### --device | --emulator | --target-ID

Roda em um dispositivo ou emulador ou pode passar qual o ID do algo do dispositivo que será rodado

### Emulate

        $ionic help emulate

Similar ao "run" porém roda em um emulador ao invés de um dispositivo
      
Esses comandos fazem a mesma coisa 

        $ ionic emulate android --device
        $ ionic run android --emulator

  


