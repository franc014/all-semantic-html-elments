---
element: area
description: Defines an area inside an Image Map. It only works within the map element
doclink: https://html.spec.whatwg.org/multipage/image-maps.html#the-area-element
---

<p class="mb-2">Role with href: Link</p>
<p class="mb-2">Role without href: Generic</p>

<h3>Example:</h3>

<map name="landscape" >
    <area  shape="rect" coords="0 0 198 150"
    href="https://es.wikipedia.org/wiki/Volc%C3%A1n_Pichincha"
    target="_blank"
    alt="Guagua Pichincha"
    >
    <area  shape="rect" coords="198 0 400 150"
    href="https://es.wikiloc.com/rutas-senderismo/cubilche-20912963"
    target="_blank"
    alt="Cubilche">
    <area  shape="rect" coords="0 198 198 400"
    href="https://es.wikipedia.org/wiki/Quilotoa"
    target="_blank"
    alt="Quilotoa">
    <area  shape="rect" coords="198 198 400 400"
    href="https://ecuventure.com/es/mountains/cerro-puntas/"
    target="_blank"
    alt="Puntas">
</map>

<img  usemap="#landscape" src="/images/mountains.png" alt="All mountains">
