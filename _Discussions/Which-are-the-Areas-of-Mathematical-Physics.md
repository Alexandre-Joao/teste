---
layout: default
title: "Which are the Areas of Mathematical Physics?"
date: 2026-04-12
author: "Alexandre"
author_url: "https://orcid.org/0009-0007-0034-5243"  
---

<!-- Capinha estilo artigo (igual ao exemplo que você mostrou) -->
<div style="margin-top: 40px; margin-bottom: 50px;">

  <h1 style="font-size: 2.6rem; margin-bottom: 12px; color: #ffffff;">
    {{ page.title }}
  </h1>

  <div style="color: #aaaaaa; font-size: 1.15rem; margin-bottom: 8px;">
    {{ page.date | date: "%d %b %Y" }}
  </div>

  {% if page.author_url %}
  <div style="color: #f4c430; font-size: 1.4rem; font-weight: 500;">
    <a href="{{ page.author_url }}" target="_blank" rel="noopener" style="color: #f4c430; text-decoration: none;">
      {{ page.author }}
    </a>
  </div>
  {% else %}
  <div style="color: #f4c430; font-size: 1.4rem; font-weight: 500;">
    {{ page.author }}
  </div>
  {% endif %}

</div>

<!-- === Seu conteúdo da página começa aqui === -->
<p>Esta página é um teste.</p>

<p>Aqui você pode começar a escrever o conteúdo da nota normalmente.</p>

<p>Exemplo de equação:</p>

$$ f'(x) = 2x $$
