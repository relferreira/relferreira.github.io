---
published: true
title: Hello world
layout: post
---
Sublime text 2 é um incrível editor de texto, utilizado para a escrita de código em diversas linguagens. Na área de desenvolvimento Web ele ganhou muito força devido a diversas funções que facilitam muito a edição rápida de códigos e devido aos *Packages*, que estendem os poderes do editor. Este post irá indicar alguns packages para melhorar a sua experiência com esta ferramenta.
<!-- more -->

##Package Control
A primeira etapa para deixar o Sublime melhor ainda é instalar o *Package Control. Como o nome diz, ele é responsável pelo gerenciamento de pacotes, que são uma espécie de plugins capazes de agregar funcionalidades ao editor de texto.

O processo de instalação é bastante simples. Com o Sublime aberto, acesse o menu View>Show Console ou pressione o atalho "ctrl + '" e copie e cole o código localizado no [site do Package Control](https://sublime.wbond.net/installation). Tome cuidado em escolher a versão correta do Sublime que você está utilizando. *Este tutorial irá cobrir apenas o Sublime Text 2*.


##Instalando Pacotes

Após a finalização do processo de instalação, o Package Control poderá ser acessado pelo atalho 'ctrl + shift + p' (no Windows) ou _____ (no Mac). Digite "Install Package" e realize uma busca do pacote que deseja. Segue abaixo uma lista de pacotes muito úteis no dia a dia de um desenvolvedor.

## SublimeLinter

Enfatiza as linhas de código que possuem erros em potencial. O pacote suporta uma lista de linguagens como por exemplo:

+ HTML
+ CSS
+ JavaScript
+ PHP
+ Phyton

E muitas outras. 
Para suportar códigos em JavaScript ou CSS é necessário possuir a engine JavaScript instalada no sistema operacional. A forma mais simples de garantir esta condição é instalando o NodeJs através do [link](http://nodejs.org/#download).

Para mais informações, acesse o repositório do desenvolvedor no [github](https://github.com/SublimeLinter/SublimeLinter).

##DocBlockr

Este pacote possui como premissa facilitar a documentação do código. Basta digitar, por exemplo, o atalho "/**" e pressionar "Tab" para surgir um bloco de documentação. Quando utilizado em funções ou métodos, ele irá listar, automaticamente, todos os nomes dos parâmetros e valores retornados, para uma descrição sobre o seus tipos de dados e contextos.

{% img https://github-camo.global.ssl.fastly.net/415148aecc6dac2e5ebb12b7f7584f4a8744eca4/687474703a2f2f73706164676f732e6769746875622e696f2f7375626c696d652d6a73646f63732f696d616765732f66756e6374696f6e2d74656d706c6174652e676966 %}

Existem diversos atalhos e a lista de linguagens suportadas inclui Javascript, PHP, ActionScript, CoffeeScript, Java, Groovy, Objective C, C, C++ e Rust.
Veja mais detalhes no [github](https://github.com/spadgos/sublime-jsdocs).

## Minifier

Como o nome indica, o pacote realiza a minificação de arquivos JS e CSS.
Após instalar o pacote, acesse o menu "Tools/Minify".

Para mais informações e atalhos acessem o repositório do pacote, [github](https://github.com/tssajo/Minify).

##ColorPicker

Quem nunca digitou "background-color" em um arquivo css e não tinha nem idéia de qual cor utilizar? Se você se encaixa nesta descrição, este pacote é para você. Basta acessar o atalho "ctrl + shift + c" (no Windows) que uma palheta de cores, padrão do sistema operacional, irá aparecer.

{% img http://i5.minus.com/iY1DDCRG5TsyR.png %}

Acesse a página do desenvolvedor para mais informações, [site](http://weslly.github.io/ColorPicker/) and learn more.



## Soda Theme

{% img http://buymeasoda.github.io/soda-theme/images/soda-dark-screenshot.png 'Soda Theme' %}

Além de todas as customizações que o Sublime oferece, você ainda pode instalar temas adicionais. Um dos mais famosos é o [Soda Theme](http://buymeasoda.github.io/soda-theme/). O pacote vem com duas opções de cores, Soda Light, que se baseia em cores mais claras, e o Soda Dark, que é mais escuro.

Para instalar basta procurar o tema no Package Control. Logo, você deve abrir o arquivo de preferências do usuário acessando o menu "Preferences/Settings/User". Adicione ou modifique o campo "theme" de modo que fique

	{
	    "theme": "Soda Light.sublime-theme"
	}


ou

	{
	    "theme": "Soda Dark.sublime-theme"
	}

Existem outras opções do tema como modificar o estilo das tabs e das pastas. Saiba mais no [site](http://buymeasoda.github.io/soda-theme/).