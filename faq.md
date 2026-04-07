---
layout: page
lang: en
title: FAQ
eyebrow: Frequently asked questions
lead: Answers about orders, downloads, sizes, and digital products.
permalink: /faq/
en_url: /faq/
de_url: /de/faq/
---

## General questions

{% for item in site.data[page.lang].faq %}
<details class="faq-item">
  <summary>{{ item.question }}</summary>
  <p>{{ item.answer }}</p>
</details>
{% endfor %}

## <span id="weekly-offer">Offer of the week</span>

Use this section to highlight a weekly favorite, a discount, or a selected Etsy product.

- **Title:** To be added
- **Promotion period:** To be added
- **Product link:** Please add

## Contact

If your question is not answered here, you can direct visitors to the contact option or message form in your Etsy shop.
