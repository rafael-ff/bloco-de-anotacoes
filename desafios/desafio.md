# Como mudar tema do zsh

1. acesse o link <https://github.com/robbyrussell/oh-my-zsh/wiki/themes> e encontre um tema que lhe agrade (veja se ele não possui nenhuma particularidade) copie o nome do tema para posterior inclusão no arquivo __.zshrc__


2. digite o comando abaixo no seu terminal.(neste caso estamos utilizando o vim como editor de texto, mas pode ser utilizado outro de sua preferência)
```
vim ~/.zshrc
```
![mudar tema zsh](https://preview.ibb.co/nMfthA/zsh.png)


2. No vim, aperte a tecla "i" (de insert) para incluir informações no arquivo.

3. Procure no texto o trecho __ZSH_THEME="xxxxx"__

4. cole no valor __ZSH_THEME=""__ o nome do tema que você copiou no passo 1, por exemplo: __ZSH_THEME="bira"__, este é o tema que estou utilizando.

5. Para salvar e sair do vim, aperte __ESC__ seguido de __:x__

6. Feito isso, feche seu terminal e abra novament e pronto, seu novo tema foi instalado.

# Alterando mensagem do último commit

* Caso seu último commit esteja com a mensagem errada, basta utilizar o comando `git commit --amend`. Após digitar o comando, o editor de texto será aberto e nele você poderá efetuar a modificação e salvar.

# Dicas de markdown

## Links

* utilize os sinais de menor e maior - \<http://www.google.com.br> - para mostrar o próprio link como texto <http://www.google.com.br>

* Para o texto de sua preferência virar um link, utilize um par de colchetes [ ] para o seu texto, seguido de um par de parenteses () contendo o seu link. Por exemplo: para gerar o seguinte resultado  [Google](https://www.google.com.br), faça \[Google]\(https://google.com.br)

## Lista ordenada
* utilize o numero ordinal seguido de ponto para criar uma estrutura igual a mostrada abaixo:
```
1. item 1
2. item 2
```
## Ênfase
* caso precise enfatizar algo, simplesmente utilize \*parte enfatizada* (este gera um itálico) ou \_\_parte enfatizada__(este gera um negrito).<br>
O resultado será respectivamente: *parte enfatizasa* __parte enfatizada__ 

## BLocos de código
* Por último, para gerar blocos de cógidos, utilize três sinais de crase, seguido do seu código e no final mais três sinais de crase para fechar. \``` codigo\```.
Resultado:
```
function example(){
    return 'test';
}
```
 


