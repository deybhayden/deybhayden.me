# deybhayden.me

My personal website built with [hugo](https://gohugo.io/) using the [anatole](https://github.com/lxndrblz/anatole) theme.

## usage

```bash
brew install hugo
hugo server -D
```

## deploy

I host my site on [Firebase](https://console.firebase.google.com/?pli=1) - follow [these steps](https://gohugo.io/hosting-and-deployment/hosting-on-firebase/) to deploy the hugo-generated assets.

Only run these if you haven't deployed via Firebase before:

```bash
firebase login
firebase init
```

Then to deploy:

```bash
hugo && firebase deploy
```
