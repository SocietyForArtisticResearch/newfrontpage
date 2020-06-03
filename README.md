# RC main pages redesign and restructruring 

## Motivation

* make journals and institutions easier to find.
* show sara announcements on a more prominent place.
* organise information pages in a more logical way.

We have moved the content of the sidebar to the footer.  The portals
and journals now have dedicated overview pages instead of being listed
on the frontpage.  There are two menus. The desktop (non-mobile)
version shows a navigation bar with the main pages and an account menu
icon. The responsive (mobile) version shows two menus, the navigation
bar is accessible through a hamburger menu.

This design (header and footer) is to be used for all RC pages except
of the editors.

## Structure

The redesigned landing page consists of 3 sections:
- header
- content 
- footer

The header and footer elements do not stick to the viewport, they may
be static.




### Header

The header contains:
   - search
   - (advanced search) register/login
   - about & help

The login should open in a new page containing different login options
and feide login, like the current "authentication required"-page.

#### Home

- Recent Activities
- Recent Publications
- Sar Announcements
  display title, subject sender and - header picture (<img id="result-headerImg" ...>)



  
#### Institutional Portals

- The non-journal portals


#### Tab: Journals


- We need a new portal setting that specifies whether a portal is a journal.

- Journals at the moment are: JAR, RUUKKU, VIS & Journal for Sonic Studies


#### Researchers 

- There is an option to filter by interest (keywords) and names.

   
### Footer

Contains a list of info pages, contact info etc. all of which should
be wrapped in the newly designed header and footer.  At the very
bottom, there is a single line for our hosting partner from Sweden.

## Mockup structure

The links do not work.  We have patched over the default RC styling,
the mockup CSS also contains responsive rules.

- ./css_patches/frontpage_patch.css
Contains patches of default RC styling.

- ./css_patches/style.css
Contains new rules for new content pages.
  

