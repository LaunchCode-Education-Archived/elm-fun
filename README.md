# Elm Fun

Project to teach coding to Geek Gala partiers

Built on elm-0.18.
Run with `elm-reactor` then navigate to http://localhost:8000

Maybe you want to browse the doc for https://package.elm-lang.org/packages/MacCASOutreach/graphicsvg/2.1.0/GraphicSVG

## Notes for improvement after first use - GeekGala 2018

Main idea: make things easier with less refactoring.

### Circular Trees
The geometry of converting from triangle-trees to circle trees is too hard! Either they need a diagram (my preference), or they need to have oval be a drop-in replacement for isocelese2 - like all they do is change the word.

### Draw a random thing

Give them some sketches of clouds, cats, spiders, etc.

### press 'r' for Reset

This was good

### Afterburner
Reset the rocket state to 'falling' if it's thrusting in a new
updater, then have the thrust key set it back to 'thrusting' when it's
pressed. That way when they copy-paste that line, the exhaust plume
graphic works as you'd expect.

### Crashing the Rocket

This challenge is too hard! Nobody did it.

## Install on LC Education Laptop

Open a shell then run this script

```
git clone https://github.com/LaunchCodeEducation/elm-fun.git
cd elm-fun
npm install --local elm@0.18.0
export PATH="`pwd`/node_modules/elm/binwrappers:$PATH"
elm-reactor
```

Then open Google Chrome (Safari won't cut the mustard) at http://localhost:8000/src/Scene.elm
