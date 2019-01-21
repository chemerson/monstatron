---
layout: tag
sidebar:
  - title: "Title"
    image: http://placehold.it/300x200
    image_alt: "image"
    text: "Some text here."
  - title: "Another Title"
    text: "More text here."
    nav: sidebar-sample

gallery:
  - url: ./assets/img/ac.png
    image_path: ./assets/img/ac.png
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: ./assets/img/ac.png
    image_path: ./assets/img/ac.png
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: ./assets/img/ac.png
    image_path: ./assets/img/ac.png
    alt: "placeholder image 3"
    title: "Image 3 title caption"

gallery2:
  - url: https://flic.kr/p/8a6Ven
    image_path: https://farm2.staticflickr.com/1272/4697500467_8294dac099_q.jpg
    alt: "Black and grays with a hint of green"
  - url: https://flic.kr/p/8a738X
    image_path: https://farm5.staticflickr.com/4029/4697523701_249e93ba23_q.jpg
    alt: "Made for open text placement"
---

Section 1.10.32 of "de Finibus Bonorum et Malorum", written by Cicero in 45 BC

![ac](./assets/img/ac.png) Where does this end up? Right under the picture, but is it a caption

{% include gallery id="gallery" caption="This is a sample gallery with **Markdown support**." %}
{% include gallery id="gallery2" layout="half" caption="This is a second gallery example with images hosted externally." %}
{% include figure image_path="./assets/img/ac.png" alt="this is a placeholder image" caption="This is a figure caption." %}

