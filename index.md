---
layout: default
---
{% include JB/setup %}

<div class="hero-unit row" >
		<h1>L'innovation au Québec ?</h1>
		<p>Bienvenue sur le site du rapport du voyage d'études à Montréal du <a href="http://masterpic.fr" target="_blank">Master PIC</a>, qui a eu lieu du 28 octobre au 3 novembre 2012. Vous trouverez ici la liste des <a href="articles-list.html#Entreprises-ref">comptes rendus des visites d'entreprises</a> ainsi que des <a href="articles-list.html#Articles-ref">articles de réflexion</a> sur des sujets d'innovation.</p>
		<p>
			<span class='st_facebook_vcount' displayText='Facebook'></span>
			<span class='st_googleplus_vcount' displayText='Google +'></span>
			<span class='st_twitter_vcount' displayText='Tweet'></span>
			<span class='st_linkedin_vcount' displayText='LinkedIn'></span>
		</p>
</div>

<div class="row">
	    <div class="span6">
		<h2>Visites d'entreprises</h2>
			<p>Cliquez sur une entreprise pour découvrir le compte rendu de la visite que nous y avons fait.</p>
			<p><a class="btn" href="articles-list.html#Entreprises-ref">Liste des entreprises &raquo;</a></p>
            {% for category in site.categories %}
                {% if category == "Entreprises" %}
                    {% assign pages_list = category[1] %}  
                    {% include JB/pages_list %}
              {% endif %}
            {% endfor %}
    </div>
    <div class="span6">
	    <h2>Regards croisés sur l'innovation</h2>
	    <p>"Open innovation", "implication des consammateurs dans le processus créatif", "innovation et performance des entreprises", autant de problématiques d'innovation qui se posent dans les entreprises aujourd'hui. Nous [les étudiants du Master PIC] avons exploré quelques unes de ces problématiques au regards des visites d'entreprise à Montréal. </p>
	    <p><a class="btn" href="articles-list.html#Articles-ref">Lire &raquo;</a></p>
	</div>	
</div>

###Avant-propos
Cette note est issue d’un voyage d’études organisé dans le cadre du Master Projet Innovation Conception de l’Ecole Polytechnique. Cet enseignement, qui réunit des étudiants d’écoles d’ingénieurs et de business school, associe des enseignements théoriques et l’implication dans des projets d’innovation concrets au sein d’entreprises.

Le voyage est l’une des composantes importantes du cursus. Il permet d’apprécier les enjeux des processus de l’innovation dans un contexte différent et de prendre la mesure de l’importance des aspects culturels dans ce domaine de la gestion. Ce séjour permet aussi naturellement de nouer des contacts avec les entreprises et les universités du pays d’accueil.

Les formations sur les domaines de gestion et ce type de voyages d’étude en particulier ne seraient pas possibles sans des coopérations étroites entre le monde académique et le monde de l’entreprise. Je tiens à remercier les entreprises qui nous ont accueillis avec beaucoup de disponibilité et d’ouverture.

Je remercie aussi chaleureusement nos collègues universitaires canadiens, en particulier Patrick Cohendet Brian Hobbs et Laurent Simon qui nous ont particulièrement aidés au montage de cette mission et l’ont éclairée de leurs analyses.

Enfin, David Massé et Felix von Pechmann ont assuré l’essentiel du lourd travail de montage de ce voyage. Au nom de tous nous les remercions.

> Christophe Midler, *professeur responsable du Master PIC*




