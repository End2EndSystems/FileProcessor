---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

## File Processor System

Create data sources for your files, based on a file layout.

Work with CSV, Fixed Length or Excel files.

Change the final value of fields using the transformations.

### What do you want to do

## [Work With Data Sources]({{ 'files/data-sources' | prepend: site.baseurl }})

Create, edit and delete data sources.
Configure fields for your data sources.
Add transformations for the files (set, replace, or work with dates values)

## [Upload Files]({{ 'files/upload' | prepend: site.baseurl }})

Upload files and go take a coffee, the system works in asynchronous way.
It will identify the data source pattern
Will process each line and each fields, according the data source fields and transformations configured.
Follow the process, see error messages.

## [Files Results]({{ 'files/results' | prepend: site.baseurl }})

After upload process
Edit the resulting values as you wish
Download a final file in a csv format.
