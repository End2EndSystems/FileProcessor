---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Fonte de Dados - Arquivo CSV
permalink: /files/data-sources/Csv-File/Fields/
---

{% include data-sources/manage/fields/wizard-data-source-fields.html %}

---

Toda a fonte de dados possuem campos a serem extraídas informações.

{% include link-button.html icon="bi-file-earmark-plus" label="Novo campo" %}

<div class="tab-content py-3" id="data-source-configuration-tabs">
    <div class="tab-pane fade show active" id="basic-info" role="tabpanel" aria-labelledby="basic-info-tab">
        {% include data-sources/manage/fields/list.html %}
    </div>
</div>

{% include link-button.html icon="bi-file-earmark-plus" label="Novo campo" %}

{% include link-button.html icon="bi-arrow-left-short" label="Voltar a lista de Fonte de Dados" url="/files/data-sources" %}
