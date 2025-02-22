---
category: Components
type: Data Display
title: Carousel
cover: https://gw.alipayobjects.com/zos/antfincdn/%24C9tmj978R/Carousel.svg
---

A carousel component. Scales with its container.

## When To Use

- When there is a group of content on the same level.
- When there is insufficient content space, it can be used to save space in the form of a revolving door.
- Commonly used for a group of pictures/cards.

## API

| Property | Description | Type | Default | Version |
| --- | --- | --- | --- | --- |
| autoplay | Whether to scroll automatically | boolean | false |  |
| dotPosition | The position of the dots, which can be one of `top` `bottom` `left` `right` | string | `bottom` |  |
| dots | Whether to show the dots at the bottom of the gallery, `object` for `dotsClass` and any others | boolean \| { className?: string } | true |  |
| easing | Transition interpolation function name | string | `linear` |  |
| effect | Transition effect | `scrollx` \| `fade` | `scrollx` |  |
| autoplaySpeed | Whether to scroll automatically | number | 5 |  |
| afterChange | Callback function called after the current index changes | function(current) | - |  |
| beforeChange | Callback function called before the current index changes | function(from, to) | - |  |

## Methods

| Name | Description |
| --- | --- |
| goTo(slideNumber, dontAnimate) | Go to slide index, if dontAnimate=true, it happens without animation |
| next() | Change current slide to next slide |
| prev() | Change current slide to previous slide |

Find more APIs in react-slick [documentation](https://react-slick.neostack.com/docs/api).

## FAQ

### How to add custom arrows?

See [#12479](https://github.com/ant-design/ant-design/issues/12479).
