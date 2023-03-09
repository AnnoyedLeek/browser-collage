# js browser collage
Drag stuff around using the "draggable" function of jQuery. I want the final product to be a fun little browser collage activity for my personal website. Users should ultimately be able to drag objects in and out of the main div from a separate image bank at will, be able to bring forward or back a selected image, as well as click a button that takes a screenshot of the container wrapper.

Functionality to add:
- [x] Basic drag functionality.
- [ ] Implement HTML2Canvas & Canvas2Image to provide screenshot functionality.
- [ ] Add a selection system and create visual feedback that indicates which draggable item is selected.
- [ ] Create a function to change a selected image's z-index by one (up or down).
- [ ] Add some sort of delete option; this will either be selection-based or a "drag out of window and disappear" method.
- [ ] Make an image bank (with mini previews to save bandwidth and space) that will drag and snap to full width/height.

Sources:
[jQuery "Draggable" Docs](https://jqueryui.com/draggable/)
[Canvas2Image Releases](https://github.com/hongru/canvas2image)
Note: This is the most recent version I could find of Canvas2Image. Not sure if there is anything newer somewhere not on Github.
[HTML2Canvas Docs](https://html2canvas.hertzen.com/)
[HTML2Canvas Releases](https://github.com/niklasvh/html2canvas)
