# AutoUserBGs
Automated version of UserBGs where anyone can add a background almost instantly, without manual approval.

if there ever will be manual approval, it will be minimal and require one click to aprove.

the backend will be open source

## Importing
to import AutoUserBGs into your theme, use
```css
/* Base UserBGs */
@import url("https://discord-custom-covers.github.io/usrbg/snippets/modals.css");
@import url("https://discord-custom-covers.github.io/usrbg/snippets/userPopouts.css");

/* AutoUserBGs */
@import url("https://0j3-2.github.io/AutoUserBGs/publicvars.css");
```

To import just the variables, and handle the rest yourself, use
```css
/* UserBGs */
@import url("https://discord-custom-covers.github.io/usrbg/dist/usrbg.css");

/* AutoUserBGs */
@import url("https://0j3-2.github.io/AutoUserBGs/publicvars.css");
```
## Adding UserBGs
We **STRONGLY** recommend waiting for my website to have the ability to add them directly, but until then, you can clone https://github.com/0J3-2/Aurora/tree/master/scss/UserBGs/0J3.scss into a new file in https://github.com/0J3-2/Aurora/tree/master/scss/UserBGs, and submit a pull request. This requires some knowledge of CSS though.
