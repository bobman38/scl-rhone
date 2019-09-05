---
title: Journaux
layout: page
---

La SCL publie périodiquement un journal que vous pouvez consulter sur ce site. Pourquoi un journal ? Tout simplement pour diffuser plus largement les réflexions de la SCL et pour informer les habitants de l'Ouest Lyonnais de l'évolution des projets autoroutiers. Ce journal permet aussi d'informer les habitants des communes qui n'ont pas la possibilité de pouvoir s'exprimer dans leur bulletin municipal. Diffusé à 30 000 exemplaires dans plus de 30 communes, il reflète les idées de notre association dont le travail est toujours basé sur des documents officiels.

Pour vous faciliter la lecture du journal nous vous proposons de télécharger la version qui vous intéresse. Pour cela il vous suffit de cliquer sur le journal choisi.

<div class="toto">
bla
</div>
<ul>
  {% for item in site.data.newspaper.items %}
    <li>
        <a href="{{ item.file }}">{{ item.date }} {{ item.name }}</a>
    </li>
  {% endfor %}
</ul>
