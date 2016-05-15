# firebase-input

`<firebase-input>` wraps a Firebase document value in a paper-input for editing

[API Docs and Demo](https://heka-house-firebase-input-demo.firebaseapp.com/)

[Source](http://github.com/hekahouse/firebase-input/)

The label is set to the path of the value.

## Example
    <template is="dom-repeat" items="{{LEAVES}}" as="LEAF">
      <firebase-input
        firebase-root="https://YOUR-FIREBASE.firebaseio.com/COLLECTION/ITEM/LEAF"
        label="leaf"></firebase-input>
    </template>

In the above example replace YOUR-FIREBASE, COLLECTION, ITEM and LEAF-PATH with appropriate values from your Firebase.

LEAVES are a collection of the full paths to Firebase values ie:

    https://YOUR-FIREBASE.firebaseio.com/users/name/first-name

## Note

The Firebase document is initiaized once the firebase-root is provided.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-input depends only on standard polymer elements from Google

## Related

firebase-input is designed for use inside of [firebase-card](https://HekaHouse.github.io/firebase-card)
