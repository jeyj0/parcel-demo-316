# Parcel Demo for Issue 316

This project was created as a demo project for issue number 316 in the parcel-bundler project. (https://github.com/parcel-bundler/parcel/issues/316)

## Tests

There are three commits, each containing a different setup to test whether this is still an issue. The fourth commit contains this readme.

To execute the test for yourself, simply run `$ npm install` followed by `$ npm start`. If the test succeeds there should be a dist/-folder created containing a png image, which is loaded as background-image for the div#test when opening http://localhost:1234/. Otherwise the test failed.

### Testcase 1

Test failure (still an issue)

First commit

I have copied the dependencies from the original issue and used the current parcel version to see if the issue was still occuring in a minimalistic setup. And indeed it did.

### Testcase 2

Test failure (still an issue)

Second commit

I used the same dependencies as in Testcase 1, but updated node-sass to the newest current version (4.9.3).

### Testcase 3

Test failure (still an issue)

Third commit

I updated the rest of the dependencies to their respective current version as of time of this writing.
