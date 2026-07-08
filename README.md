# Avrad Apps GitHub Pages Site

This folder contains a reusable static website for Avrad Apps.

It is designed to be copied into a GitHub Pages repository such as:

```text
avradapps.github.io
```

Important URLs after publishing:

```text
https://USERNAME.github.io/
https://USERNAME.github.io/app-ads.txt
https://USERNAME.github.io/hindi-panchang/privacy-policy.html
```

The `app-ads.txt` file is shared across apps that use the same AdMob publisher account.

To add a new app later:

1. Create a new folder, for example `new-app/privacy-policy.html`.
2. Link it from `index.html`.
3. Update `app-ads.txt` only if a new ad network or publisher account is added.
