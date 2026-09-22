Documentação do Projeto: Gamdle de Navegador Web

Este documento explica de forma simples e direta o funcionamento do programa Gamdle de Navegador Web, criado para demonstrar como o computador organiza tarefas do dia a dia, como navegar na internet e baixar arquivos. Criado para ajudar no tédio e estresse que o dia q dia proporciona fazendo com que tenha um tempo para se divertir mas ainda sim exercitarmos a mente.

1. O que este programa faz?
Quando usamos a internet, o navegador precisa lembrar por onde passamos para que o botão "Voltar" funcione. Ele também precisa organizar os arquivos que mandamos baixar para que eles não venham todos embaralhados.
Este programa simula exatamente essas duas funções usando conceitos básicos de programação:

 • O Histórico de Páginas (Pilha): Guarda as páginas que você visitou para que você possa voltar nelas na ordem correta.

 • A Fila de Downloads (Fila): Organiza os arquivos que você deseja baixar, garantindo que o primeiro que você pediu seja o primeiro a ser baixado.

2. Como as coisas funcionam por dentro
Para organizar os dados, o programa utiliza duas lógicas muito comuns no nosso cotidiano:

 • A Pilha (LIFO - O último a entrar é o primeiro a sair):

   • Exemplo prático: Pense em uma pilha de pratos limpos em cima da mesa. O último prato que você lava e coloca em cima é o primeiro que você pega para usar.

   • No programa: Se você visitou o Google, depois o GitHub e por fim o StackOverflow, a última página aberta fica no topo. Quando você clica em "Voltar", é essa última página que some primeiro.

 • A Fila (FIFO - O primeiro a chegar é o primeiro a sair):

   • Exemplo prático: Pense em uma fila de banco ou de cinema. Quem chega primeiro, é atendido primeiro.

   • No programa: Se você pediu para baixar um relatório, depois uma foto e depois um instalador, o programa vai baixar exatamente nessa mesma ordem.

3. Como usar o programa no computador
Para quem quer rodar e testar o código no computador:

 • O que você precisa: Um programa que saiba ler e compilar a linguagem C (como o GCC).

 • Como executar:

   • Salve o código em um arquivo de texto com o nome navegador.c.

   • Abra a tela preta de comandos (Terminal ou Prompt de Comando) na pasta onde salvou o arquivo.

   • Digite o comando para compilar: gcc navegador.c -o navegador

   • Digite o comando para rodar: ./navegador (ou apenas navegador no Windows).

 • O que vai acontecer: O programa vai rodar sozinho no terminal, mostrando passo a passo a simulação de navegação pelas páginas web e, em seguida, executando a fila de downloads na ordem certa.

4. Sobre os Direitos de Uso (Licença)
Este software é totalmente livre e gratuito para fins de estudo. Ele utiliza a licença padrão MIT License, o que significa que qualquer pessoa pode copiar, modificar, estudar ou compartilhar este código livremente, desde que mantenha os créditos originais de autoria.
