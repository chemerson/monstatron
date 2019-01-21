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


---
{% include gallery id="gallery" caption="This is a sample gallery with **Markdown support**." %}
{% include gallery id="gallery2" layout="half" caption="This is a second gallery example with images hosted externally." %}

Section 1.10.32 of "de Finibus Bonorum et Malorum", written by Cicero in 45 BC

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

![ac](./assets/img/ac.png) Where does this end up? Right under the picture, but is it a caption

{% include figure image_path="./assets/img/ac.png" alt="this is a placeholder image" caption="This is a figure caption." %}

