# Deployment Guidance

## Setup on a new machine

1. Setup Virtual Environment
    
    virtualenv env
    source env/bin/activate
    pip install -r requirements.txt
    
2. Generate publication lists

    python manage.py genpublications

## Semantic-ui

See [here] (http://semantic-ui.com/introduction/build-tools.html) for a 
complete list of components.
    

## Local Test

1. Switch to the test environment

    source env/bin/activate

## Thanks

1. `font-face` resources:
   [CSS-Trick](https://css-tricks.com/snippets/css/using-font-face/) and 
   `font-face generator` on [FontSquirrel](http://www.fontsquirrel.com).
