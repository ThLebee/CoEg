---
title: Lettres d’Auguste Mariette
layout: landing
description : 'Cette rubrique rassemble les lettres écrites par Auguste Mariette, consultables et téléchargeables aux formats PDF et XML. Elle donne également accès aux métadonnées de ces documents et à des outils de visualisation autour de ce corpus.'
image: assets/images/Mariette.jpg
nav-menu: true
---
<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">

<!-- Content -->
<h2>Édition des lettres</h2>

<iframe src="https://ThLebee.github.io/CoEg_test_forty/doc/CoEg_Mariette.pdf" width="100%" height="500px"></iframe>

<p>Les lettres peuvent être téléchargées sous plusieurs formats&nbsp;:
<ul>
	<li>Une édition PDF qui permet de consulter le corpus, (à consulter <a href="https://github.com/ThLebee/CoEg_test_forty/blob/gh-pages/doc/CoEg_Mariette.pdf">sur Github</a>, <a href="https://raw.githubusercontent.com/ThLebee/CoEg_test_forty/gh-pages/doc/CoEg_Mariette.pdf">dans le navigateur</a> ou <a href="{{site.baseurl}}/doc/CoEg_Mariette.pdf" download>télécharger</a>&nbsp;;</li>
	<li>Le fichier Latex qui a permis de générer l’édition PDF, accessible <a href="https://github.com/ThLebee/CoEg_test_forty/blob/gh-pages/doc/CoEg_Mariette.tex">sur Github</a> ou <a href="{{site.baseurl}}/doc/CoEg_Mariette.tex" download>en téléchargement</a>&nbsp;;</li>
	<li>Une édition en XML-TEI&nbsp;: elle aussi consultable <a href="https://github.com/ThLebee/CoEg_test_forty/blob/gh-pages/doc/CoEg_Mariette.xml">sur Github</a> ou <a href="{{site.baseurl}}/doc/CoEg_Mariette.xml" download>téléchargeable directement</a>.</li></ul></p>

<section>
	<h2>Métadonnées des lettres</h2>
	<p>Les données descriptives des lettres sont ici rassemblées sous différents formats pour pouvoir être exploités informatiquement.
	<ul>
		<li>La descriptions des lettres  (au format CSV) à consulter <a href="https://raw.githubusercontent.com/ThLebee/CoEg_test_forty/gh-pages/doc/CoEg_Mariette_letters.tsv">dans le navigateur</a>, <a href="https://github.com/ThLebee/CoEg_test_forty/blob/gh-pages/doc/CoEg_Mariette_letters.tsv">sur Github</a> ou <a href="{{site.baseurl}}/doc/CoEg_Mariette_letters.tsv" download>télécharger</a>&nbsp;: les différents champs y reprennent, pour chaque lettre éditée, son identifiant, l’institution et le lieu de conservation, la date et le lieu d'écriture, l’identité du destinataire, ainsi que les identifiants associés&nbsp;;</li>
		<li>La description des lettres au format <a href="https://correspsearch.net/index.xql?id=participate_cmi-format">XML-CMIF</a> à <a href="{{site.baseurl}}/doc/CoEg_Mariette_CMIF.xml" download>télécharger</a> ou <a href="https://github.com/ThLebee/CoEg/blob/gh-pages/doc/CoEg_Mariette_CMIF.xml">consulter sur Github</a>.</li></ul></p>

</section>
<section>
	<h2>Outils de visualisation</h2>
	<p>Quelques exemples d’utilisation des données accessibles plus haut.</p>
	<div>
		<hr>
		<h3>Visualiser les lettres dans le temps et l’espace</h3>
		<div class="row">
			<div class="6u 12u$(small)">
				<h4>Lieux d'écriture des lettres</h4>
					<p>Sur cette carte, chaque lettre est rattachée à son lieu d’écriture. La description donne des informations plus détaillées sur sa date et sa localisation actuelle, ainsi qu’un lien vers la lettre dans le fichier PDF.</p>
			</div>
			<div class="6u$ 12u$(small)">
				<h4>Chronologie des lettres éditées</h4>
				<p>Cette frise indique les lettres éditées, classées par correspondant, avec un lien pour accéder à la lettre en question dans le fichier PDF.</p></div>
		</div>
		<div class="row">
			<div class="6u 12u$(small)">
				<iframe width="100%" height="500px" frameborder="0" allowfullscreen src="//umap.openstreetmap.fr/fr/map/correspondances-egyptologiques-lieux-decriture_461359?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=null&allowEdit=false&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=undefined&captionBar=false#5/37.996/25.884"></iframe>
				<center><p><a href="//umap.openstreetmap.fr/fr/map/correspondances-egyptologiques-lieux-decriture_461359" class="button small">Voir en plein écran</a></p></center>
			</div>
			<div class="6u$ 12u$(small)">
				<iframe width="100%" height="500px" src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1dSLs2GhF5R_Ly6vMcmb1ixwKNxUXUVIr1il8k6omaM8&font=Default&lang=fr&initial_zoom=1&height=500' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>
				<center><p><a href="https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1dSLs2GhF5R_Ly6vMcmb1ixwKNxUXUVIr1il8k6omaM8&font=Default&lang=fr&initial_zoom=2&height=650" class="button small">Voir en plein écran</a></p></center>
			</div>
		</div>
	</div>
		<hr>
	<h3>Lieux mentionnés dans les lettres</h3>
<p>Cette carte indique les lieux indexés dans les lettres de Mariette. Leur description plus détaillée des lieux est accessible dans l’<a href="{{site.baseurl}}/webpages/data">index</a>.</p>
			<iframe width="100%" height="500px" frameborder="0" allowfullscreen src="//umap.openstreetmap.fr/fr/map/correspondances-egyptologiques-lieux_461360?scaleControl=false&miniMap=false&scrollWheelZoom=true&zoomControl=true&allowEdit=false&moreControl=true&searchControl=null&tilelayersControl=null&embedControl=null&datalayersControl=true&onLoadPanel=undefined&captionBar=false#5/37.996/25.884"></iframe>
			<center><p><a href="//umap.openstreetmap.fr/fr/map/correspondances-egyptologiques-lieux_461360" class="button small">Voir en plein écran</a></p></center>
</section>
