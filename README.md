# FUNÇÕES

<h2>Sintaxe</h2>
<p>function nome(parametros){</p>
<p>//Instruções </p>
<p>}</p>
<br>
<h2>Função anonima</h2>
<p>const soma = function (a,b){ </p>
<p>   return a + b; </p>
<p> } </p>
<br>
<h2>Função autoinvocavel(IIFE)</h2>
<p> ( </p>
<p>     let name = "Digital Innovation One"</p>
<p>     retur name;</p>
<p>)();</p>
<p>ELA É EXECUTADA LOGO APÓS SER DECLARADA</p>
<br>
<h2>Callback</h2>
<p>Função passada como arguneto para outra Função </p>
<br>
<h2>VALORES PADRÃO</h2>
<p>*Arguments*</p>
<p>É um array com todos os parâmetros passados quando a função é invocada</p>
<br>
<h3>ARRAYS</h3>
<h3>Spread: uma forma de lidar separadamente com elementos</h3>
<p>O que era parte de um array, se torna uma parte independente</p>
<p>function sum(x, y, z){</p>
<p>        returna x + y + z;</p>
<p>}</p>
<p>const numbers = [1, 2, 3];</p>
<br>
<p>console.log(sum(...numbers));</p>
<br>
<h3>REST</h3>
<p>function confereTamanho(...args){</p>
<p> console.log(args.length)</p>
<p>}</p>
<p>confereTamanho() //0</p>
<p>confereTamanho(1, 2) //2</p>
<p>confereTamanho(3, 4, 5) //3</p>
<p>O que era parte de um elemento independente se torna parte de um array</p>
<h2>Object Destructuring</h2>
<p>Se colocar entre {} consegue filtrar apenas os dados que deseja em um objeto</p>
<br>
<h2>Arrow function</h2>
<p>const helloWorld = () => "Hello world"; </p>
<br>
<h1>Atividade 1: Alunos Aprovados</h1>
<p>1.Crie uma função que recebe o array alunos e um número que irá representar a média final;</p>
<p>2.Percorra o array e popule um novo array auxiliar apenas com os alunos cujas notas são maiores ou iguais à média final;</p>
<p>3. Utilize a técnica "object destructuring" para manipular as propriedades desejadas de cada aluno.</p>
<h1>Atividade 2: This</h1>
<p>Dada a função calculaIdade, utilize os métodos call e apply para modificar o valor de this. Crie seus próprios objetos para esta atividade!</p>

<p>function calculaIdade(anos) {<br>
	return `Daqui a ${anos} anos, ${this.nome} terá ${<br>
		this.idade + anos<br>
	} anos de idade.`;<br>
}</p>
