---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Upload Files
permalink: files/uploads/
---

Upload file(s), if found a data source based on file name process the file(s).

{% include upload-files/upload.html %}

---

{% include upload-files/list.html %}

<script type="text-html" id="tpl-file-details">
    {% include upload-files/row-template.html %}
</script>

{% include upload-files/include-row.html %}