# ALA Core Classroom:
## CollectionBuilder: A Static Web Approach to Digital Projects in Libraries

Repository to be used during the 2020 ALA Core Classroom Series.

Metadata for this workshop can be downloaded here: 
- [Psychiana Collection Demo Metadata](https://drive.google.com/open?id=1x48Te3duPAxh53foEihQVKTfCKUjaCCbH7TrMMd_yU4)

The digital objects described by the metadata (including image files, pdfs, and mp3s) are already in this repository (in the `objects` directory), so you don't need to upload them. 

Two demo metadata sets are available for use as you're learning. Both are drawn from the following University of Idaho digital collection:
- [Psychiana Digital Collection](https://www.lib.uidaho.edu/digital/psychiana/)
- [Carleton Watkins Mine Interiors Collection](https://www.lib.uidaho.edu/digital/watkins/)

To use the Watkins material, copy [this spreadsheet](https://docs.google.com/spreadsheets/d/1mThECwBYaUdvUrSbc9d2wbjedpYyvVD89jJ15R-7Qmo/edit?usp=sharing)
The Watkins objects are already in the repository.

## Getting Started

Click the green "use this template" button above to get started. Create your template repository, then add the metadata and configure the repository to fit your collection and settings.

See [Getting Started Docs](https://collectionbuilder.github.io/docs/introduction.html) for detailed information. **Note:** 
Since `collectionbuilder-gh` uses [GitHub Pages](https://pages.github.com/), it is only suitable for small collections, with lower resolution images. GitHub repositories are limited to 1GB.

## More on CollectionBuilder

`collectionbuilder-gh` is intended as a simple template for hands-on teaching about digital libraries.
It can be used in a workshop setting to take participants through digitization and metadata creation, to having a live collection site hosted on GitHub.

`collectionbuilder-gh` aims to be well documented and easy to configure by following the example, with the potential to scaffold learning of a multitude of transferable digital and data skills.
A project in "minimal computing," it provides a depth of learning opportunities, allowing users to take complete ownership over the project and make their work open to the world.

Learn about:

- Git and GitHub basics
- [Markdown](https://guides.github.com/features/mastering-markdown/), plaintext writing and content creation
- HTML, CSS, and JS literacy
- commandline literacy
- GitHub collaboration and project management
- [Jekyll](https://jekyllrb.com/) basics
- working in the Open, open source and open data
- digital libraries concepts such as "collections as data", minimal computing, data-driven design

> We prefer commonly understood formats (such as CSV spreadsheets over YAML), and convention over configuration (follow the example over learn all the options).

## Features

- [Jekyll](https://jekyllrb.com/) for GitHub Pages 
- Layout using [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/).
- [jQuery](https://jquery.com/)
- Mapping using [Leaflet.js](http://leafletjs.com/)
- Tables using [DataTables](https://datatables.net/)
- Galleries using [lightGallery](http://sachinchoolur.github.io/lightGallery/)
- Simple [lunr](https://lunrjs.com/) search 
- Rich markup using [Schema.org](http://schema.org) and [Open Graph protocol](http://ogp.me/) standards.

## Build a Digital Collection! 

Check out the [CollectionBuilder-GH tutorial](https://collectionbuilder.github.io/collectionbuilder-gh/documentation/) for how to get started, or visit the [CollectionBuilder home](https://collectionbuilder.github.io/) for more information.

If you are interested in using CollectionBuilder, or are already using it, please drop us a line (**libstatic.uidaho@gmail.com**) since we would love to learn more about it's use in the wild. 
There are also currently opportunities to [collaborate on CollectionBuilder](https://collectionbuilder.github.io/about.html#the-grant).

## License

CollectionBuilder documentation and general web content is licensed [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/). 
This license does *NOT* include any objects or images used in digital collections, which may have individually applied licenses described by a "rights" field.
CollectionBuilder code is licensed [MIT](https://github.com/CollectionBuilder/collectionbuilder-gh/blob/master/LICENSE). 
This license does not include external dependencies included in the `assets/lib` directory, which are covered by their individual licenses.

## My notes
Serve site from different location with more than 1GB storage (limit for GH repos):
Digital Ocean Spaces offers 3 static sites for free
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-static-site-from-github-with-digitalocean-app-platform-quickstart
