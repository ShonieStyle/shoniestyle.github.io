---
layout: page
lang: de
title: FAQ
eyebrow: Häufige Fragen
lead: Antworten zu Bestellung, Downloads, Größen und digitalen Produkten.
permalink: /de/faq/
en_url: /faq/
de_url: /de/faq/
---

## Allgemeine Fragen

{% for item in site.data[page.lang].faq %}
<details class="faq-item">
  <summary>{{ item.question }}</summary>
  <p>{{ item.answer }}</p>
</details>
{% endfor %}

## <span id="angebot-der-woche">Angebot der Woche</span>

Hier kannst du später dein wöchentliches Highlight, einen Rabatt oder ein ausgewähltes Etsy-Produkt bewerben.

- **Titel:** Noch offen
- **Aktionszeitraum:** Noch offen
- **Link zum Produkt:** Bitte ergänzen

## Kontakt

Falls deine Frage hier nicht beantwortet wird, kannst du in deinem Etsy-Shop auf eine Kontaktmöglichkeit oder ein Nachrichtenformular verweisen.