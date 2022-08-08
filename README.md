
# NewTab Searchpage for Chrome


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [NewTab Searchpage for Chrome](#newtab-searchpage-for-chrome)
  - [Installation](#installation)
    - [In Vivaldi Browser](#in-vivaldi-browser)
  - [Refs](#refs)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# NewTab Searchpage for Chrome

Make the NewTab page in Chrom(e|ium)-based browsers show search fields for your most used search engines and websites

## Installation

### In Vivaldi Browser

* clone or download this repo
* open [extensions page (`vivaldi://extensions/`)](vivaldi://extensions/)
* switch on `Developer mode`
* click on `Load unapcked` button
* navigate to the directory where you unpacked this repo, chose `Select`
* go to [Vivaldi settings (`vivaldi://settings/all/`)](vivaldi://settings/all/)
* search for `New Tab Page`
* activate entry `Start Page > Controlled by Extension`
* hit `ctrl+t` to see whether it works

**To Do**

* The above will make history show blank page
* apply patch https://forum.vivaldi.net/topic/15528/how-to-make-your-startpage-newtab-extension-work-again/2
* in short, install extension
* copy ID of extension
* then choose New Tab Page > Enter address
* enter `chrome-extension://moifjngbhhfpfnkjghanopgconaepajl/main.html`
* replace `moifjngbhhfpfnkjghanopgconaepajl` with the ID you copied

## Refs

* https://blog.lateral.io/2016/04/create-chrome-extension-modify-websites-html-css/





