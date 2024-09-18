# a5x5

The ultimate smallest bitmap variable-width font that can be comfortably read from a distance.

This font is designed for use in systems with displays extremely limited in resolution and pixel density.

## Character Set

Since the available canvas space is so limited, we can only implement so many characters. However, as this font is primarily meant to serve as the smallest available font on a scientific calculator, we can guarantee that there will be lots of mathematical symbols and Greek letters in the first release.

### Completeness

Take a look at [TODO.md](./TODO.md).

## Variability

* Character height usually meets, but shall never exceed, 5 pixels.
* Character width ranges from 3 to 5 pixels depending on its visual complexity.
* Characters (like lowercase G and Y) which have elements under their "main spaces" are not given any underspace and always fit within the same line.

## Contributors

* twisted_nematic57
* fghsgh for her very insightful input and some contributions to the Greek letters

## Licensing

Public domain :)
