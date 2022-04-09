---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Upload Files
permalink: files/uploads/
---

Here you can upload you file to be processed

> Important
>
> If you leave this upload page before send the files (using the 'Add files to upload button')
> you will lost the current work, and the process will start again
> 
> If after the processing files you do not click on 

{% include styles/form-upload.html %}
{% include upload-files/upload.html %}

{% include upload-files/proceed-button.html %}

| File name          | Status         | Percentual    | Last Errors                 | Action      |
| ------------------ | -------------- | :-----------: | --------------------------- | :---------: |
| Csv File           | Validated      | 100%          | No errors                   | [Remove](#) |
| Fixed Length       | Failed         | 100%          | No Data Source Found        | [Remove](#) |
| Excel File         | Processing     |  45%          | Row #15 with error          | [Remove](#) |
| Newer Excel File 2 | Processing     |  12%          | Row #15 Field #5 with error | [Remove](#) |

{% include upload-files/proceed-button.html %}

<script type="text-html" id="tpl-file-details">
{% include upload-files/row-template.html %}
</script>

{% include upload-files/include-row.html %}