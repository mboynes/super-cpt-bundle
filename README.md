# SuperCPT for TextMate/Sublime Text 2

## About

This is a snippet collection for working with the SuperCPT plugin for WordPress (http://wordpress.org/extend/plugins/super-cpt/)

## TextMate Installation


    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone https://github.com/mboynes/super-cpt-bundle.git SuperCPT.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'


## Sublime Text 2 Installation

Add this to your Sublime Packages directory.

## Instructions

This plugin gives you a few snippets for working with the SuperCPT WordPress plugin. Each one is a tab trigger.

* `scpt`:
  Add a filter for `after_setup_theme` and check to see if this plugin exists
* `cpt`:
  Add a new Super Custom Post Type
* `tax`:
  Add a new Super Custom Taxonomy
* `amb`:
  Add a new meta box for your Super Custom Post Type
* `ctat`:
  Connect one or more Post Types with one or more Taxonomies
* `icon`:
  Add an icon for your Custom Post Type
* `cpm`:
  Create a new Super_Custom_Post_Meta object around an existing post type (e.g. posts)


## Author

**Matthew Boynes**

* http://twitter.com/senyob
* http://github.com/mboynes


## Copyright and license

Copyright 2012 Matthew Boynes

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.