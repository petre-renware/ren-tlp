hi<small>(c) 2021 - 2023 RENware Software Systems</small>

**Learning @ RENware Software Systems Knowledge Base**

* Last released version: #FIXME what was the last one?

***

[TOC]

# CHANGELOG

<small markdown>
* For version code structure meaning see SDEVEN methodology document (*sic !*) :).
* with (F) are marked those changes that are features in order to be copied in a RELNOTE file
* -#NOTE ____ PUBLISHING IS MADE ON `learning.renware.eu`:
    * FROM `PUBLISHING` BRANCH, wheen committed
</small>


## 2.0 ArtK new re-branded portal @ `learning.renware.eu`


### ___#FIXME_wip___ 2.0.2 Articles Catalog


-#TODO---------------------[START]--- short action plan

* tbd... use Jinja data loaded in Markdown to show different info ref any learning item - following things could help:
   * [ ] load `JSON` got in `230727piu_c` as Jinja info that can be used in Markdown files
   * [ ] use JS inside Markdown file (if ok, retain as separated file in SCRATCH area to replicate in `RENpo`)
   * [ ] just use as simple Jinja variables and multiply it with constructs like `{% for ... %}`

* tbd... continue "Learning Catalog" (`learning_catalog.md`) page

-#TODO---------------------[END]--- short action plan

* wip... last used 230727piu_f








### 2.0.1-beta ready articles linked as-is from old portal

* 230727piu_f "Learning Catalog" disclaimer and replace TODOs with "UPCOMING..." + transform them in HTML comments
* 230727piu_e finalize `about.md` page & put a picture in `learning_catalog.md` page
* 230727piu_d made first draft of `about.md` page - sections for who we are, project, team, ... and REN-TLP product license 
* 230727piu_c new directory `doc_src/data/` with JSON article data ref _`articles_register.json`_ and _`mb-apm-data/unit_01.json`_
* 230727piu_b plugin that enables displaying the date of the last git modification of a page:
    * [x] add [`mkdocs-git-revision-date-localized-plugin`](https://github.com/timvink/mkdocs-git-revision-date-localized-plugin)
    * [x] enable in `mkdocs.yml` section `plugins`: `- git-revision-date-localized`
* 230727piu_a put `[TOC]` on Learning Catalog page







### 2.0.0-beta re-constructed old portal skeleton on new structure

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










# Changelog history

<small markdown>The files are located in `versions_history/` directory and can be CHANGELOG(s) and RELNOTE(s) for different versions.</small>

* last `app_version` [1.1.28 RELNOTE](versions_history/1.1.28_relnote.md)

