## fairlyfunctional.io blog repo

Uses firebase for hosting. Local firebase config is:

    ~/.config/configstore/firebase-tools.json

Hosting setup described [here](https://medium.freecodecamp.org/hugo-firebase-how-to-create-your-own-dynamic-website-for-free-in-minutes-463b4fb7bf5a).

Test in dev mode:

    hugo -D server

Deploy (make sure to remove draft flags):

    hugo && firebase deploy
