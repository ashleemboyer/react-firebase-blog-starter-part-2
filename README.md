# react-firebase-blog-starter-part-2

## Changelog

### Monday, September 2nd, 2019

On the home page, I forgot to introduce a loading state to prevent `getFirebase` from being endlessly called. [A `loading` constant](https://github.com/ashleemboyer/react-firebase-blog-starter-part-2/blob/master/src/pages/home.js#L7), an [`if` statement using that constant](https://github.com/ashleemboyer/react-firebase-blog-starter-part-2/blob/master/src/pages/home.js#L10) to prevent multiple calls to Firebase, and an [`if` statement for returning a loading message](https://github.com/ashleemboyer/react-firebase-blog-starter-part-2/blob/master/src/pages/home.js#L28) have all been added to [`src/pages/home.js`](https://github.com/ashleemboyer/react-firebase-blog-starter-part-2/blob/master/src/pages/home.js).
