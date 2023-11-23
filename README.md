# 3b

[![Deploy](https://github.com/unit-mesh/3b/actions/workflows/deploy.yml/badge.svg)](https://github.com/unit-mesh/3b/actions/workflows/deploy.yml)

> 3b is a sophisticated editor designed for content creation, catering to various formats such as blogs, articles, user
> stories, and more.

In the documentary "10 Years with Hayao Miyazaki"  the esteemed artist (宫崎骏, 宮﨑駿／みやざきはやお) chooses a 3B
pencil,
deeming conventional ones too inflexible for his creative process. Let us pay homage to his lofty ideals.

Todos: see [Roadmap](https://github.com/unit-mesh/3b/issues/1)

Online Demo: [https://editor.unitmesh.cc/](https://editor.unitmesh.cc/)

## Design Principle

- [Facets as Composable Extension Points](https://marijnhaverbeke.nl/blog/facets.html)

* Composition: Multiple extensions attaching to a given extension point must have their effects combined in a
  predictable way.
* Precedence: In cases where combining effects is order-sensitive, it must be easy to reason about and control the order
  of the extensions.
* Grouping: Many extensions will need to attach to a number of extension points, or even pull in other extensions that
  they depend on.
* Change: The effect produced by extensions may depend on other aspects of the system state, or be explicitly
  reconfigured.

## Refs:

### Tiptap Editor extensions

App:

- [Gitlab](https://gitlab.com/gitlab-org/gitlab/-/tree/master/app/assets/javascripts/content_editor/extensions)

Editor:

- [https://github.com/fantasticit/magic-editor](https://github.com/fantasticit/magic-editor)
- [Think Editor's Tiptap extensions](https://github.com/fantasticit/think/tree/main/packages/client/src/tiptap/core/extensions)

## License

TrackChange based on: [TrackChangeExtension](https://github.com/chenyuncai/tiptap-track-change-extension)

This code is distributed under the MIT license. See `LICENSE` in this directory.
