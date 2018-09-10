[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinincubator-media-object.svg)](https://vaadin.com/directory/component/vaadinincubator-media-object)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-media-object.svg)](https://vaadin.com/directory/component/vaadinincubator-media-object)

# &lt;incubator-media-object&gt;

[&lt;incubator-media-object&gt;](https://vaadin.com/directory/component/vaadinincubator-element) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-media-object/master/screenshot.png" width="200" alt="Screenshot of incubator-media-object">](https://vaadin.com/directory/component/vaadinincubator-element)

## Example Usage

```html
  <incubator-media-object header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-media-object>
```
