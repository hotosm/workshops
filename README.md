# OSM Workshops

This is a repository for workshop related information for planning, coordinating, and linking. Each folder contains documents, images, PDFs, and general information on a workshop. Use the wiki for drafts and ideas, move into markdown documents to solidify and archive workshop documentation and materials.

Access at [hotosm.github.io/workshops/](https://hotosm.github.io/workshops/)

### Long term vision

Longer term vision is that each folder can be a small microsite for a workshop. 

### To add a new workshop

Content is managed within markdown files and displayed directly on the page. Uses [zero-md](https://zerodevx.github.io/zero-md/) to render the markdown file within the page. Work in progress and as always open for other suggestions.

Style assets are located in `/assets/css` folder. Each workshop page has a separate `index.html` file that references a `README.md` or other file defined by:

```
<!-- Edit your Markdown URL file location here -->
<zero-md file="workshops.md">
	<div class="md-html"></div>
</zero-md>
```
