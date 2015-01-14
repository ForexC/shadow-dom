# Multiple Shadow Roots

### [Live Demo](http://wilsonpage.github.io/shadow-dom/multiple-shadow-roots)

## Issues:

1. The `<style>` of the first shadow-root doesn't seem to be taking affect on the second (differs from Chrome).
2. The `<content>` insertion point in the first shadow-root doesn't seem to be filled with the light-dom content by default, `<shadow><content></content></shadow>` is required (not demoed). This differs from Chrome's behaviour explained in [this article](www.html5rocks.com/en/tutorials/webcomponents/shadowdom-301/#toc-shadow-insertion). View the 'Live Demo' in that section of the article in both Chrome and Firefox.
