# Design Languages
We use standard HTML5 tags, attributes and rules! In many cases you just need write standard html in semantic way and don't think about styling!!
- https://html.spec.whatwg.org/multipage/
- http://w3c.github.io/html/dom.html#allowed-aria-roles-states-and-properties

## Information architecture
### Semantic content
We always care to write content in semantic way by all resources.
- https://html.spec.whatwg.org/multipage/
- https://www.w3.org/TR/rdfa-core/
- https://www.w3.org/TR/rdfa-lite/
- https://schema.org/
- https://search.google.com/structured-data/testing-tool

## Supported languages
We still hard work to complete exiting languages and add more languages with complete guides!
- [Ant](http://Ant.design)
- [Flat]()
- [Fluent](https://www.microsoft.com/design/fluent/)
- [IBM](https://www.ibm.com/design/language/)
- [Material](https://material.io/)
- [Semantic](https://semantic-ui.com/)
- [US-DS](https://designsystem.digital.gov/)

## Browser User Agent Stylesheets
- Mozilla Firefox: https://dxr.mozilla.org/mozilla-central/source/layout/style/res/html.css
- Google Chrome: https://chromium.googlesource.com/chromium/blink/+/master/Source/core/css/html.css
- Safari (WebKit): https://trac.webkit.org/browser/trunk/Source/WebCore/css/html.css
- Internet Explorer: You can't view Internet Explorer's UA Stylesheet because it's not open source.
- Servo (Firefox): https://github.com/servo/servo/blob/master/resources/user-agent.css

## Usage
### Project
We strongly suggest use git submodule instead of any package manager by below command! [Read more about git submodule here](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
- Add: `git submodule add https://github.com/SabzCity/design-languages`
- Clone: `git clone ...` and after call `git submodule init`
- Update: `git submodule update --remote`

### HTML
Easily add desire design language to your HTML file like
```HTML
<link rel="stylesheet" type="text/css" href="/design-languages/design-language--material.css">
<link rel="stylesheet" type="text/css" href="/design-languages/theme-light.css">
```
Also you can use gui-engine-js concept in gui.sabz.city to load dynamically user selected design language and theme!

## Production Ready!?
This package is under development and not ready to use in real production. It can have breakable changes until we remove this part from README!
But we are glad to hear your experience or idea about this concept.