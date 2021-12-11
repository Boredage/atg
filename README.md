# All the Guides
This repository is for the All the Guides website. 

The website utilizes github pages and the technologies it provides, including:

Jekyll
Sass/CSS
HTML


The main site is the Gameplay Guides. There is also a 'troubleshooting' section for launching the game and server related issues.

The _config.yml in the root directory contains a few things you need to change. Primary the baseurl and url.

Mods can be added to the game guides in two steps. First the mod must be added to the _data/gameguides-mods.yml file (this will add it to the navigation) then in /gg you will have to add a page that uses the layout for mods and add your content. Use one of the other pages in the directory as a template.

Question and answers to the FAQ section can be added to:
_data/gameguides-faq.yml for the game guides faq
_data/troubleshooting-faq.yml for the troubleshooting section.
_data/spellbound-faq.yml


Notes:
Most images were moved to my hosting to save on space. Should it go down the site will still work but may look a little funky but still be functional 