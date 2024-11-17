---
title: "Grassy Fields Guide"
slug: "grassy-fields-guide"
layout: "single"
heroStyle: "background"
showHero: true
---
<iframe width="100%" height="576" src="https://maphub.net/embed_h/rLZ6kQntzMt34k3U?panel=1&panel_closed=1&geolocation=1&directions=1&autoplay=1" frameborder="0" allow="geolocation"></iframe>

[Here are the icons you can use](https://blowfish.page/samples/icons/ "icons")

The built-in icons aren't very helpful to me. So here's more about how to start setting your own:

>Additionally, custom icons are also fully supported. Simply provide your own SVG icon assets by placing them in the assets/icons/ directory in the root of your project. Any icons in the icons directory will then be available to use throughout the theme. In order achieve automatic color filling every SVG path needs fill=“currentColor” XML attribute.

- to include images you MUST use the figure shortcode, not a markdown syntax.

[Free font awesome icons](https://fontawesome.com/search?q=free&o=r&m=free "Free font awesome icons")

{{< timeline >}}

{{< timelineItem icon="github" header="The first route waypoint: Red Chair Lookout" badge="734 m" subheader="This is Williams Lake, a nice place to site and just BE for a while." >}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus non magna ex. Donec  sollicitudin ut lorem quis lobortis. Nam ac ipsum libero. Sed a ex eget ipsum tincidunt venenatis quis sed nisl. Pellentesque sed urna vel odio consequat tincidunt id ut purus. Nam sollicitudin est sed dui interdum rhoncus. 
{{< /timelineItem >}}


{{< timelineItem icon="code" header="Another Awesome Header" badge="date - present" subheader="Awesome Subheader" >}}
This is the where the image is supposed to be. I've found that the ONLY way to have an image show up is to use the figure shortcode.

{{< figure
    src="gate.jpg"
    alt="Abstract purple artwork"
    caption="Photo by [Jr Korpa](https://unsplash.com/@jrkorpa) on [Unsplash](https://unsplash.com/)"
>}}


{{< /timelineItem >}}

{{< timelineItem icon="star" header="Shortcodes" badge="AWESOME" >}}
With other shortcodes
{{< youtube-enhanced id=7PP7FDrDJKA title="The youtube video" allowFullScreen=true loading=lazy controls=true >}}

{{< /timelineItem >}}

{{< timelineItem icon="code" header="Another Awesome Header">}}
{{< github repo="nunocoracao/blowfish" >}}
{{< /timelineItem >}}

{{< /timeline >}}
