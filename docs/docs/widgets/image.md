---
id: image
title: Image
---
# Image

Image widget is used to display images in your app. 

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Image](/img/widgets/image/image.png)

</div>

## Events

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Image](/img/widgets/image/events.png)

</div>

### On click

On click event is triggered when an image is clicked.

:::info
Check [Action Reference](/docs/actions/show-alert) docs to get the detailed information about all the **Actions**.
:::

## Properties

### URL

Enter the URL of the image to display it on the widget.

### Zoom buttons
Toggle this to enable zoom options inside image.

### Alternative text
Used for alt text of images.

### General
#### Tooltip

A Tooltip is often used to specify extra information about something when the user hovers the 
mouse pointer over the widget.

Under the <b>General</b> accordion, you can set the value in the string format. 
Now hovering over the widget will display the string as the tooltip.

<div style={{textAlign: 'center'}}>

![ToolJet - widget- button](/img/tooltip.png)

</div>

## Layout

### Show on desktop

Toggle on or off to display the widget in desktop view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.
### Show on mobile

Toggle on or off to display the widget in mobile view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.

## Styles

### Border type

Choose a border type for the image from available options:
- None
- Rounded
- Circle
- Thumbnail

### Image fit

Choose a image fit - similar to object fit for the image from available options:
- fill
- cover
- contain
- scale-down
### Background color

Add a background color to widget by providing the `HEX color code` or choosing the color of your choice from the color-picker.

### Padding

Adds padding between the image and widget border. It accepts any numerical value from `0` to `100`.

### Visibility

Toggle on or off to control the visibility of the widget. You can programmatically change its value by clicking on the `Fx` button next to it. If `{{false}}` the widget will not be visible after the app is deployed. By default, it's set to `{{true}}`.

### Disable

This is `off` by default, toggle `on` the switch to lock the widget and make it non-functional. You can also programmatically set the value by clicking on the `Fx` button next to it. If set to `{{true}}`, the widget will be locked and becomes non-functional. By default, its value is set to `{{false}}`.

:::info
Any property having `Fx` button next to its field can be **programmatically configured**.
:::