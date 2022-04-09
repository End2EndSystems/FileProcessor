---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Upload Files
permalink: /upload-files/
---

Here you can upload you file to be processed

{% include styles/form-upload.html %}
{% include upload-files/upload.html %}

| File name          | Status         | Percentual    | Last Errors                 | Action      |
| ------------------ | -------------- | :-----------: | --------------------------- | :---------: |
| Csv File           | Validated      | 100%          | No errors                   | [Remove](#) |
| Fixed Length       | Failed         | 100%          | No Data Source Found        | [Remove](#) |
| Excel File         | Processing     |  45%          | Row #15 with error          | [Remove](#) |
| Newer Excel File 2 | Processing     |  12%          | Row #15 Field #5 with error | [Remove](#) |

<script type="text-html" id="tpl-file-details">
{% include upload-files/row-template.html %}
</script>

{% include upload-files/include-row.html %}