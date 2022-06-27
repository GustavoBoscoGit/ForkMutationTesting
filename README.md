# ForkMutationTesting

<p>Alunos: Frederico Bernardes Wust Stein e Gustavo Bosco.</p>

<p>Nesse trabalho realizamos o fork de um projeto com testes unitários prontos, e executamos o teste de mutação.</p>
<p>Ferramentas utilizadas:</p>

- Xunit para os testes unitários;
- Stryker para os testes de mutação;

<p>A linguagem utilizada foi o C# pois o Stryker é uma biblioteca que oferece testes de mutação exclusivamente para .NET.</p>
<p>Ao executar o Stryker é gerado um relatório onde nele estão presentes os cenários que foram "mortos" pela mutação e aqueles que sobreviveram. Também é possivel visualizar qual foi a mutação realizada pela ferramenmta.</p>

<p>Relatório Geral:</p>
<p align="center"><img src="img/img1.png"></p>

<p>Cenários que sobreviveram a mutação:</p>
<p align="center"><img src="img/sobrevivente1.png"></p>
<p align="center"><img src="img/sobrevivente2.png"></p>

<p>Cenários mortos pela mutação:</p>

<p align="center"><img src="img/cenarioMortos.png"></p>

# Como Executar

<p>Para executar o teste de mutação é necessário ter o .NET instalado e também é preciso instalar a biblioteca do striker.</p>
<p>Para instalar a biblioteca do striker é necessário rodar o comando:</p>

- dotnet tool install -g dotnet-stryker;

<p>Para executar o teste de mutação é necessário rodar o comando:</p>

- dotnet Stryker;



