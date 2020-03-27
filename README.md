<!DOCTYPE html>
<html lang="{{ site.lang | default: "it - ITA" }}">
  <head>

    {% if site.google_analytics %}
      <script async src="https://www.googletagmanager.com/gtag/js?id={{ site.google_analytics }}"></script>
      <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', '{{ site.google_analytics }}');
      </script>
    {% endif %}
    <meta charset="UTF-8">

{% seo %}
	<meta name = "author" content = "Giorgiutti &quot;GiulioCesare02&quot; Cristian">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="theme-color" content="#157878">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">
  </head>
  <body>

    <header class="page-header" role="banner">
      <p style="text-align:right;"><a href="http://umbrelladryeradvanced.github.io/immagini" style="color: rgb(250,255,250)"><font size="2">Galleria Immagini</font></a></p>
      <h1 class="project-name">{{ page.title | default: site.title | default: site.github.repository_name }}</h1>
      <h2 class="project-tagline">{{ page.description | default: site.description | default: site.github.project_tagline }}</h2>
      {% if site.github.is_project_page %}
        <a href="{{ site.github.repository_url }}" class="btn">View on GitHub</a>
      {% endif %}
      {% if site.show_downloads %}
        <a href="{{ site.github.zip_url }}" class="btn">Download .zip</a>
        <a href="{{ site.github.tar_url }}" class="btn">Download .tar.gz</a>
      {% endif %}
    </header>
	
	<article>
		<img src="https://user-images.githubusercontent.com/62671277/77656689-86ff7700-6f74-11ea-9265-18794c936979.png" alt="Logo3">
		<ul>
			<li><a href="http://umbrelladryeradvanced.github.io/immagini"><strong>Galleria Immagini</strong></a></li>
			<li><a href="https://it.wikipedia.org/wiki/Strage_di_piazza_Fontana"><strong>Scopri di più</strong></a></li>
			<li><a href="https://www.youtube.com/watch?v=PSi09nxiyHA"><strong>Sei Maria Grazia da Bassano? Guarda qui</strong></a></li>
		</ul>
		<br/>
		<strong>LA NOSTRA MISSION</strong>
		<br/>
		<p>
			Umbrella Dryer Advanced è un’azienda che si è inserita nel mercato con l'obiettivo di portare un’idea innovativa, che possa essere         utile nella quotidianità. L’azienda punta sul diffondere sul mercato Europeo questo prodotto, il quale è attualmente diffuso               unicamente in Oriente e in America. La nostra idea nasce dalle piccole inconvenienze quotidiane: un ombrello bagnato che sporca e         inumidisce i vestiti, pozze d’acqua sparse in giro. Abbiamo quindi colto l’occasione di questo progetto per poter mettere in atto la       nostra idea: 
			<br/>
			<strong>un asciuga ombrelli</strong>.
			<br/>
		</p>
		<p>
		Nel breve termine, contiamo di riuscire a vendere piccole quantità di prodotti, con il fine di raccogliere i fondi necessari per far prendere piede all’azienda. Nel lungo termine invece, puntiamo ad espanderci per poter non solo diffondere il prodotto dovunque sia possibile, ma anche per poter trattare altri prodotti non ancora presenti in Europa.
		</p>
	</article>
    <main id="content" class="main-content" role="main">
      {{ content }}

      <footer>
        <a href="giorgiutti.cristian2@gmail.com"><strong>Contattaci via email</strong></a>
		<a href="https://github.com/UmbrellaDryerAdvanced"><strong>Contattaci via GitHub</strong></a>
      </footer>
    </main>
  </body>
</html>
