

![website](https://github.com/alpiepho/css-grid-resume/workflows/website/badge.svg)

## CSS Grid Resume Template


:construction: WORK IN PROGRESS 


Deployed on GitHub pages [here](https://alpiepho.github.io/css-grid-resume/).

A concrete example of my own resume can be found [here](https://github.com/alpiepho/css-grid-resume-mine).

This is a responsive web application, with different formatting for various
size displays.  For Mobile, the site is displayed mostly veritical.  For
web browsers, it is a normal page with some action buttons (possibly a drop down in the furure).  For printing, the action buttons are removed, etc.

My hope is that the origianl template and this concrete example will be useful for others to copy/clone and add their own online resume.

## Cloning/Copying Project

This project uses a very simple Github Actions script.  When you first commit it to your
own GitHub project it will fail.  This is because you need to generate and install your
own PERSONAL_TOKEN.  

To generate a PERSONAL_TOKEN:
- click on your user icon in the top right of GitHub page:, select settings
- on lower left, select 'Deveoper settings'
- on left, select 'Personal acces tokens'
- use button 'generate new token'
- you will need to enter password for GitHub
- name this token the same as the GitHub project
- select 'repo' permissions
- copy the key (don't close window until the install is done, you might need to go back)

To install a PERSONAL_TOKEN:
- navigate to your Github project
- select 'Settings' tab
- on left, select 'Secrets'
- add new Secret
- name it PERSONAL_TOKEN
- copy/paste token from generation above

Test GitHub Action:
- Change something and push
- I find it easiest to use GitHub page and edit README.md (add a line)
- If it passes, you can close generation window



## Background

The idea for this started from a blog post on CSS Tricks [here](https://css-tricks.com/new-year-new-job-lets-make-a-grid-powered-resume/).

As I was starting from that example, other sites/examples were found.  One that was
bven better is the code pen referenced.  It is layed out differently.
[here](https://codepen.io/alichur/embed/bGNGGNP?height=367&theme-id=1&default-tab=result&user=alichur&slug-hash=bGNGGNP&pen-title=grid%20resume%20%20swapping%20sections&name=cp_embed_2).

## My onging TODO List and Ideas

- consider using apline.js for any dynamic stuff https://github.com/alpinejs/alpine
- adjust based on media size
- change px to rem
- BONUS: easteregg animation


## References

How to use :before to add bullets
https://www.w3.org/Style/Examples/007/color-bullets.en.html

Used https://stackoverflow.com/questions/54791658/vertical-divider-as-pseudo-element-with-css-grids
for seperators

Used this for gh-pages (used the script only for now, with change to PUBLISH_DIR)
https://github.com/peaceiris/actions-gh-pages


