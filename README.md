# firebase-input

`<firebase-input>` wraps a Firebase document value in a paper-input for editing

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/firebase-input)

[Source](http://github.com/hekahouse/firebase-input/)

## Install

    bower install --save HekaHouse/firebase-input

## Example
    <firebase-input
      user="{{user}}"
      app="{{app}}"
      app-name="APP NAME FROM FIREBASE APP"
      firebase-branch="/path/to/document"
      label="some element"></firebase-input>

## Note

The Firebase document is initiaized once the user and app properties are provided.

These come from associated firebase-app and firebase-auth elements

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-input depends only on standard polymer elements from Google

including the pre-release [polymerfire](https://github.com/firebase/polymerfire)

## Related

firebase-input is designed for use inside of:

[firebase-card](https://heka-house-polymer-demos.firebaseapp.com/firebase-card)
