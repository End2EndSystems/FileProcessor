---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Envio de arquivos
permalink: files/uploads/
---

Envio de arquivos(s).

Se o nome do arquivo for compatível com uma fonte de dados o mesmo será processado conforme a configuração definida.

{% include upload-files/upload.html %}

---

{% include upload-files/list.html %}

<script type="text-html" id="tpl-file-details">
    {% include upload-files/row-template.html %}
</script>

{% include upload-files/include-row.html %}