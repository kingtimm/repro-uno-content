# Content with Image

Attempting to use [Attributes](https://content.nuxtjs.org/guide/writing/mdc#attributes) from nuxt content..

The classes get applied to the items, but it looks like they aren't recognized in the uno.css unless the tag is outside of curly braces

I added a content filesystem reference in `uno.config.ts`.


## Case 1
[Padded text]{.px-8} this class was already in the css (has padding applied)

## Case 2
![beach image](/img/beach.jpg){.w-32.rounded} 

Because the word **rounded** is here, the rounded tag seems to be in the uno.css. However, the other tag on the image is only referenced in those curly braces and won't show up.