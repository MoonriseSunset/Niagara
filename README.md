# Niagara
## Base CSS File to build decent looking websites

As I started relearning CSS and HTML, I created a master CSS file and gradually added to it. Eventually, I would then apply this master CSS file in various capacities to my other website projects. Niagara is a more open version of such a file, a sort of base stylesheet which can be tweaked.

## Using Niagara:
I've split Niagara into two versions, ``NiagaraFull`` and ``NiagaraSimple``.

``NiagaraSimple`` has a few customizations broken out into variables at the top of the file. Generally this is good if you're new/only want to tweak little parts of it.

``NiagaraFull`` (WIP _maybe_) has most if not all of the parameters broken out into variables, giving you ***full*** control over the look of the site.

## Specs:

### **Fonts:**

- Roboto
- Oxygen
- Lato

### Theme:

Niagara directly imports the *Nord* theme instead of defining the color profiles within the file through variables. It does use a few other colors (pure black and white being two) outside of that, but otherwise everything is Nord.