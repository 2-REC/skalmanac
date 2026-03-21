---
#TODO: determine which to use ("image" or "ratio", depending in image) (or "fixed"?)
# +adapt
header:
  - type: single-image
    fit: image
    image:
        src: images/header/band.jpg
        #caption: musicians
        #copyright: "2-REC"
    alignX: center
    alignY: top
    paddingX: 0
    paddingY: 0
    title:
      - "The Ska Exploration Project"
    subtitle:
      - "From Roots to Rude"
    titleColor:
    titleShadow: true
    titleFontSize: 25%
    subtitleColor:
    subtitleShadow: true
    subtitleCursive: true
    subtitleFontSize: 10%
    spaceBetweenTitleSubtitle: 10%

  - type: single-ratio
    fit: ratio
    height: 25%
    image:
        src: images/header/background.png
        size: cover
        repeat: no-repeat
        position: center
        caption: TEst
        copyright: "No rights reserved"
    alignX: center
    alignY: center
    paddingX: 0
    subtitlePaddingY: 10%
    paddingY: 0
    title:
      - HUGO
    subtitle:
      - The world's fastest framework for building websites
    titleColor:
    titleShadow: true
    titleFontSize: 50%
    subtitleColor:
    subtitleShadow: true
    subtitleCursive: true
    subtitleFontSize: 10%
    spaceBetweenTitleSubtitle: 10%
---
