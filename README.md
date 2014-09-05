# gaffa-container

Basic container view for [Gaffa](https://github.com/gaffa-tape/gaffa)

This view should not be used directly, but instead should be inherited be other views.

## Install:

    npm i gaffa-container

## Add to gaffa:

    gaffa.registerConstructor(require('gaffa-contianer'));

# API

## Rendering

By default, gaffa-container will render a ```<div>```

You can override ```.tagName``` to render other content elements
