# What is a design system
A design system consist of different parts:
- The design kit (Also known as UI Kit, is a set of patterns and components existing in design tools like Figma or Sketch.)
- The component library
- The pattern library
- UX rules and governance
- Documentation aka reference site, a website that aggregates all items (UI kit, component library, pattern library, UX rules) of the design system

The purpose of the design system is to solve inconsistencies in most importantly the behavior (UX) but also in look and feel of the interface (UI). Because of the reusability and governance a design system increases productivity, can reduce cost and increase efficiency.

Design systems are essential for building better, faster, and more cohesive digital products and experiences at scale, with respect to accessibility and brand identity.

![Design system](./Design%20systems.png)

# Related terms
Other design system related terms that might need clarification.

## style guide 
Documents a company or brand's visual identity and how it is used e.g. [Spotify](https://developer.spotify.com/documentation/general/design-and-branding/). It defines rules about typography, colors, logo's, iconography, paddings, margins etc. Style guides were already used in the 70's in print before they were used for the web platform. One of the first style guides used for print was [NASA's graphics standards manual from 1976.](https://www.nasa.gov/sites/default/files/atoms/files/nasa_graphics_manual_nhb_1430-2_jan_1976.pdf)

## pattern library
A library of UI patterns or reusable design solutions to solve reoccurring design problems. A Navbar solves the problem of navigating to different sections on the website. As a designer you can just reapply the navbar pattern without having to rethink this again and again. A pattern is always linked to a component.

## component library
A component library is the set of reusable components which turn the design language and UI Kit into living, breathing code.

## design tokens
A design token is an abstraction of a visual property such as color, font, spacing, animation, etc. Design tokens are shared across Design/UI Kits and component libraries for a cohesive experience. Design tokens originated at Salesforce where Jina Anne coined the term. In the most basic form these are just css variables in the component library. Other ways to structure design tokens [Open props](https://open-props.style/) or System UI. A [W3C community group](https://github.com/design-tokens/community-group) is currently working on a specification for design tokens

## design assets
Design assets are part of the design language and can be more static reusable elements like logo's, icons, illustrations, photography and videos.

## design language
Design is a form of communication. Graphical user interfaces use dozens of individual elements to speak to their users. Colors, typography, shapes, patterns, all of these front-end styling options have a direct impact on how users will comprehend the product and their emotions. A design language embodies the design principles. Every component and pattern that is created should be evaluated against the design principles.

## design principles
Design principles are the grounding values and principles which drive the creation of your products. Design principles must support the global vision of your product and express its identity. What do you want your users to feel when using your product? Sample principles from Firefox photon design language: adaptable, quick, aware, approachable, supportive and whimsical.

## design language system
There is no industry wide definition for this and people use the terms design system and design language system interchangeably. But you can't call just a component library a language or a system. A design language system sets expectations therefor when calling it a DLS, expectations are: pattern library, component library + rules + semantics + UX guidelines


# Learning resources
- [styleguides.io](http://styleguides.io/)
- [design sytem questionaire](https://github.com/bradfrost/design-system-questionnaire)
- [design.systems](https://design.systems/)
- [atomic design](https://atomicdesign.bradfrost.com/)
- [Emma Bostian's beginner guide](https://fem-design-systems.netlify.app/)
- [design systems repo](https://designsystemsrepo.com/)
- [backlight](https://backlight.dev/docs)
- [spotify design](https://spotify.design/article/5-things-i-wish-id-known-before-starting-a-design-system-at-spotify)


# Design systems built on web components
- [Group UI](https://volkswagen.frontify.com/d/rzB71PwpjXgt) (Volkswagen)
- [Material You](https://material.io/) (Google)
- [Fast Fluent UI](https://github.com/microsoft/fluentui) (Microsoft)
- [Fast Frame](https://www.fast.design/docs/design-systems/fast-frame) (Microsoft)
- [Spectrum](https://spectrum.adobe.com/) (Adobe)
- [Carbon](https://www.carbondesignsystem.com/) (IBM)
- [Vaadin design system](https://vaadin.com/design-system) (Vaadin)
- [Clarity](https://clarity.design/) (VMware)
- [Formilk](https://github.com/atomicojs/formilk) (Open source)
- [Backlight sample design systems](https://backlight.dev/docs/design-system-examples) (Backlight)

# Design systems built on JS frameworks (React, Vue, Svelte, ...)
- [Atlassian design system](https://atlassian.design/) (Atlassian)
- [Primer](https://primer.style/) (Github)
- [Vitamin](https://www.decathlon.design/726f8c765/p/71b8e3-decathlon-design-system) (Decathlon)
- [Paste](https://primer.style/) (Twillio)
- [HPE design system](https://design-system.hpe.design/) (Hewlett Packard)
- [Fluid](https://www.engie.design/) (Engie)
- [Photon](https://design.firefox.com/photon/) (Firefox)
- [Baseweb](https://baseweb.design/) (Uber)
- [Polaris](https://polaris.shopify.com/) (Polaris)
- Hawkins (Netflix)
- [GEL](https://www.bbc.co.uk/gel) (BBC)
- [Auro](https://auro.alaskaair.com/) (Alaskan Airlines)

# Component libraries built on web components
- [Shoelace](https://shoelace.style/) (Open source)
- [Zooplus web components](https://github.com/zooplus/zoo-web-components) (Zooplus)
- [Lion white label web components](https://github.com/ing-bank/lion) (ING bank)
- [Patternfly elements](https://github.com/patternfly/patternfly-elements) (Redhat)
- [Lightning web components](https://developer.salesforce.com/docs/component-library/documentation/en/lwc) (Salesforce)
- [Ionic](https://ionicframework.com/) (Ionic)
- [Elix](https://github.com/elix/elix) (Elix)
- [Clever components](https://github.com/CleverCloud/clever-components) (Clever Cloud)

| Component library | [Lit](https://lit.dev/) | [Stencil](https://stenciljs.com/) | [Vanillajs](https://github.com/WICG/webcomponents) | [Fast](https://www.fast.design/) | [Atomico](https://atomicojs.github.io/) | [Haunted](https://github.com/matthewp/haunted) | [Hybrids](https://hybrids.js.org/#/) |
| --- | :---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Shoelace | ✅ | | | | | | |
| Zooplus web components | | | ✅ | | | | |
| Lion white label | ✅ | | | | | | |
| Patternfly elements | ✅ | | | | | | |
| Lightning web components | | | ✅ | | | | |
| Group UI | | ✅ | | | | | |
| Formilk | | | | | ✅ | | |
| Fast Fluent UI | | | | ✅ | | | |
| Fast Frame | | | | ✅ | | | |
| Spectrum | ✅ | | | | | | |
| Carbon | ✅ | | | | | | |
| Vaadin | ✅ | | | | | | |
| Clarity | ✅ | | | | | | |
| Ionic | | ✅ | | | | | |
| Material web | ✅ | | | | | | |
| Elix | | | ✅ | | | | |
| Clever components | ✅ | | | | | | |
| Auro | ✅ | | | | | | |
