hi<small>(c) 2021 - 2023 RENware Software Systems</small>

**Learning @ RENware Software Systems Knowledge Base**

* Last released version: #FIXME what was the last one?

***

[TOC]

# CHANGELOG

<small>

* For version code structure meaning see SDEVEN methodology document (*sic !*) :).
* with (F) are marked those changes that are features in order to be copied in a RELNOTE file
* -#NOTE ____ PUBLISHING IS MADE ON `learning.renware.eu`:
    * FROM `PUBLISHING` BRANCH, wheen committed
</small>


## 2.0 ArtK new re-branded portal @ `learning.renware.eu`


### 2.0.1-beta ready articles linked as-is from old portal


-#TODO---------------------[START]--- short action plan

* tbd... use Jinja data loaded in Markdown to show different info ref any learning item - following things could help:
   * use JS inside Markdown file (if ok, retain as separated file in SCTRATH area to replicate in `RENpo`)
   * just use as simple Jinja variables adn multiply it with constructs like `{% for ... %}`
* tbd... get JSON article data and load it as Jinja info that can be used in Markdown files
* tbd... `about.md` page - section for who we are, project, team? and REN-TLP product license
* tbd... continue "Learning Catalog" (`learning_catalog.md`) page
* tbd... put `[TOC]` on Learning Catalog page

-#TODO---------------------[END]--- short action plan

* wip...



### 2.0.0-beta re-constructed old portal skeleton on new structure (#FIXME_wip...)

* 230726piu_j made "Learning Catalog" dedicated page & entry
* 230726piu_i create skeleton (wip style) for `about.md` page
* 230726piu_h clarified license - will be only in "Learning Catalog" - in top navbar does not appear anything ref materials and ref RENware is in footer
* 230726piu_g made "Learning Catalog" dedicated page & entry and dedicated top nav entrya
* 230726piu_f update `index.md` and transform in a Home page (SDEVEN like)
* 230726piu_e update product logon (in mkdocs.yml) with uploaded pictures in `230726piu_d`; refactored navigation structure

* 230726piu_d created and uploaded in `doc_src/pictures/`  REN-learn logo (source `fodg` & `png` types)
* 230726piu_c get from TLP project pictures with `confused1.gif` & `notebook.jpg` and uploaded in `doc_src/pictures/`
* 230726piu_b updated master index and structure (mkdocs.yml)
* 230726piu_a updated and improved master index page to show what is happening in this platform by categories: articles, books, courses, etc...
* 230725piu_b initializing `mkdocs` generator
    * adjust `mkdocs.yml` for a fresh start (it was imported from SDEVEN)
    * built environment for `mkdocs` run & build static site
    * made a master `index.md` file, useful just to test `mkdocs` right configuration
* 230725piu_a started `learning.renware.eu` project and initialized for **`artk` Articles**


