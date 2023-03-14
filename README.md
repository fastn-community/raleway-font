# Raleway : FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Raleway]https://fonts.google.com/specimen/Raleway/about?query=ralew).

Raleway is an elegant sans-serif typeface family. Initially designed by Matt McInerney as a single thin weight, it was expanded into a 9 weight family by Pablo Impallari and Rodrigo Fuenzalida in 2012 and iKerned by Igino Marini. A thorough review and italic was added in 2016.

It is a display face and the download features both old style and lining numerals, standard and discretionary ligatures, a pretty complete set of diacritics, as well as a stylistic alternate inspired by more geometric sans-serif typefaces than its neo-grotesque inspired default character set.



Designers: Matt McInerney, Pablo Impallari, Rodrigo Fuenzalida

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/raleway-font).

TLRD:

Include fifthtry.github.io/raleway-font package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/raleway-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/raleway-font/assets as raleway

;-- fpm.type.headline-small: $raleway.fonts.Raleway
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `Raleway` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Raleway  Font is under [OFL](https://fonts.google.com/specimen/Raleway/about?query=ralew), this FPM wrapper is also
under [OFL](LICENSE).




