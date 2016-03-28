#Introduction
**SASS-SMACSS** is a style-guide and workflow i personally use to make front end development easier using **SMACSS** principles and **SASS**. It basically helps you write sass in a more organised way.

A basic-level understanding of **SASS** and **SMACSS** architecture is needed, To get started with **SMACSS**, visit [SMACSS](http://www.smacss.com).

#Basic Usage
##Structure

* config.rb
* css
  * styles.css
* scss
  * base
    * _clearfix.scss
    * _defaults.scss
    * _index.scss
    * _normalize.scss
  * helpers
    * _index.scss
    * _mixins.scss
    * _variables.scss
  * layout
    * _container.scss
    * _extends.scss
    * _grid.scss
    * _index.scss
  * modules
    * _buttons.scss
    * _extends.scss
    * _forms.scss
    * _images.scss
    * _index.scss
    * _nav.scss
  * state
    * _index.scss
  * styles.scss

.
+-- _config.yml
+-- _drafts
|   +-- begin-with-the-crazy-ideas.textile
|   +-- on-simplicity-in-technology.markdown
+-- _includes
|   +-- footer.html
|   +-- header.html
+-- _layouts
|   +-- default.html
|   +-- post.html
+-- _posts
|   +-- 2007-10-29-why-every-programmer-should-play-nethack.textile
|   +-- 2009-04-26-barcamp-boston-4-roundup.textile
+-- _data
|   +-- members.yml
+-- _site
+-- index.html
