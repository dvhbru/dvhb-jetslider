jetSlider
=========

Simple plugin for making beautiful page transitions


Options
=======

| Option             | Type      | Default                                          | Description |
| ------------------ | --------- | ------------------------------------------------ | ----------- |
| slideSelector      | *String*  | `'section'`                                      | Selector of the slide elements |
| transitionDuration | *Number*  | `800`                                            | Duration of transition between slides |
| scroll             | *Boolean* | `true`                                           | Mouse scroll |
| keyboard           | *Boolean* | `true` if parent element is <body>. Else `false` | Keyboard arrows |
| easing             | *String*  | `'ease-in-out'`                                  | Easing function e.g. `'linear'`, `'ease-in'`, `'cubic-bezier(0.42,0,0.58,1)'`... |
| jsFallback         | *Boolean* | true                                             | If `true` js fallback will be used for animations in browsers which don't support css transorms and transitions. If `false` slides will change without animation in those browsers |
