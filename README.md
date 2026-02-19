# Awesome Web Components [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

A curated list of awesome Web Components resources.

> **Note**
> This project was previously named "Web Components the Right Way"

[Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components) — a suite of different technologies allowing you to create reusable custom elements — with their functionality encapsulated away from the rest of your code — and utilize them in your web apps.

## Contents

* [Introduction](#introduction)
* [Standards](#standards)
  * [Custom Elements](#custom-elements)
  * [Shadow DOM](#shadow-dom)
  * [HTML Templates](#html-templates)
  * [CSS Shadow Parts](#css-shadow-parts)
* [Guides](#guides)
  * [Accessibility](#accessibility)
  * [Best Practices](#best-practices)
  * [Codelabs](#codelabs)
  * [Examples](#examples)
* [Articles](#articles)
  * [Architecture](#architecture)
  * [Interoperability](#interoperability)
  * [Limitations](#limitations)
  * [Styling](#styling)
* [Real World](#real-world)
  * [Case Studies](#case-studies)
  * [Components](#components)
  * [Component Libraries](#component-libraries)
  * [Design Systems](#design-systems)
  * [Use Cases](#use-cases)
* [Libraries](#libraries)
  * [Class Based](#class-based)
  * [Functional](#functional)
  * [Integrations](#integrations)
  * [Benchmarks](#benchmarks)
* [Frameworks](#frameworks)
  * [Angular](#angular)
  * [React](#react)
  * [Vue](#vue)
  * [Svelte](#svelte)
* [Ecosystem](#ecosystem)
  * [Meta Frameworks](#meta-frameworks)
  * [Starter Kits](#starter-kits)
  * [Testing Solutions](#testing-solutions)
  * [Tools](#tools)
* [Books](#books)
* [Tutorials](#tutorials)
* [Insights](#insights)
  * [Podcasts](#podcasts)
  * [Presentations](#presentations)
  * [Talks](#talks)
* [Usage Metrics](#usage-metrics)
* [Proposals](#proposals)
  * [Form-associated Custom Elements](#form-associated-custom-elements)
  * [Constructable Stylesheet Objects](#constructable-stylesheet-objects)
  * [Custom State Pseudo Class](#custom-state-pseudo-class)
* [Miscellaneous](#miscellaneous)
* [Archive](#archive)
  * [Polyfills](#polyfills)
  * [History](#history)
* [Who To Follow](#who-to-follow)
* [Maintainers](#maintainers)

## Introduction

* [An Introduction to Web Components](https://css-tricks.com/an-introduction-to-web-components/)
* [Intro to Web Components](https://developer.salesforce.com/blogs/2020/01/intro-to-web-components.html)
* [The Holy Grail Of Reusable Components: Custom Elements, Shadow DOM, And NPM](https://www.smashingmagazine.com/2018/07/reusable-components-custom-elements-shadow-dom-npm/)
* [The Motivation For Using Web Components, an Introduction](https://www.thinktecture.com/web-components/introduction-and-motivation/)
* [The Power of Web Components](https://hacks.mozilla.org/2018/11/the-power-of-web-components/)
* [Web Components 101](https://nhswd.com/blog/web-components-101-what-are-web-components/)
* [Web Components: From the orbital height](https://javascript.info/webcomponents-intro)
* [What are browser-native web components?](https://gomakethings.com/what-are-browser-native-web-components/)
* [Why Web Components?](https://www.fast.design/docs/resources/why-web-components/)

## Standards

### Custom Elements

Custom Elements provide a way for authors to build their own fully-featured DOM elements.

* [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements) ⭐ 5,776 | 🐛 2,711 | 🌐 HTML | 📅 2026-02-19
* [All about HTML Custom Elements](https://github.com/shawnbot/custom-elements) ⭐ 203 | 🐛 4 | 📅 2019-03-04
* [A Guide to Custom Elements for React Developers](https://css-tricks.com/a-guide-to-custom-elements-for-react-developers/)
* [Custom elements](https://javascript.info/custom-elements)
* [Custom Elements v1: Reusable Web Components](https://web.dev/custom-elements-v1/)
* [Handling properties in custom element upgrades](https://nolanlawson.com/2021/08/03/handling-properties-in-custom-element-upgrades/)
* [Handy Custom Elements' Patterns](https://gist.github.com/WebReflection/ec9f6687842aa385477c4afca625bbf4)
* [HTML Living Standard: Custom elements](https://html.spec.whatwg.org/multipage/custom-elements.html)
* [MDN - Using Custom Elements](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)

### Shadow DOM

Shadow DOM describes a method of combining multiple DOM trees into one hierarchy and how these trees interact with each other within a document, thus enabling better composition of the DOM.

* [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/shadow-dom) ⭐ 5,776 | 🐛 2,711 | 🌐 HTML | 📅 2026-02-19
* [Shadow DOM in depth](https://github.com/praveenpuglia/shadow-dom-in-depth) ⭐ 237 | 🐛 1 | 📅 2022-05-26
* [A complete guide on shadow DOM and event propagation](https://pm.dartus.fr/blog/a-complete-guide-on-shadow-dom-and-event-propagation/)
* [DOM Living Standard: Shadow tree](https://dom.spec.whatwg.org/#shadow-trees)
* [MDN - Using Shadow DOM](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
* [Mind the document.activeElement!](https://dev.to/open-wc/mind-the-document-activeelement-2o9a)
* [Open vs. Closed Shadow DOM](https://blog.revillweb.com/open-vs-closed-shadow-dom-9f3d7427d1af)
* [Shadow DOM](https://javascript.info/shadow-dom)
* [Shadow DOM and events](https://javascript.info/shadow-dom-events)
* [Shadow DOM slots, composition](https://javascript.info/slots-composition)
* [Shadow DOM styling](https://javascript.info/shadow-dom-style)
* [Shadow DOM v1: Self-Contained Web Components](https://web.dev/shadowdom-v1/)
* [The Rise of Shadow DOM](https://medium.com/front-end-hacking/the-rise-of-shadow-dom-84aa1f731e82)
* [Understanding Slot Updates with Web Components](https://coryrylan.com/blog/understanding-slot-updates-with-web-components)
* [What is the Shadow DOM?](https://bitsofco.de/what-is-the-shadow-dom/)
* [Who doesn't love some slots?](https://dev.to/westbrook/who-doesnt-love-some-s-3de0)
* [Your Content in Shadow DOM Portals](https://dev.to/westbrook/your-content-in-shadow-dom-portals-3cdb)

### HTML Templates

`<template>` element is used to declare fragments of HTML that can be cloned and inserted in the document by script.

* [Crafting Reusable HTML Templates](https://css-tricks.com/crafting-reusable-html-templates/)
* [HTML Living Standard: The `template` element](https://html.spec.whatwg.org/multipage/scripting.html#the-template-element)
* [HTML templates with vanilla JavaScript](https://gomakethings.com/html-templates-with-vanilla-javascript/)
* [MDN - \<template>: The Content Template element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
* [MDN - Using templates and slots](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)
* [Template element](https://javascript.info/template-element)
* [Templating in HTML](https://kittygiraudel.com/2022/09/30/templating-in-html/)
* [The HTML5 template element](https://dev.to/ahferroin7/the-html5-template-element-26b6)
* [Understanding The Template Element In HTML](https://blog.openreplay.com/understanding-the-template-element-in-html/)
* [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/html/semantics/scripting-1/the-template-element) ⭐ 5,776 | 🐛 2,711 | 🌐 HTML | 📅 2026-02-19

### CSS Shadow Parts

CSS Shadow Parts allow developers to expose certain elements inside Shadow DOM for styling purposes.

* [W3C First Public Working Draft](https://www.w3.org/TR/css-shadow-parts-1/)
* [CSS Shadow Parts are coming!](https://dev.to/webpadawan/css-shadow-parts-are-coming-mi5)
* [MDN - `::part()` CSS pseudo element](https://developer.mozilla.org/en-US/docs/Web/CSS/::part)
* [MDN - `part` global attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/part)
* [::part and ::theme, an ::explainer](https://meowni.ca/posts/part-theme-explainer/)
* [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/css/css-shadow-parts) ⭐ 5,776 | 🐛 2,711 | 🌐 HTML | 📅 2026-02-19

## Guides

### Accessibility

* [Accessibility for Web Components](https://developer.salesforce.com/blogs/2020/01/accessibility-for-web-components.html)
* [Accessibility with ID Referencing and Shadow DOM](https://coryrylan.com/blog/accessibility-with-id-referencing-and-shadow-dom)
* [Dialogs and shadow DOM: can we make it accessible?](https://nolanlawson.com/2022/06/14/dialogs-and-shadow-dom-can-we-make-it-accessible/)
* [How to Make Accessible Web Components — a Brief Guide](https://www.sitepoint.com/accessible-web-components/)
* [Managing focus in the shadow DOM](https://nolanlawson.com/2021/02/13/managing-focus-in-the-shadow-dom/)
* [The future of accessibility for custom elements](https://robdodson.me/the-future-of-accessibility-for-custom-elements/)
* [The Guide to Accessible Web Components](https://www.erikkroes.nl/blog/accessibility/the-guide-to-accessible-web-components-draft/)
* [Web Components and the Accessibility Object model (AOM)](https://www.24a11y.com/2019/web-components-and-the-aom/)
* [Web Components punch list](https://www.tpgi.com/web-components-punch-list/)
* [Web components still need to be accessible](https://www.24a11y.com/2018/web-components-still-need-to-be-accessible/)

### Best Practices

* [Custom Element Best Practices](https://web.dev/custom-elements-best-practices/)
* [Developing Components: Publishing](https://open-wc.org/guides/developing-components/publishing/)
* [Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki) ⚠️ Archived
* [Guidelines for creating web platform compatible components](https://w3ctag.github.io/webcomponents-design-guidelines/)
* [How to Publish Web Components to NPM](https://justinfagnani.com/2019/11/01/how-to-publish-web-components-to-npm/)
* [Open Web Components Recommendations](https://open-wc.org)

### Codelabs

* [Build a Story Web Component with LitElement](https://dev.to/straversi/build-a-story-web-component-with-litelement-e59)
* [Building Custom Elements with Web Components for the 2020 Elections](https://medium.com/stories-from-upstatement/building-custom-elements-with-web-components-for-the-2020-elections-f767ff9e9c6a)
* [Creating Custom Form Controls with ElementInternals](https://css-tricks.com/creating-custom-form-controls-with-elementinternals/)
* [From Web Component to Lit Element](https://codelabs.developers.google.com/codelabs/the-lit-path)
* [HowTo Components –`<howto-checkbox>`](https://web.dev/components-howto-checkbox/)
* [HowTo Components –`<howto-tabs>`](https://web.dev/components-howto-tabs/)
* [HowTo Components – `<howto-tooltip>`](https://web.dev/components-howto-tooltip/)
* [Lit: basics](https://open-wc.org/codelabs/basics/lit-html.html#0)
* [Lit: intermediate](https://open-wc.org/codelabs/intermediate/lit-html.html#0)
* [Lit for React Developers](https://codelabs.developers.google.com/codelabs/lit-2-for-react-devs#0)
* [Web Components: basics](https://open-wc.org/codelabs/basics/web-components.html#0)

### Examples

* [web-components-examples](https://github.com/mdn/web-components-examples) ⭐ 3,362 | 🐛 4 | 🌐 JavaScript | 📅 2026-01-13 - Series of web components examples, related to the MDN web components documentation.
* [howto-components](https://github.com/GoogleChromeLabs/howto-components) ⭐ 874 | 🐛 52 | 🌐 JavaScript | 📅 2025-11-16 - Collection of web components that implement common web UI patterns.
* [generic-components](https://github.com/thepassle/generic-components) ⭐ 573 | 🐛 11 | 🌐 JavaScript | 📅 2022-07-21 - Collection of generic web components with a focus on accessibility, and ease of use.
* [Nude UI](https://github.com/LeaVerou/nudeui) ⭐ 232 | 🐛 6 | 🌐 JavaScript | 📅 2025-04-23 - Collection of accessible, customizable, ultra-light web components.
* [vanilla-retro-js](https://github.com/martine-dowden/vanilla-retro-js) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-06 - Vanilla JS UI component library of HTML deprecated tags.
* [open-wc code examples](https://open-wc.org/guides/developing-components/code-examples/) - Collection of best practices and design patterns for developing web components.

## Articles

### Architecture

* [A deep analysis into isomorphic, autonomous cross-framework usage #MicroFrontends](https://itnext.io/a-deep-analysis-into-isomorphic-autonomous-cross-framework-usage-microfrontends-364271dc5fa9)
* [Frankenstein Migration: Framework-Agnostic Approach (Part 1)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-1/)
* [Frankenstein Migration: Framework-Agnostic Approach (Part 2)](https://www.smashingmagazine.com/2019/09/frankenstein-migration-framework-agnostic-approach-part-2/)
* [Generating Config driven Dynamic Forms using Web Components](https://codeburst.io/generating-config-driven-dynamic-forms-using-web-components-7c8d400f7f2e)
* [Hiding internal framework methods and properties from web component APIs](https://component.kitchen/blog/posts/hiding-internal-framework-methods-and-properties-from-web-component-apis)
* [How to deliver Custom Elements](https://medium.com/@WebReflection/how-to-deliver-custom-elements-702fae32d25c)
* [Making Web Components for Different Contexts](https://css-tricks.com/making-web-components-for-different-contexts/)
* [Supporting both automatic and manual registration of custom elements](https://component.kitchen/blog/posts/supporting-both-automatic-and-manual-registration-of-custom-elements)
* [Web Components — the right way](https://equinusocio.dev/blog/web-components-the-right-way/)

### Interoperability

* [Advanced Tooling for Web Components](https://css-tricks.com/advanced-tooling-for-web-components/)
* [Custom Elements Everywhere](https://custom-elements-everywhere.com)
* [Custom Elements That Work Anywhere](https://robdodson.me/interoperable-custom-elements/)
* [JavaScript frameworks, meet Web Components](https://www.voorhoede.nl/nl/blog/javascript-frameworks-meet-web-components/)
* [Web Components aren't a framework replacement - they're better than that](https://lamplightdev.com/blog/2020/01/18/web-components-arent-a-framework-replacement-theyre-better-than-that/)
* [Web Components: Seamlessly interoperable](https://medium.com/@sergicontre/web-components-seamlessly-interoperable-82efd6989ca4)

### Limitations

* [Beyond the polyfills: how Web Components affect us today?](https://dev.to/webpadawan/beyond-the-polyfills-how-web-components-affect-us-today-3j0a)
* [Custom elements, shadow DOM and implicit form submission](https://www.hjorthhansen.dev/shadow-dom-and-forms/)
* [Form-associated custom elements](https://www.hjorthhansen.dev/shadow-dom-form-participation/)
* [You might not need shadow DOM](https://www.hjorthhansen.dev/you-might-not-need-shadow-dom/)

### Styling

* [Does shadow DOM improve style performance?](https://nolanlawson.com/2021/08/15/does-shadow-dom-improve-style-performance/)
* [Eschewing Shadow DOM](https://every-layout.dev/blog/eschewing-shadow-dom/)
* [How Nordhealth uses Custom Properties in Web Components](https://web.dev/custom-properties-web-components/)
* [Options for styling web components](https://nolanlawson.com/2021/01/03/options-for-styling-web-components/)
* [Style scoping versus shadow DOM: which is fastest?](https://nolanlawson.com/2022/06/22/style-scoping-versus-shadow-dom-which-is-fastest/)
* [Styling a Web Component](https://css-tricks.com/styling-a-web-component/)
* [Styling in the Shadow DOM With CSS Shadow Parts](https://css-tricks.com/styling-in-the-shadow-dom-with-css-shadow-parts/)
* [Thinking Through Styling Options for Web Components](https://css-tricks.com/thinking-through-styling-options-for-web-components/)
* [Web Component Pseudo-Classes and Pseudo-Elements are Easier Than You Think](https://css-tricks.com/web-component-pseudo-classes-and-pseudo-elements/)
* [Web Standards Meet User-Land: Using CSS-in-JS to Style Custom Elements](https://css-tricks.com/web-standards-meet-user-land-using-css-in-js-to-style-custom-elements/)

## Real World

### Case Studies

* [Apple Just Shipped Web Components to Production and You Probably Missed It](https://dev.to/ionic/apple-just-shipped-web-components-to-production-and-you-probably-missed-it-57pf)
* [Bringing Order to Web Design Chaos (with Web Components)](https://dev.to/thatjoemoore/bringing-order-to-web-design-chaos--3fhb)
* [Get moving with Microsoft’s FAST web components](https://www.infoworld.com/article/3618410/get-moving-with-microsofts-fast-web-components.html)
* [How Web Components Are Used at GitHub and Salesforce](https://thenewstack.io/how-web-components-are-used-at-github-and-salesforce/)
* [How we use Web Components at GitHub](https://github.blog/2021-05-04-how-we-use-web-components-at-github/)
* [Implementing a Design Language System with Stencil.js](https://medium.com/@Danetag/implementing-a-design-language-system-with-stencil-js-515432918eb5)
* [ING ❤ Web Components](https://dev.to/thepassle/ing--web-components-aef)
* [ING Open-Sources Lion, Its White-Label Web Component Library – Q\&A with Thomas Allmer](https://www.infoq.com/articles/ing-open-sources-lion-web-component/)
* [Lessons Learned, making our app with Web Components](https://medium.com/samsung-internet-dev/lessons-learned-making-our-app-with-web-components-bf55379cfcda)
* [Looking back on five years of web components](https://bitworking.org/news/2019/07/looking-back-on-five-years-of-web-components)
* [Shipping Web Components in 2020](https://dev.to/joe8bit/shipping-web-components-in-2020-2h54)
* [The Firefox UI is now built with Web Components](https://briangrinstead.com/blog/firefox-webcomponents/)
* [Using web components to encapsulate CSS and resolve design system conflicts](https://about.gitlab.com/blog/2021/05/03/using-web-components-to-encapsulate-css-and-resolve-design-system-conflicts/)
* [Web Components at GitHub - Web Components SF Meetup](https://www.infoq.com/news/2020/08/web-components-sf-meetup-2020/)
* [Web Components at Scale at Salesforce: Challenges Encountered, Lessons Learnt](https://www.infoq.com/news/2020/03/web-components-salesforce-lwc/)
* [Web Development At Scale: Composable Applications With Web Components](https://medium.com/@jarrodek/composable-applications-with-web-components-ebe5158387be)
* [web.dev engineering blog #1: How we build the site and use Web Components](https://web.dev/how-we-build-webdev-and-use-web-components/)

### Components

* [`<trix-editor>`](https://github.com/basecamp/trix) ⭐ 19,909 | 🐛 173 | 🌐 JavaScript | 📅 2026-01-09 - Rich text editor custom element for everyday writing.
* [`<model-viewer>`](https://github.com/google/model-viewer) ⭐ 7,908 | 🐛 118 | 🌐 TypeScript | 📅 2026-02-18 - Web component for rendering interactive 3D models.
* [`<lite-youtube>`](https://github.com/paulirish/lite-youtube-embed) ⭐ 6,286 | 🐛 27 | 🌐 HTML | 📅 2025-11-10 - Lite YouTube embed with a focus on visual performance.
* [`<css-doodle>`](https://github.com/css-doodle/css-doodle) ⭐ 5,960 | 🐛 7 | 🌐 JavaScript | 📅 2026-01-22 - Web component for drawing patterns with CSS.
* [`<deep-chat>`](https://github.com/OvidijusParsiunas/deep-chat) ⭐ 3,531 | 🐛 22 | 🌐 TypeScript | 📅 2026-02-16 - Web component for chat with AI capabilities.
* [`<vime-player>`](https://github.com/vime-js/vime) ⭐ 2,841 | 🐛 172 | 🌐 TypeScript | 📅 2024-11-17 - Customizable, extensible, accessible and framework agnostic media player.
* [`<rapi-doc>`](https://github.com/mrin9/RapiDoc) ⭐ 1,882 | 🐛 130 | 🌐 JavaScript | 📅 2026-02-11 - Web component for creating documentation from OpenAPI Specification.
* [`<emoji-picker>`](https://github.com/nolanlawson/emoji-picker-element) ⭐ 1,717 | 🐛 34 | 🌐 JavaScript | 📅 2026-02-16 - Lightweight emoji picker, distributed as a web component.
* [`<qr-code>`](https://github.com/bitjson/qr-code) ⭐ 1,377 | 🐛 14 | 🌐 TypeScript | 📅 2023-02-28 – Web component for rendering customizable, animate-able, SVG-based QR codes.
* [`<dark-mode-toggle>`](https://github.com/GoogleChromeLabs/dark-mode-toggle) ⭐ 1,212 | 🐛 4 | 🌐 JavaScript | 📅 2026-02-14 - Custom element that allows to create a dark mode toggle or switch.
* [`<midi-player>`](https://github.com/cifkao/html-midi-player) ⭐ 855 | 🐛 19 | 🌐 TypeScript | 📅 2025-07-06 - MIDI file player and visualizer web components.
* [`<shader-doodle>`](https://github.com/halvves/shader-doodle) ⭐ 580 | 🐛 6 | 🌐 JavaScript | 📅 2023-03-04 - Web component for writing and rendering shaders.
* [`<active-table>`](https://github.com/OvidijusParsiunas/active-table) ⭐ 308 | 🐛 27 | 🌐 TypeScript | 📅 2025-05-13 - Editable table web component.
* [`<api-viewer>`](https://github.com/web-padawan/api-viewer-element) ⭐ 283 | 🐛 19 | 🌐 TypeScript | 📅 2026-01-22 - API documentation and live playground for Web Components.
* [`<progressive-image>`](https://github.com/andreruffert/progressive-image-element) ⭐ 273 | 🐛 2 | 🌐 HTML | 📅 2026-02-17 - Custom element to progressively enhance image placeholders.
* [`<json-viewer>`](https://github.com/alenaksu/json-viewer) ⭐ 233 | 🐛 8 | 🌐 TypeScript | 📅 2025-04-03 - Web component to visualize JSON data in a tree view.
* [`<web-vitals>`](https://github.com/stefanjudis/web-vitals-element) ⭐ 186 | 🐛 7 | 🌐 JavaScript | 📅 2023-08-15 - Bring [web vitals](https://github.com/GoogleChrome/web-vitals) ⭐ 8,420 | 🐛 19 | 🌐 JavaScript | 📅 2026-02-18 quickly into your page using custom elements.
* [`<chess-board>`](https://github.com/justinfagnani/chessboard-element) ⭐ 122 | 🐛 21 | 🌐 TypeScript | 📅 2025-08-22 - Standalone chess board web component.
* [`<player-x>`](https://github.com/playerxo/playerx) ⭐ 121 | 🐛 5 | 🌐 JavaScript | 📅 2024-07-19 - Media player web component.
* [`<range-slider>`](https://github.com/andreruffert/range-slider-element) ⭐ 87 | 🐛 6 | 🌐 JavaScript | 📅 2026-02-16 - Accessible range slider custom element with keyboard support.
* [`<fg-modal>`](https://github.com/filamentgroup/fg-modal) ⚠️ Archived - Accessible modal dialog web component.
* [`<file-viewer>`](https://github.com/avipunes/file-viewer) ⭐ 44 | 🐛 9 | 🌐 JavaScript | 📅 2024-04-12 - Web component built with Svelte to view files.
* [`<theme-switch>`](https://github.com/mahozad/theme-switch) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-14 - Animated toggle button to switch between light, dark, and system theme.

### Component Libraries

* [AMP](https://github.com/ampproject/amphtml) ⭐ 14,916 | 🐛 1,011 | 🌐 JavaScript | 📅 2026-01-17 - Web component framework for easily creating user-first websites, stories, ads, emails and more.
* [Shoelace](https://github.com/shoelace-style/shoelace) ⭐ 13,855 | 🐛 104 | 🌐 TypeScript | 📅 2026-02-17 - A forward-thinking library of web components.
* [Wired Elements](https://github.com/wiredjs/wired-elements) ⭐ 10,757 | 🐛 35 | 🌐 TypeScript | 📅 2023-10-07 - Set of common UI elements with a hand-drawn, sketchy look.
* [github-elements](https://github.com/github/github-elements) ⭐ 2,898 | 🐛 1 | 🌐 JavaScript | 📅 2025-12-08 - GitHub's Web Component collection.
* [LDRS](https://github.com/GriffinJohnston/ldrs) ⭐ 2,147 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-22 - Lightweight, customizable loading animations/spinners.
* [Lion Web Components](https://github.com/ing-bank/lion) ⭐ 1,930 | 🐛 160 | 🌐 JavaScript | 📅 2026-02-18 - Set of highly performant, accessible and flexible Web Components.
* [Blaze UI Atoms](https://github.com/BlazeSoftware/atoms) ⭐ 1,561 | 🐛 4 | 🌐 TypeScript | 📅 2023-06-20 - Set of web components powered by Blaze CSS.
* [Lume](https://github.com/lume/lume) ⭐ 1,489 | 🐛 125 | 🌐 TypeScript | 📅 2026-02-09 - Custom elements for 3D graphics. Built with Three.js for WebGL/WebGPU rendering, and Solid.js for reactivity and templating.
* [Microsoft Graph Toolkit](https://github.com/microsoftgraph/microsoft-graph-toolkit) ⭐ 1,044 | 🐛 186 | 🌐 TypeScript | 📅 2026-02-07 - Collection of web components for the Microsoft Graph.
* [Elix](https://github.com/elix/elix) ⭐ 833 | 🐛 12 | 🌐 JavaScript | 📅 2023-03-01 - High-quality, customizable web components for common user interface patterns.
* [AgnosticUI](https://github.com/AgnosticUI/agnosticui) ⭐ 772 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-16 - A CLI-based UI component library that copies Lit web components directly into your project. Full React and Vue wrappers for native framework experience.
* [Playground Elements](https://github.com/PolymerLabs/playground-elements) ⭐ 639 | 🐛 97 | 🌐 TypeScript | 📅 2025-10-02 - Serverless code experiences with web components.
* [Vaadin components](https://github.com/vaadin/web-components) ⭐ 554 | 🐛 935 | 🌐 JavaScript | 📅 2026-02-18 - Evolving set of high-quality web components for building business web applications.
* [Smart Web Components](https://github.com/HTMLElements/smart-webcomponents) ⭐ 471 | 🐛 6 | 🌐 CSS | 📅 2026-02-03 - Web components for business applications.
* [Apollo Elements](https://github.com/apollo-elements/apollo-elements) ⭐ 423 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-15 - Custom elements for using Apollo GraphQL with various web components libraries.
* [LRNWebComponents](https://github.com/elmsln/lrnwebcomponents/) ⭐ 269 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-18 - ELMS:LN produced web components for any project.
* [Clever components](https://github.com/CleverCloud/clever-components) ⭐ 238 | 🐛 327 | 🌐 JavaScript | 📅 2026-02-18 - Collection of Web Components made by Clever Cloud.
* [Wokwi Elements](https://github.com/wokwi/wokwi-elements) ⭐ 224 | 🐛 18 | 🌐 TypeScript | 📅 2026-02-07 - Web Components for Arduino and various electronic parts.
* [DataFormsJS](https://github.com/dataformsjs/dataformsjs) ⭐ 197 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-31 - Standalone Components for SPA routing, displaying data from web services, and more.
* [Curvenote](https://github.com/curvenote/article) ⭐ 193 | 🐛 20 | 🌐 TypeScript | 📅 2025-05-14 - Web components for creating interactive scientific articles.
* [Ignite UI Web Components](https://github.com/IgniteUI/igniteui-webcomponents) ⭐ 168 | 🐛 68 | 🌐 TypeScript | 📅 2026-02-18 - Complete library of UI components from Infragistics.
* [Umbraco UI Components](https://github.com/umbraco/Umbraco.UI) ⭐ 144 | 🐛 46 | 🌐 TypeScript | 📅 2026-02-18 - Collection of user interface web components for Umbraco CMS.
* [Nightingale](https://github.com/ebi-webcomponents/nightingale) ⭐ 143 | 🐛 25 | 🌐 TypeScript | 📅 2026-01-17 - Data visualisation web components for the life sciences.
* [Immersive Custom Elements](https://github.com/MozillaReality/immersive-custom-elements) ⚠️ Archived - Set of web components for embedding immersive (VR & AR) content.
* [AXA Pattern Library](https://github.com/axa-ch-webhub-cloud/pattern-library) ⭐ 130 | 🐛 27 | 🌐 JavaScript | 📅 2023-12-04 - AXA CH UI components library built with Web Components.
* [Blackstone UI](https://github.com/kjantzer/bui) ⭐ 108 | 🐛 17 | 🌐 JavaScript | 📅 2025-12-08 - Web components for creating interfaces by Blackstone Publishing.
* [Dile Components](https://github.com/Polydile/dile-components) ⭐ 98 | 🐛 2 | 🌐 JavaScript | 📅 2026-02-18 - General use Web Components for websites and applications.
* [Stripe Elements](https://github.com/bennypowers/stripe-elements) ⭐ 84 | 🐛 17 | 🌐 TypeScript | 📅 2023-12-06 - Custom Element Wrapper for Stripe.js v3 Elements.
* [Brightspace UI core](https://github.com/BrightspaceUI/core) ⭐ 77 | 🐛 37 | 🌐 JavaScript | 📅 2026-02-18 - Collection of web components for building Brightspace applications.
* [Medblocks UI](https://github.com/medblocks/medblocks-ui) ⭐ 68 | 🐛 12 | 🌐 TypeScript | 📅 2025-05-29 - Web Components for rapid development of openEHR and FHIR systems.
* [TrendChart Elements](https://github.com/WebLogin/trendchart-elements) ⭐ 62 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-08 - Components to generate simple, light and responsive charts.
* [Pixano Elements](https://github.com/pixano/pixano-elements) ⭐ 42 | 🐛 6 | 🌐 TypeScript | 📅 2023-03-22 - Re-usable web components dedicated to data annotation tasks.
* [AnywhereUI](https://github.com/adaleks/anywhere-ui) ⭐ 39 | 🐛 3 | 🌐 TypeScript | 📅 2024-06-06 - Collection of rich web components that includes framework bindings. Created with StencilJS.
* [Joomla UI custom elements](https://github.com/joomla-projects/custom-elements) ⭐ 31 | 🐛 12 | 🌐 JavaScript | 📅 2026-02-14 - Compilation of Joomla 4 Custom Elements.
* [One Platform Components](https://github.com/1-Platform/op-components) ⭐ 31 | 🐛 17 | 🌐 TypeScript | 📅 2026-02-17 - Set of web components for Red Hat One Platform.
* [elements-sk](https://github.com/google/elements-sk) ⚠️ Archived - Collection of custom elements for "a la carte" web development.
* [Mutation testing elements](https://github.com/stryker-mutator/mutation-testing-elements) ⭐ 27 | 🐛 46 | 🌐 TypeScript | 📅 2026-02-18 - A schema for mutation testing results with the web components to visualize it.
* [Nuxeo Elements](https://github.com/nuxeo/nuxeo-elements) ⭐ 27 | 🐛 29 | 🌐 JavaScript | 📅 2026-02-18 - Components for building web applications with Nuxeo using Web Components.
* [Titanium Elements](https://github.com/LeavittSoftware/titanium-elements) ⭐ 19 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-18 - Collection of lightweight web components used by Leavitt Group Enterprises.
* [TEI Publisher Components](https://github.com/eeditiones/tei-publisher-components) ⭐ 18 | 🐛 53 | 🌐 JavaScript | 📅 2026-02-17 - Collection of web components used by TEI Publisher and apps generated by it.
* [Tradeshift Elements](https://github.com/Tradeshift/elements) ⭐ 18 | 🐛 56 | 🌐 JavaScript | 📅 2026-02-02 - Reusable Tradeshift UI Components as Web Components.
* [Open Business Application Platform Web Components](https://github.com/openbap/obap-elements) ⭐ 14 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-06 - Collection of web components designed for business applications.
* [Fusion Web Components](https://github.com/equinor/fusion-web-components) ⭐ 13 | 🐛 22 | 🌐 TypeScript | 📅 2026-02-18 - Ser of web components used by Equinor Fusion.
* [Furo Webcomponents](https://github.com/eclipse/eclipsefuro-web) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-06 - Enterprise ready set of web components which work best with Eclipse Furo.
* [Ketch.UP](https://github.com/smeup/ketchup) ⭐ 11 | 🐛 8 | 🌐 JavaScript | 📅 2026-02-18 - Web components library for Sme.UP.
* [Warp View](https://github.com/senx/warpview) ⭐ 8 | 🐛 0 | 🌐 HTML | 📅 2023-05-04 - Collection of charting web components for Warp 10.
* [XWeather](https://github.com/kherrick/x-weather) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2020-10-02 - Collection of web components implementing portions of the OpenWeatherMap API.
* [Webmarkets web components](https://github.com/Webmarkets/wm-web-components) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-10 - Set of Webmarkets' public web components.
* [VSCode Webview Elements](https://github.com/bendera/vscode-webview-elements) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2024-01-01 - Components for creating VSCode extensions which use the Webview API.

### Design Systems

* [Fluent UI Web Components](https://github.com/microsoft/fluentui/tree/master/packages/web-components) ⭐ 19,854 | 🐛 647 | 🌐 TypeScript | 📅 2026-02-18 - Library of Web Components that supports Microsoft's Fluent design language.
* [Material Web Components](https://github.com/material-components/material-web) ⭐ 10,754 | 🐛 164 | 🌐 SCSS | 📅 2026-02-14 - Material Design implemented as Web Components.
* [FAST Components](https://github.com/microsoft/fast/tree/master/packages/web-components) ⭐ 9,619 | 🐛 80 | 🌐 TypeScript | 📅 2026-02-18 - Library of Web Components based on the FAST design language.
* [UI5 Web Components](https://github.com/SAP/ui5-webcomponents) ⭐ 1,721 | 🐛 289 | 🌐 TypeScript | 📅 2026-02-19 - Set of reusable UI elements implementing SAP Fiori Design Guidelines.
* [Spectrum Web Components](https://github.com/adobe/spectrum-web-components) ⭐ 1,488 | 🐛 226 | 🌐 TypeScript | 📅 2026-02-19 - Adobe Spectrum design language implementation built with Web Components.
* [Carbon Web Components](https://github.com/carbon-design-system/carbon-web-components) ⚠️ Archived - Carbon Design System variant on top of Web Components.
* [PatternFly Elements](https://github.com/patternfly/patternfly-elements) ⭐ 387 | 🐛 207 | 🌐 TypeScript | 📅 2026-02-10 - Collection of flexible and lightweight Web Components based on the Unified Design Kit.
* [Calcite Components](https://github.com/Esri/calcite-components) ⭐ 346 | 🐛 849 | 🌐 TypeScript | 📅 2026-02-19 - Shared Web Components for Esri's Calcite design framework.
* [NuML | NUDE Elements](https://github.com/tenphi/numl) ⭐ 338 | 🐛 24 | 🌐 JavaScript | 📅 2023-03-04 - HTML Framework and Design System based on Web Components and runtime CSS generation.
* [Siemens iX Web Components](https://github.com/siemens/ix/tree/main/packages/core) ⭐ 322 | 🐛 95 | 🌐 TypeScript | 📅 2026-02-19 - Web Components implementing Siemens iX design system.
* [Crayons](https://github.com/freshdesk/crayons) ⭐ 236 | 🐛 45 | 🌐 JavaScript | 📅 2026-02-18 - Collection of web components that adheres to the Freshworks Design System.
* [Momentum UI Web Components](https://github.com/momentum-design/momentum-ui/tree/master/web-components) ⭐ 212 | 🐛 61 | 🌐 SCSS | 📅 2026-02-12 - Set of UI components based on Momentum Design.
* [Clarity Core Web Components](https://github.com/vmware-clarity/core/tree/main/projects/core) ⚠️ Archived - Suite of web components from the Clarity Design System.
* [Astro Space UX Design System](https://github.com/RocketCommunicationsInc/astro) ⭐ 149 | 🐛 30 | 🌐 TypeScript | 📅 2026-02-18 - Set of components to build rich space app experiences with established interaction patterns.
* [Red Hat Design System](https://github.com/RedHat-UX/red-hat-design-system) ⭐ 135 | 🐛 244 | 🌐 HTML | 📅 2026-02-18 - Web components for building uniform experiences with the Red Hat brand.
* [OutlineJS](https://github.com/phase2/outline) ⭐ 131 | 🐛 21 | 🌐 TypeScript | 📅 2025-11-11 - Web component based design system starter kit.
* [Pharos Design System](https://github.com/ithaka/pharos) ⭐ 129 | 🐛 71 | 🌐 TypeScript | 📅 2026-02-17 - JSTOR's design system to create cohesive, supportive, and beautiful experiences.
* [Liquid](https://github.com/emdgroup-liquid/liquid) ⭐ 84 | 🐛 23 | 🌐 TypeScript | 📅 2025-12-01 - UI component library based on the Liquid Design System.
* [Forge Components](https://github.com/tyler-technologies-oss/forge) ⭐ 64 | 🐛 64 | 🌐 TypeScript | 📅 2026-02-18 - Library of Web Components adhering to the Forge Design System.
* [Helix UI](https://github.com/HelixDesignSystem/helix-ui) ⭐ 64 | 🐛 32 | 🌐 JavaScript | 📅 2023-01-06 - Web Component library for the Helix Design System.
* [Lyne Components](https://github.com/lyne-design-system/lyne-components) ⭐ 58 | 🐛 70 | 🌐 TypeScript | 📅 2026-02-18 - Building blocks of the Lyne Design System are based on Web Components.
* [Zooplus web components](https://github.com/zooplus/zoo-web-components) ⭐ 50 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-29 - Set of web components that implement Z+ shop style guide.
* [GOV.UK Web Components](https://github.com/tgreyuk/govuk-webcomponents) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2021-02-08 - Set of encapsulated web components consuming the GOV.UK Design System.
* [Auro Design System](https://auro.alaskaair.com) - Alaska Airlines design system to innovate on ideas and collaborate on the future.
* [Blueprint UI](https://blueprintui.dev) - Web Component based design system with flexible and lightweight components.
* [Bolt Design System](https://github.com/boltdesignsystem/bolt) - Twig and Web Component-powered UI components, reusable visual styles and tooling.
* [Nord](https://nordhealth.design) - Nordhealth’s design system for products, digital experiences and brand.
* [U-M Library Design System](https://design-system.lib.umich.edu) - University of Michigan Library Design System.

### Use Cases

* [How we chose to build our Design System using StencilJS Web Components](https://medium.com/8451/how-we-chose-to-build-our-design-system-using-stenciljs-web-components-4878c36743c5)
* [How searching for a bundle-free React led me to web components](https://www.bryanbraun.com/2020/08/31/how-searching-for-a-bundle-free-react-led-me-to-web-components/)
* [Reasons Web Components are perfect for a big company](https://medium.com/@sergicontre/reasons-web-components-are-perfect-for-a-big-company-28790d712ad5)
* [5 Reasons Web Components Are Perfect for Design Systems](https://ionicframework.com/blog/5-reasons-web-components-are-perfect-for-design-systems/)
* [Web components: the secret ingredient helping power the web](https://web.dev/web-components-io-2019/)
* [Web Components for Enterprise. Part 1: Salesforce, Oracle, SAP](https://dev.to/webpadawan/web-components-for-enterprise-part-1-salesforce-oracle-sap-e70)
* [Web Components for Enterprise. Part 2: Nuxeo, Ionic, Vaadin](https://dev.to/webpadawan/web-components-for-enterprise-part-2-nuxeo-ionic-vaadin-22l7)
* [Why I use Web Components - My use cases](https://dev.to/shihn/why-i-use-web-components-my-use-cases-1nip)
* [Why we use Web Components](https://viljamis.com/2019/why-we-use-web-components/) by [@viljamis](https://twitter.com/viljamis)
* [Why we use Web Components](https://dev.to/ionic/why-we-use-web-components-2c1i) by [@maxlynch](https://twitter.com/maxlynch)

## Libraries

### Class Based

* [Omi](https://github.com/Tencent/omi) ⭐ 13,262 | 🐛 69 | 🌐 TypeScript | 📅 2026-01-10 - Next generation web framework in 4kb JavaScript (Web Components + JSX + Proxy + Store + Path Updating).
* [Stencil](https://github.com/ionic-team/stencil) ⭐ 13,031 | 🐛 165 | 🌐 TypeScript | 📅 2026-02-19 - Compiler for generating Web Components.
* [FAST Element](https://github.com/microsoft/fast/tree/master/packages/web-components/fast-element) ⭐ 9,619 | 🐛 80 | 🌐 TypeScript | 📅 2026-02-18 - Lightweight library for building performant, memory-efficient, standards-compliant Web Components.
* [Lightning Web Components](https://github.com/salesforce/lwc) ⭐ 1,754 | 🐛 418 | 🌐 JavaScript | 📅 2026-02-18 - blazing fast, enterprise-grade Web Components foundation.
* [slim.js](https://github.com/slimjs/slim.js) ⭐ 1,037 | 🐛 14 | 🌐 CSS | 📅 2023-09-06 - Fast & Robust Front-End Micro-framework based on modern standards.
* [Tonic](https://github.com/optoolco/tonic) ⭐ 889 | 🐛 16 | 🌐 JavaScript | 📅 2026-02-06 - Minimalist, stable, audit friendly component framework.
* [Panel](https://github.com/mixpanel/panel) ⭐ 277 | 🐛 10 | 🌐 JavaScript | 📅 2025-03-29 - Web Components + Virtual DOM: web standards for powerful UIs.
* [Lume Element](https://github.com/lume/element) ⭐ 184 | 🐛 14 | 🌐 TypeScript | 📅 2026-02-18 - Write custom elements with reactivity and templating powered by Solid.js signals and effects.
* [WebCell](https://github.com/EasyWebApp/WebCell) ⭐ 180 | 🐛 7 | 🌐 TypeScript | 📅 2025-09-28 - Web Components engine based on VDOM, JSX, MobX & TypeScript.
* [Joist](https://github.com/joist-framework/joist) ⭐ 135 | 🐛 6 | 🌐 TypeScript | 📅 2026-02-15 - Set of small libraries designed to add the bare minimum to web components to make you productive.
* [ReadyMade](https://github.com/readymade-ui/readymade/tree/main/src/modules/core) ⭐ 67 | 🐛 8 | 🌐 TypeScript | 📅 2025-03-10 - Write custom element classes with decorators. No dependencies.
* [DNA](https://github.com/chialab/dna) ⭐ 59 | 🐛 6 | 🌐 TypeScript | 📅 2026-02-18 - Progressive Web Components library.
* [element-js](https://github.com/webtides/element-js) ⭐ 30 | 🐛 22 | 🌐 JavaScript | 📅 2026-01-26 - Simple and lightweight base classes for web components with a beautiful API.
* [Forge Core](https://github.com/tyler-technologies-oss/forge-core) ⭐ 7 | 🐛 11 | 🌐 TypeScript | 📅 2026-01-22 - Building blocks and utilities that are used when building Forge Web Components.
* [Lit](https://lit.dev) - Simple library for building fast, lightweight web components.

### Functional

* [Solid Element](https://github.com/solidjs/solid/tree/main/packages/solid-element) ⭐ 35,156 | 🐛 131 | 🌐 TypeScript | 📅 2026-02-19 - Library that extends Solid adding Custom Web Components and extensions.
* [hybrids](https://github.com/hybridsjs/hybrids) ⭐ 3,167 | 🐛 7 | 🌐 JavaScript | 📅 2026-01-07 - UI library for creating Web Components with simple and functional API.
* [haunted](https://github.com/matthewp/haunted) ⭐ 2,701 | 🐛 60 | 🌐 TypeScript | 📅 2026-02-11 - React's Hooks API implemented for web components.
* [atomico](https://github.com/atomicojs/atomico) ⭐ 1,263 | 🐛 17 | 🌐 TypeScript | 📅 2025-11-26 - Small library for the creation of interfaces based on web components using functions and hooks.
* [Elemento](https://github.com/dsolimando/elemento) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-08 - A lightweight library for building functional web components using signals and Lit.

### Integrations

* [react-shadow](https://github.com/Wildhoney/ReactShadow) ⭐ 1,376 | 🐛 40 | 🌐 JavaScript | 📅 2025-01-09 - Utilise Shadow DOM in React with all the benefits of style encapsulation.
* [remount](https://github.com/rstacruz/remount) ⭐ 724 | 🐛 11 | 🌐 JavaScript | 📅 2023-03-08 - Mount React components to the DOM using custom elements.
* [preact-custom-element](https://github.com/preactjs/preact-custom-element) ⭐ 401 | 🐛 13 | 🌐 JavaScript | 📅 2025-12-18 - Generate/register a custom element from a preact component.
* [reactify-wc](https://github.com/BBKolton/reactify-wc) ⭐ 178 | 🐛 17 | 🌐 JavaScript | 📅 2023-03-06 - Use web components with React properties and functions.
* [@adobe/react-webcomponent](https://github.com/adobe/react-webcomponent) ⭐ 104 | 🐛 12 | 🌐 JavaScript | 📅 2024-04-10 - Automate the wrapping of a React component in a custom element.
* [nuxt-custom-elements](https://github.com/GrabarzUndPartner/nuxt-custom-elements) ⭐ 83 | 🐛 18 | 🌐 JavaScript | 📅 2026-02-17 - Export your project components as custom elements for integration into external pages.
* [@riotjs/custom-elements](https://github.com/riot/custom-elements) ⭐ 39 | 🐛 5 | 🌐 JavaScript | 📅 2026-01-21 - Simple API to create vanilla custom elements with Riot.js.
* [ember-custom-elements](https://github.com/Ravenstine/ember-custom-elements) ⭐ 15 | 🐛 17 | 🌐 JavaScript | 📅 2026-02-13 - Render Ember and Glimmer components using custom elements.

### Benchmarks

* [All the Ways to Make a Web Component](https://webcomponents.dev/blog/all-the-ways-to-make-a-web-component/)
* [web-components-benchmark](https://vogloblinsky.github.io/web-components-benchmark/) - Benchmark Web Components technologies with various examples.
* [web-components-todo](https://wc-todo.firebaseapp.com/) - The same todo application built in different Web Components libraries for benchmark purpose.

## Frameworks

### Angular

* [Angular Elements Overview](https://angular.io/guide/elements)
* [Building and consuming Angular Elements as Web Components](https://indepth.dev/building-and-bundling-web-components/)
* [How to use Angular ngModel and ngForms with WebComponents](https://itnext.io/how-to-use-angular-ngmodel-and-ngforms-with-webcomponents-802bd9e1d3d7)
* [Using Web Components in Angular](https://coryrylan.com/blog/using-web-components-in-angular)
* [Web Components With Angular Ivy In 6 Steps](https://www.softwarearchitekt.at/post/2019/05/18/web-components-custom-elements-with-angular-ivy-in-6-steps.aspx)

### React

* [3 Approaches to Integrate React with Custom Elements](https://css-tricks.com/3-approaches-to-integrate-react-with-custom-elements/)
* [Building Interoperable Web Components That Even Work With React](https://css-tricks.com/building-interoperable-web-components-react/)
* [Rendering React Components With Custom Elements](https://guillaumebriday.fr/rendering-react-components-with-custom-elements)
* [How to use Web Components in React](https://www.robinwieruch.de/react-web-components)
* [Using Web Components With Next (or Any SSR Framework)](https://css-tricks.com/using-web-components-with-next-or-any-ssr-framework/)

### Vue

* [Using Web Components in Vue](https://coryrylan.com/blog/using-web-components-in-vue)

### Svelte

* [Svelte Custom Element API](https://svelte.dev/docs#Custom_element_API)
* [How to Create a Web Component in Svelte](https://dev.to/silvio/how-to-create-a-web-components-in-svelte-2g4j)
* [Svelte Web Component — 5.4KB](https://itnext.io/svelte-web-component-5-4kb-4afe46590d99)

## Ecosystem

## Meta Frameworks

* [AMP](https://github.com/ampproject/amphtml) ⭐ 14,916 | 🐛 1,011 | 🌐 JavaScript | 📅 2026-01-17 - Web component framework to easily create user-first experiences for the web.
* [WebC](https://github.com/11ty/webc) ⭐ 1,409 | 🐛 64 | 🌐 JavaScript | 📅 2025-12-02 - Framework-independent standalone HTML serializer for generating markup for web components.
* [Web Components Compiler](https://github.com/ProjectEvergreen/wcc) ⭐ 120 | 🐛 21 | 🌐 JavaScript | 📅 2026-02-19 - Compiler to make server-side rendering of native web components easier.
* [luna-js](https://github.com/webtides/luna-js) ⭐ 10 | 🐛 11 | 🌐 JavaScript | 📅 2024-07-10 - SSR framework that makes working with the WebComponents standard a breeze.
* [Enhance](https://enhance.dev/docs/) - Web standards-based HTML framework for building lightweight web applications.
* [Rocket](https://rocket.modern-web.dev) - Modern web setup for static sites with a sprinkle of JavaScript.

### Starter Kits

* [custom-element-boilerplate](https://github.com/github/custom-element-boilerplate) ⭐ 176 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-30 - Boilerplate for creating a custom element.
* [nutmeg](https://github.com/abraham/nutmeg) ⭐ 117 | 🐛 23 | 🌐 TypeScript | 📅 2024-06-16 - Build, test, and publish vanilla Web Components with a little spice.
* [hello-web-components](https://github.com/fernandopasik/hello-web-components) ⭐ 31 | 🐛 6 | 🌐 TypeScript | 📅 2026-02-18 - Simple starter hello world web component written in TypeScript.
* [Create Open Web Components](https://open-wc.org/docs/development/generator/) - Web component project scaffolding.

### Testing Solutions

* [query-selector-shadow-dom](https://github.com/webdriverio/query-selector-shadow-dom) ⭐ 260 | 🐛 24 | 🌐 JavaScript | 📅 2024-03-27 - querySelector that can pierce Shadow DOM roots, useful for automated testing.
* [shadow-automation-selenium](https://github.com/sukgu/shadow-automation-selenium) ⭐ 116 | 🐛 12 | 🌐 Java | 📅 2026-02-16 - Shadow DOM automation using Selenium.
* [cypress-lit](https://github.com/simonireilly/cypress-lit) ⭐ 25 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-17 - Test your Lit elements and native web components in Cypress with all the modern browsers.
* [capybara-shadowdom](https://github.com/yuki24/capybara-shadowdom) ⭐ 15 | 🐛 1 | 🌐 Ruby | 📅 2023-07-05 - Ruby gem that adds basic support for the Shadow DOM to Capybara.
* [Cypress component tests for Lit](https://dev.to/simonireilly/cypress-component-tests-for-lit-elements-web-components-45oj) - How to run component tests for a Lit web component with Cypress.
* [Developing Components: Testing](https://open-wc.org/guides/developing-components/testing/) - Using @web/test-runner for testing web components in a real browser.
* [How To Automate Shadow DOM In Selenium WebDriver](https://www.lambdatest.com/blog/shadow-dom-in-selenium/) - Locating Shadow DOM elements using Selenium WebDriver in a Maven project.
* [Native Automation support for Shadow DOM](https://staleelement.medium.com/native-automation-support-for-shadow-dom-with-webdriverio-and-cypress-chapter-3-26249a589f5e) - Shadow DOM and open-source testing frameworks.
* [Open Web Components: Testing](https://open-wc.org/docs/testing/testing-package/) - Opinionated package that combines and configures testing libraries.
* [Testing Shadow DOM elements in Selenium](https://reflect.run/articles/testing-shadow-dom-elements-in-selenium/) - In Selenium 4, there is now a way to access Shadow DOM nodes.
* [Test web components with Playwright](https://alexbilson.dev/plants/technology/test-web-components-with-playwright/) - So you’ve created a native web component or two. How do you test them in popular browsers?
* [W3C Webdriver conquering automation of Shadow DOM](https://staleelement.medium.com/w3c-webdriver-conquering-automation-of-shadow-dom-chapter-2-d92c7fe9e74c) - Shadow DOM tree and its interaction with the W3C Webdriver.

### Tools

* [web-component-analyzer](https://github.com/runem/web-component-analyzer) ⭐ 516 | 🐛 96 | 🌐 TypeScript | 📅 2023-11-24 - CLI that analyzes web components and emits documentation / diagnostics.
* [Custom Elements Locator](https://github.com/open-wc/locator) ⭐ 38 | 🐛 4 | 🌐 JavaScript | 📅 2023-02-03 - Chrome extension to find custom elements on a page.
* [Web Components Codemods](https://github.com/kcmr/web-components-codemods) ⭐ 10 | 🐛 36 | 🌐 JavaScript | 📅 2026-02-17 - Codemods for Web Components.
* [Backlight](https://backlight.dev/) — With collaboration between developers and designers at heart, Backlight is a very complete coding platform where teams build, document, publish, scale and maintain Design Systems.
* [@storybook/web-components](https://www.npmjs.com/package/@storybook/web-components) - UI development environment for plain web-component snippets.
* [webcomponents.dev](https://webcomponents.dev) - Component IDE for web platform developers.

## Books

* [Web Components in Action](https://www.manning.com/books/web-components-in-action) - Book by Ben Farrell, available at Manning early release program.
* [Web Component Essentials](https://leanpub.com/web-component-essentials) - Book by Cory Rylan, early preview edition available at Leanpub.

## Tutorials

* [Building Web Components with Vanilla JavaScript](https://dev.to/aspittel/building-web-components-with-vanilla-javascript--jho)
* [Creating a Custom Element from Scratch](https://css-tricks.com/creating-a-custom-element-from-scratch/)
* [Creating a Reusable Avatar Web Component](https://marcoslooten.com/blog/creating-a-reusable-avatar-web-component/)
* [Creating Web Components with Stencil](https://auth0.com/blog/creating-web-components-with-stencil/)
* [Encapsulating Style and Structure with Shadow DOM](https://css-tricks.com/encapsulating-style-and-structure-with-shadow-dom/)
* [Getting started with LitElement and TypeScript](https://labs.thisdot.co/blog/getting-started-with-litelement-and-typescript)
* [Web Components: from zero to hero](https://dev.to/thepassle/web-components-from-zero-to-hero-4n4m)
* [Deep Dive: Web Components & Dependency Injection – The Experiment](https://www.thinktecture.com/web-components/dependency-injection/)
* [Handling data with Web Components](https://itnext.io/handling-data-with-web-components-9e7e4a452e6e)
* [How to use D3js with WebComponents](https://towardsdatascience.com/how-to-use-d3js-with-webcomponents-a75ae4f980de)
* [Navigation Lifecycle using Vaadin Router, LitElement and TypeScript](https://labs.thisdot.co/blog/navigation-lifecycle-using-vaadin-router-litelement-and-typescript)
* [Recreating The Arduino Pushbutton Using SVG And `<lit-element>`](https://www.smashingmagazine.com/2020/01/recreating-arduino-pushbutton-svg/)
* [Routing Management with LitElement and TypeScript](https://labs.thisdot.co/blog/routing-management-with-litelement)
* [Snake-Eating Game Making with Web Components of Omi and MVP Architecture](https://dev.to/dntzhang/snake-eating-game-making-with-web-components-of-omi-and-mvp-architecture-206)
* [Stencil – Web Components On Steroids](https://www.thinktecture.com/web-components/stenciljs-web-components-on-steroids/)
* [Using Modern Web Components](https://coryrylan.com/blog/using-modern-web-components)
* [Using Web Components in WordPress is Easier Than You Think](https://css-tricks.com/using-web-components-in-wordpress-is-easier-than-you-think/)
* [Web Components 101: Framework Comparison](https://coderpad.io/blog/development/web-components-101-framework-comparison/)
* [Web Components 101: Lit Framework](https://coderpad.io/blog/development/web-components-101-lit-framework/)
* [Web Components Tools: A Comparison](https://www.nexmo.com/blog/2020/05/20/web-components-tools-a-comparison)
* [Where to begin building Web Components? - The Basics](https://dev.to/alangdm/where-to-begin-building-web-components-the-basics-3b78)
* [Where to begin building Web Components? - Class-based Libraries](https://dev.to/alangdm/where-to-begin-building-web-components-class-based-libraries-18m6)

## Insights

### Podcasts

* [Code\[ish\], episode 38: Building with Web Components](https://www.heroku.com/podcasts/codeish/38-building-with-web-components)
* [Frontend Happy Hour, episode 62: Web Components - shots of shadow DOM](https://frontendhappyhour.com/episodes/web-components-shots-of-shadow-dom/)
* [Labs Talk - Web Components with Peter Muessig](https://labstalk.buzzsprout.com/993481/3932975-web-components-with-peter-muessig)
* [Real Talk JavaScript, episode 7: Custom Web Components with Rob Wormald](https://realtalkjavascript.simplecast.fm/eaf3db9e)
* [Real Talk JavaScript, episode 101: Back to Basics with Native HTML and LitElement](https://realtalkjavascript.simplecast.com/episodes/episode-101-back-to-basics-with-native-html-and-litelement)

### Presentations

* [Are Web Components the Betamax of web development?](https://noti.st/lostinbrittany/EjUZyd/are-web-components-the-betamax-of-web-development) by [@lostinbrittany](https://twitter.com/lostinbrittany)
* [Designing Standard Systems](https://drive.google.com/file/d/1ALFiWOFU0UAGUpaZPMIVnoADs9_REtL5/view) by [@stefsull](https://twitter.com/stefsull) and [@bferrua](https://twitter.com/bferrua)
* [Frontend Architecture for Scalable Design Systems](https://events.drupal.org/seattle2019/sessions/design-system-architecture-pattern-lab-twig-and-web-components) by [@salem\_cobalt](https://twitter.com/salem_cobalt)
* [lit-apollo: Data-Driven Components that Use the Platform](https://apolloelements.dev/using-lit-apollo/) by [@PowersBenny](https://twitter.com/PowersBenny)
* [Mastering Shadow DOM](https://martine-dowden.github.io/portfolio/presentation/mastering-shadow-dom) by [@Martine\_Dowden](https://twitter.com/Martine_Dowden)
* [Modernizing Large Frontends with Web Components](https://speakerdeck.com/samjulien/modernizing-large-frontends-with-web-components) by [@samjulien](https://twitter.com/samjulien)
* [Shadow DOM: off the beaten track](https://docs.google.com/presentation/d/1wi74YiTLtLSfgjyccKm5LxYp9k8aeJda0AekWV5mqJI/edit?usp=sharing) by [@serhiikulykov](https://twitter.com/serhiikulykov)
* [Using Web Components to Build a Framework-agnostic UI Library](https://gotochgo.com/2019/sessions/866/using-web-components-to-build-a-framework-agnostic-ui-library) by [@brianbouril](https://twitter.com/brianbouril) and [@danciupuliga](https://twitter.com/danciupuliga)
* [Web Components and the AOM](https://decks.tink.uk/2019/jsconf/index.html) by [@LeonieWatson](https://twitter.com/LeonieWatson)
* [Web Components and Styles Scoping](https://www.dropbox.com/s/wdh9uufjui5htll/Web-Components-and-Styles-Scoping-by-bashmish-FrontMania-2018.pdf) by [@bashmish](https://twitter.com/bashmish)
* [Web Components can do that?!](https://slides.com/vogloblinsky/web-components-can-do-that) by [@vogloblinsky](https://twitter.com/vogloblinsky)
* [Web Components: Introduction and State of the Art](https://webcomponents.dev/blog/web-components-slides/) by [@webcomp\_dev](https://twitter.com/webcomp_dev)

### Talks

* [Better Apps: Delivering Universal UI Patterns as Web Components](https://youtu.be/mtHf7crZZIQ) by [@janmiksovsky](https://twitter.com/janmiksovsky)
* [Custom Web Shadow Elements, or Whatever…](https://vimeo.com/364370506) by [@aerotwist](https://twitter.com/aerotwist)
* [Styling and Theming Web Components](https://youtu.be/FM7ROEVPA4k) by [@justinfagnani](https://twitter.com/justinfagnani)
* [Web Components at Enterprise Scale](https://youtu.be/iFp-P2UJT_Y) by [@diervo](https://twitter.com/diervo)

## Usage Metrics

* [Chrome Platform Status: `CustomElementRegistryDefine`](https://chromestatus.com/metrics/feature/timeline/popularity/1689)
* [Chrome Platform Status: `ElementAttachShadow`](https://chromestatus.com/metrics/feature/timeline/popularity/804)
* [Chrome Platform Status: `HTMLTemplateElement`](https://chromestatus.com/metrics/feature/timeline/popularity/2769)

## Proposals

### Form-associated Custom Elements

* [Form Participation API Explained](https://docs.google.com/document/d/1JO8puctCSpW-ZYGU8lF-h4FWRIDQNDVexzHoOQ2iQmY/edit?usp=sharing) - Document by Google Chrome team.
* [Form-associated custom elements](https://www.chromestatus.com/features/4708990554472448) - Feature in Chrome platform status.
* [web-platform-tests](https://github.com/web-platform-tests/wpt/tree/master/custom-elements/form-associated) ⭐ 5,776 | 🐛 2,711 | 🌐 HTML | 📅 2026-02-19

### Constructable Stylesheet Objects

* [web-platform-tests](https://github.com/web-platform-tests/wpt/blob/master/css/cssom/CSSStyleSheet-constructable.html) ⭐ 5,776 | 🐛 2,711 | 🌐 HTML | 📅 2026-02-19
* [Explainer](https://github.com/WICG/construct-stylesheets/blob/gh-pages/explainer.md) ⭐ 136 | 🐛 27 | 🌐 Bikeshed | 📅 2022-10-14
* [Specification Draft](https://wicg.github.io/construct-stylesheets/)
* [Constructable Stylesheets](https://www.chromestatus.com/feature/5394843094220800) - Feature in Chrome platform status.

### Custom State Pseudo Class

* [Blink: Intent to implement](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/CApU9QIu3TM)
* [`ElementInternals`'s `states` property and the `:state()` pseudo class](https://github.com/w3c/webcomponents/blob/gh-pages/proposals/custom-states-and-state-pseudo-class.md) ⭐ 4,477 | 🐛 203 | 🌐 HTML | 📅 2025-12-09

## Miscellaneous

* [bruck](https://github.com/Heydon/bruck) ⭐ 515 | 🐛 2 | 🌐 JavaScript | 📅 2023-08-25 - Prototyping system built with web components and the Houdini Paint API.
* [Vaadin Directory](https://vaadin.com/directory) - Publish, discuss and rate web components
* [webcomponents.org](http://webcomponents.org/) - Discuss & share web components.

## Archive

### Polyfills

Modern browsers supports web components standards without any of the polyfills listed below.
The only notable exception is that customized built-in elements are rejected by WebKit (Safari).

#### Custom Elements polyfills

* [@webcomponents/custom-elements](https://github.com/webcomponents/polyfills/tree/master/packages/custom-elements) ⭐ 1,180 | 🐛 142 | 🌐 HTML | 📅 2026-02-18 - Custom Elements polyfill by Polymer team.
* [document-register-element](https://github.com/WebReflection/document-register-element) ⚠️ Archived - Custom Elements polyfill by Andrea Giammarchi.

#### Customized Built-in Elements polyfills

* [@ungap/custom-elements-builtin](https://github.com/ungap/custom-elements-builtin) ⚠️ Archived - Customized built-in elements polyfill by [ungap project](https://ungap.github.io).
* [@corpuscule/custom-builtin-elements](https://github.com/corpusculejs/custom-builtin-elements) ⭐ 11 | 🐛 4 | 🌐 JavaScript | 📅 2020-09-10 - Customized built-in elements polyfill by [CorpusculeJS](https://github.com/corpusculejs).

#### Shadow DOM shims

* [@lwc/synthetic-shadow](https://github.com/salesforce/lwc/blob/master/packages/@lwc/synthetic-shadow) ⭐ 1,754 | 🐛 418 | 🌐 JavaScript | 📅 2026-02-18 - Shadow DOM polyfill by [LWC](https://lwc.dev).
* [@webcomponents/shadydom](https://github.com/webcomponents/polyfills/tree/master/packages/shadydom) ⭐ 1,180 | 🐛 142 | 🌐 HTML | 📅 2026-02-18 - ShadowDOM v1 shim.
* [@webcomponents/shadycss](https://github.com/webcomponents/polyfills/tree/master/packages/shadycss) ⭐ 1,180 | 🐛 142 | 🌐 HTML | 📅 2026-02-18 - ShadowDOM style encapsulation shim.

#### HTML Templates polyfills

* [@webcomponents/template](https://github.com/webcomponents/polyfills/tree/master/packages/template) ⭐ 1,180 | 🐛 142 | 🌐 HTML | 📅 2026-02-18 - Minimal polyfill for `<template>`.
* [@ungap/import-node](https://github.com/ungap/import-node) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2020-06-01 - An `importNode` polyfill for IE11 by [ungap project](https://ungap.github.io).

### History

The articles below represent a long story of the Web Components specifications on the way towards the standardization.
Some of them refer to earlier, so-called "v0" Shadow DOM and Custom Elements specs, and abandoned HTML Imports spec.
These materials are here for historical reasons only, they are grouped by years and listed in chronological order.

#### 2019

* [A history of the HTML slot element](https://component.kitchen/blog/posts/a-history-of-the-html-slot-element)
* [Web Components for Cross-Framework Component Libraries](https://codeburst.io/web-components-for-cross-framework-component-libraries-2647741f9470)
* [Web Components in 2019: Part 1](https://codeburst.io/web-components-in-2019-part-1-6bd7251edce5)
* [Web Components in 2019: Part 2](https://codeburst.io/web-components-in-2019-part-2-a7de8c770c5a)
* [Web Components in 2019: Part 3](https://codeburst.io/web-components-in-2019-part-3-e725b781a414)
* [Web Components in 2019: Part 4](https://codeburst.io/web-components-in-2019-part-4-7fe8e63a4dee)
* [Developments in Web Components I’m excited about in 2019](https://medium.com/angular-in-depth/developments-in-web-components-im-excited-about-in-2019-3ae7751c2f64)

#### 2018

* [Styling Accessibility: A Web Components Approach](https://medium.com/@cfscorreia/styling-accessibility-a-web-components-approach-dc2aa8123eb2)
* [Web Components 101: An Introduction to Web Components](https://www.telerik.com/blogs/web-components-101-an-introduction-to-web-components)
* [Get started with Vue web components](https://medium.com/@royprins/get-started-with-vue-web-components-593b3d5b3200)
* [6 Reasons You Should Use Native Web Components](https://codeburst.io/6-reasons-you-should-use-native-web-components-b45e18e069c2)
* [Web Components in 2018](https://www.sitepen.com/blog/web-components-in-2018)
* [Web Components Introduction: Creating Custom HTML Elements in 2018](https://www.grapecity.com/en/blogs/web-components-introduction-creating-custom-html-elements-2018)
* [Create & Publish Web Components With Vue CLI 3](https://vuejsdevelopers.com/2018/05/21/vue-js-web-component/)
* [Extending Native DOM Elements with Web Components](https://medium.com/revillweb/extending-native-dom-elements-with-web-components-233350c8e86a)

#### 2017

* [Styling is critical to web component reuse, but may prove difficult in practice](https://component.kitchen/blog/posts/styling-is-critical-to-web-component-reuse-but-may-prove-difficult-in-practice)
* [Web Components: The Long Game](https://infrequently.org/2017/10/web-components-the-long-game/)
* [Web Components: Just in the Nick of Time (Polymer Summit 2017)](https://youtu.be/y-8Lmg5Gobw)
* [Using Web Components in Ionic (Polymer Summit 2017)](https://youtu.be/UfD-k7aHkQE)
* [Web Components for VR (Polymer Summit 2017)](https://youtu.be/8GmTu2JF4-0)
* [Building UI at Enterprise Scale with Web Components (Polymer Summit 2017)](https://youtu.be/FJ2KEvzlyo4)
* [Custom Elements Everywhere (Polymer Summit 2017)](https://youtu.be/sK1ODp0nDbM)
* [Evolving the Next Generation of Polymer Elements (Polymer Summit 2017)](https://youtu.be/rvpJ5O0W_6A)
* [Polymer @ YouTube (Polymer Summit 2017)](https://youtu.be/tNulrEbTQf8)
* [Web Components for CMS (Polymer Summit 2017)](https://youtu.be/c-WDHG6rrdU)
* [An intro to web components with otters](https://meowni.ca/posts/web-components-with-otters/)
* [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/)
* [Regarding the broken promise of Web Components](http://robdodson.me/regarding-the-broken-promise-of-web-components/)
* [Web Components v1 - the next generation](https://web.dev/webcomponents-org/)

#### 2016

* [Introducing Custom Elements](https://webkit.org/blog/7027/introducing-custom-elements/)
* [The Case for Custom Elements: Part 1](https://medium.com/dev-channel/the-case-for-custom-elements-part-1-65d807b4b439)
* [The Case for Custom Elements: Part 2](https://medium.com/dev-channel/the-case-for-custom-elements-part-2-2efe42ce9133)
* [Demythstifying Web Components](http://www.backalleycoder.com/2016/08/26/demythstifying-web-components/)
* [Extensible web components](https://adactio.com/journal/11052)
* [Web Component Challenges](https://blog.revillweb.com/web-component-challenges-a09ebc598d65)
* [Web Components and progressive enhancement](https://onishi.ltd/articles/2016/08/web-components-and-progressive-enhancement/)
* [Update on standardizing Shadow DOM and Custom Elements](https://annevankesteren.nl/2015/07/shadow-dom-custom-elements-update)
* [What's New in Shadow DOM v1 (by examples)](https://hayatoito.github.io/2016/shadowdomv1/)
* [Why web components are so important](https://blog.revillweb.com/why-web-components-are-so-important-66ad0bd4807a)
* [Understanding Web Components](https://medium.com/the-ui-files/understanding-web-components-d051baa66019)

#### 2015

* [Introducing Slot-Based Shadow DOM API](https://webkit.org/blog/4096/introducing-shadow-dom-api/)
* [There is an Element for that](https://medium.com/synsugar/there-is-an-element-for-that-a9fcdafe4a25)
* [What happened to Web Components?](https://2ality.com/2015/08/web-component-status.html)
* [Web Components and their role in the future of web development](http://kaytcat.github.io/web-components/)
* [Microsoft Edge and Web Components](https://blogs.windows.com/msedgedev/2015/07/15/microsoft-edge-and-web-components/)
* [Bringing componentization to the web: An overview of Web Components](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/)
* [Why Web Components will make the web a better place for our users](https://medium.com/@kaelig/why-web-components-will-make-the-web-a-better-place-for-our-users-38dc3154fc1d)
* [Practical Questions around Web Components](https://www.ianfeather.co.uk/practical-questions-around-web-components/)
* [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components/)

#### 2014

* [A No-Nonsense Guide to Web Components, Part 1: The Specs](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-1-the-specs/)
* [A No-Nonsense Guide to Web Components, Part 2: Practical Use](http://cbateman.com/blog/a-no-nonsense-guide-to-web-components-part-2-practical-use/)
* [Web Components + Backbone: A Game-Changing Combination](https://youtu.be/dztuKgjk0Bg)
* [Mozilla and Web Components: Update](https://hacks.mozilla.org/2014/12/mozilla-and-web-components/)
* [Server-less applications powered by Web Components](https://youtu.be/MdcD1rNkNLE)
* [Web Components and the Future of CSS](https://youtu.be/QHxrr6Q82yI)
* [Easy composition and reuse with Web Components](https://youtu.be/6vcQlD-jadk)
* [Let’s build some apps with Polymer!](https://youtu.be/kV0hgdMpH28)
* [Polymer: State of the Union](https://youtu.be/0LT6W5QVCJI)
* [Web Components 101: An Introduction to Fundamental Changes in HTML](https://youtu.be/hEzmy93zr0Y?t=540)
* [Web Components 201: Designing Web Components for Reuse](https://youtu.be/dwxaG-eoxdU)
* [Why Web Components — Does the Web Really Need Another Component?](https://medium.com/@shaunwalla/why-web-components-does-the-web-really-need-another-component-4af010b6446)
* [“Don’t stop thinking about tomorrow” - AngularJS and Web Components](https://youtu.be/gSTNTXtQwaY)
* [Multi-device Apps with Web Components](https://youtu.be/kn0y7uugO0Y)
* [As I Walk Through The Valley Of The Shadow Of DOM](https://youtu.be/nbsWP2cPhhU)
* [Why Web Components Are Ready For Production](https://www.telerik.com/blogs/web-components-ready-production)
* [The State of the Componentised Web](https://www.leggetter.co.uk/2014/08/06/state-componentised-web.html)
* [An Addendum to Why Web Components Aren't Ready for Production Yet](https://www.tjvantoll.com/2014/07/18/an-addendum-to-why-web-components-arent-ready-for-production-yet/)
* [Why Web Components Aren't Ready for Production... Yet](https://www.telerik.com/blogs/web-components-arent-ready-production-yet)
* [Component Interop With React And Custom Elements](https://addyosmani.com/blog/component-interop-with-react-and-custom-elements/)
* [Accessibility of Web Components](https://youtu.be/BgvDZZ8Ms8c)
* [Componentize The Web: Back To The Browser!](https://youtu.be/GOPXVLxp9Nc)
* [Google I/O 2014 - Polymer and the Web Components revolution](https://youtu.be/yRbOSdAe_JU)
* [Google I/O 2014 - Polymer and Web Components change everything you know about Web development](https://youtu.be/8OJ7ih8EE7s)
* [Google I/O 2014 - Unlock the next era of UI development with Polymer](https://youtu.be/HKrYfrAzqFA)
* [Making Polymer Elements Accessible](https://youtu.be/_IBiXfxhF-A)
* [Building an Accessible Disclosure Button – using Web Components](https://developer.paciellogroup.com/blog/2014/06/accessible-disclosure-button-using-web-components/)
* [The Road to Web Components](https://youtu.be/yLyyXHhSl8w)
* [The Web Components Revolution is Here](https://youtu.be/3QLmAm9xtnU)
* [Web Components: A chance to create the future](https://youtu.be/JUzjr1bIRUg)
* [Web Component Mashups at 3 a.m.](https://youtu.be/75EuHl6CSTo)
* [Web Components Tools & Libraries](https://youtu.be/iPmN4CvLGJc)
* [Web Components Can Do That?!](https://addyosmani.com/fitc-wccdt/)
* [Web Components and you – dangers to avoid](https://christianheilmann.com/2014/04/18/web-components-and-you-dangers-to-avoid/)
* [HTML as Custom Elements](https://github.com/domenic/html-as-custom-elements) ⭐ 261 | 🐛 14 | 🌐 CSS | 📅 2015-09-03
* [The Web's Declarative, Composable Future](https://addyosmani.com/blog/the-webs-declarative-composable-future/)
* [Using Polymer to Create Web Components](https://code.tutsplus.com/tutorials/using-polymer-to-create-web-components--cms-20475)
* [The Shadow DOM Diaries](https://gist.github.com/dglazkov/efd2deec54f65aa86f2e)
* [A Detailed Introduction To Custom Elements](https://www.smashingmagazine.com/2014/03/introduction-to-custom-elements/)

#### 2013

* [A future called Web Components](https://speakerdeck.com/zenorocha/a-future-called-web-components)
* [Building Mobile Web Applications With Brick](https://youtu.be/dW2ib0bkxGQ)
* [Polymer: declarative, encapsulated, and reusable components for the web](https://youtu.be/DH1vTVkqCDQ)
* [Web Components: Why you're already an expert](https://youtu.be/s1PTPZwzQA4)
* [Yo Polymer: a new way of building web apps](https://youtu.be/booRxAJblwM)
* [Performance and Custom Elements](https://www.stevesouders.com/blog/2013/11/26/performance-and-custom-elements/)
* [Web Components Revolution](https://robdodson.github.io/webcomponents-revolution/)
* [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/)
* [Return of Inspector Web: Web Components a Year Later](https://vimeo.com/78899868)
* [Working with Custom Elements](https://web.dev/customelements/)
* [Creating Reusable Markup with The HTML Template Element](https://blog.teamtreehouse.com/creating-reusable-markup-with-the-html-template-element)
* [Working with Shadow DOM](https://blog.teamtreehouse.com/working-with-shadow-dom)
* [Breaking Development: Web Components](https://www.lukew.com/ff/entry.asp?1752)
* [Web Components: A Tectonic Shift for Web Development - Google I/O 2013](https://youtu.be/fqULJBBEVQE)
* [Web Components: Getting Started](https://vimeo.com/68212204)
* [Shadow DOM 101](https://web.dev/shadowdom/)
* [Shadow DOM 201](https://web.dev/shadowdom-201/)
* [Shadow DOM 301](https://web.dev/shadowdom-301/)
* [Visualizing shadow DOM concepts](https://developer.chrome.com/blog/visualizing-shadow-dom-concepts/)
* [Web components and the future of web development](https://youtu.be/pb6DsPNdoXk)
* [HTML's New Template Tag](https://web.dev/webcomponents-template/)

#### 2012

* [The Basics of the Shadow DOM](https://www.sitepoint.com/the-basics-of-the-shadow-dom/)
* [Notes on Web Components + ARIA](https://developer.paciellogroup.com/blog/2012/07/notes-on-web-components-aria/)
* [Google I/O 2012 - The Web Platform's Cutting Edge](https://youtu.be/2txPYQOWBtg)
* [Introduction to Web Components](https://www.w3.org/TR/2012/WD-components-intro-20120522/)

#### 2011

* [Web Components and Model Driven Views by Alex Russell](https://fronteers.nl/congres/2011/sessions/web-components-and-model-driven-views-alex-russell)
* [What the Heck is Shadow DOM?](https://glazkov.com/2011/01/14/what-the-heck-is-shadow-dom/)

## Who To Follow

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://twitter.com/polymer">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1063502058337136640/RmlG_bbW_80x80.jpg">
          <div>Polymer</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/stenciljs">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1135534552137510914/5ZzvOFFp_80x80.png">
          <div>Stencil</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/openwc">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1101188623930662912/YKlBD7n6_80x80.png">
          <div>open-wc.org</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/webcomp_dev">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1169270943371407360/U-90Bxn0_80x80.jpg">
          <div>webcomponents.dev</div>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://twitter.com/justinfagnani">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/378800000808710206/2dbdaa1cb7b0db02f997aea5b40f29b8_80x80.jpeg">
          <div>Justin Fagnani</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/viljamis">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/671595827740086273/wCUWq-1S_80x80.png">
          <div>Viljami Salminen</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/JanMiksovsky">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/675000078055051264/u1ZEQfeE_80x80.jpg">
          <div>Jan Miksovsky</div>
        </a>
      </td>
      <td align="center">
        <a href="https://twitter.com/serhiikulykov">
          <img width="80" height="80" src="https://pbs.twimg.com/profile_images/1028197887329685504/cM6nOHlp_80x80.jpg">
          <div>Serhii Kulykov</div>
        </a>
      </td>
    </tr>
  <tbody>
</table>

## Maintainers

* Created by [@mateusortiz](https://github.com/mateusortiz) in 2014.
* Maintained by [@web-padawan](https://github.com/web-padawan) since 2018.
