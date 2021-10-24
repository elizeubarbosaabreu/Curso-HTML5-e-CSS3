# Curso-HTML5-e-CSS3

Este é o resultado do conteúdo aprendido durante o curso Introdução a Criação de Websites com HTML5 e CSS3 relizado gratuitamente pela [Digital Innovation One](https://web.digitalinnovation.one/).

# Página gerada durante os estudos
Confira no [index.html](https://elizeubarbosaabreu.github.io/Curso-HTML5-e-CSS3/) a visualização da página criada durante os estudos... ¬(¨)-¬

## Estrutura básica do html

~~~html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Isso É o título que aparece na baba do browser</title>
	</head>
	<body>
		<p>Quiquia adipisci velit est magnam non non etincidunt. Sit etincidunt dolorem eius quaerat ut. Porro aliquam quisquam dolor. Quiquia velit sit non. Neque quaerat ipsum sit numquam. Dolor ut magnam est quiquia. Quaerat est ipsum modi aliquam. Velit dolorem consectetur sed numquam ipsum. Sit velit labore ipsum numquam quisquam tempora non. Sed dolor dolore modi labore sed ut eius.</p>
	</body>
</html>
~~~

## Acrescentado seções  na estrutura do index.html

~~~html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Elizeu Barbosa Abreu</title>
	</head>
	<body>
		<header>
			<h1>Elizeu Barbosa Abreu</h1>		
		</header>
		<section>
			<header>
				<h2>Lorem Ipsum</h2>			
			</header>		
		</section>
		<section>
			<article>
				<header>
					<h3>Dolor numquam adipisci</h3>
				</header>
			<p>Adipisci porro aliquam modi numquam non consectetur. Numquam quisquam eius dolore velit. Voluptatem voluptatem ipsum porro. Velit quisquam etincidunt est. Consectetur dolor aliquam numquam quisquam sed. Numquam quiquia modi labore quaerat sed.</p>

			<p>Dolor numquam adipisci sit neque amet. Amet etincidunt quiquia voluptatem labore neque quiquia porro. Labore aliquam magnam velit neque adipisci. Ipsum non non ipsum porro labore est porro. Aliquam amet amet consectetur dolore non quiquia sit.</p>

			<p>Dolore dolore modi dolor. Voluptatem dolorem porro consectetur. Amet numquam sit aliquam tempora. Neque eius voluptatem aliquam sit dolor. Sed quisquam quiquia adipisci magnam numquam. Non numquam eius amet tempora. Labore sed modi ut numquam aliquam sit. Magnam consectetur sit porro. Dolorem velit consectetur labore dolorem. Ut ut numquam quaerat consectetur ipsum.</p> 
							
			</article>
		</section>		
	</body>
</html>
~~~

## Textos e Links
### Tags para textos

~~~html
<h1>Título da Página</h1>

<h2>Título de Sessão</h2>

<h3>Título de Artigo</h3>

<p>Conteúdo do Artigo.</p>
~~~


### Tags para Links

~~~html
<a>link</a>

<a href="https://www.linkedin.com/in/elizeu-barbosa-abreu-69965b218/">linkedin url</a>

<a href="mailto:seuemail@seuprovedor.com">Link para email</a>

<a hret="tel:08007250100">Ligar para 0800 725-0100</a>

<a target="_blank">Link Âncora</a>

~~~

### Tags para imagens
~~~html
<img>

<img alt="Logo do Linux" src="images/gnuLinux.png">

~~~
Resultado: <img alt="Logo do Linux" src="images/gnuLinux.png">


### Tags de listas: li, ul, ol

Código:
~~~html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
~~~
Resultado:
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>


Código:
~~~html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
~~~
Resultado:
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

### Adição de estilos
foi criado uma pasta para folhas de estilos.
estilos adicionados: 
~~~css
body {
	background-color: #cccccc;
	margin-top: 25px;
	margin-left: 25px;
	margin-right: 25px;	
}


#title, .subtitle, .post_title {
	color: blue;	
}

.post_title {
	font-size: 14px;
	font-style: italic;
}

article {
	background-color: #fff;
	padding: 10px;
	border: 3px solid #000000;

}
~~~

