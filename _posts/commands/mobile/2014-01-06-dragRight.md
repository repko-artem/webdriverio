---
tags: mobile
name: dragRight
arguments:
    - type: String
      name: selector
      desc: element to drag on
    - type: Number
      name: touchCount
      desc: how many fingers to flick with
    - type: Number
      name: duration
      desc: time (in seconds) to spend performing the drag
    - type: Function
      name: callback(err)
      desc: A function returning if command was executed successfully
---

Perform a drag right on an element (works only on [Appium](https://github.com/appium/appium/blob/master/docs/gestures.md))