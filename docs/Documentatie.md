---
layout: page-with-side-nav
title: Documentatie Digikoppeling Adapter Intern
folder_files:
  - title: DigikoppelingInternStandaardv1.0
    path: documenten/DigikoppelingInternStandaardv1.0.pdf
    group: 10
    versie: 1.0
    status: Ter vaststelling
    omschrijving: 
---

# Documentatie

## Digikoppeling Adapter Intern 1.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 10 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
