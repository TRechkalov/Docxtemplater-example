# Docxtemplater-example
This repository contains minimal docxtemplater usage in web browser (Checked in FF and CH. IE is not working).

It can help you in next way:

1. Minimal example of docxtemplater usage.

2. Download docxtemplater js file + dependencies. It is based on v1.0.0-beta. Or use npm to build it.

Docxtemlater can generate docx and pptx files from templates.
Full information is [here](https://github.com/open-xml-templating/docxtemplater)

When I tried to get minimal example I meet several problems.

1. docxtemplater release is just a source code archive. There is no copy-paste js files to attach it in browser page.

2. I can't extract js file from [Demo site]( http://javascript-ninja.fr/docxtemplater/v1/examples/demo.html) because 
it has some built-in style settings so it will spoil all textareas in my project.

3. You need to install nodejs to install npm to build docxtemplater and finally get docxtemplater.js.

You need to solve all these problems just to see does it work at all.

I make a minimal example of docxtemplater usage.

Steps to use:

1. Add json data to texarea

2. Load docx template

3. ...javascript magic happens...

4. Downloading ready docx

The very first example is taken [from original repository](https://github.com/open-xml-templating/docxtemplater/tree/master/examples) 
and included in this repository. There are more examples in original repository which you can test.

Thanks to docxtemplater authors)
