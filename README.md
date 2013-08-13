# Modals
Simple modal dialogue windows.


## How It Works
Turn any link into a modal toggle by adding the `.modal-toggle` class. You also need to add a `data-target` attribute that matches the ID of the modal you want to open.

    <a class="modal-toggle" data-target="#modal" href="#">Toggle Modal</a>

    <div class="modal" id="modal">
        <a class="modal-close close">x</a>
        <h3>Modal</h3>
        <p>Modal content</p>
        <button class="btn modal-close">Close</button>
    </div>


## Different Sizes

Modals come in three different sizes: standard, medium, and small.

    <a class="modal-toggle" data-target="#modal-small" href="#">Small Modal</a>
    
    <div class="modal modal-small" id="modal-small">
        <a class="modal-close close">x</a>
        <h3>Modal Small</h3>
        <p>Modal content</p>
        <button class="btn modal-close">Close</button>
    </div>


    <a class="modal-toggle" data-target="#modal-medium" href="#">Medium Modal</a>
    
    <div class="modal modal-medium" id="modal-medium">
        <a class="modal-close close">x</a>
        <h3>Modal Medium</h3>
        <p>Modal content</p>
        <button class="btn modal-close">Close</button>
    </div>


## Modal Accessibility

For better accessibility, there are a few different ways to dismiss modals.

Adding a `.modal-close` tag to any button or link turns it into a modal dismiss link. Clicking anywhere outside the modal or pressing the escape key will close the modal, too.


## Backup URLs

Always specify a functioning link as a backup for modals.

If a browser doesn't support JavaScript, the modal dialogue won't work. Specifying a backup URL ensures that people can always access your content, even on less capable browsers.

When JavaScript is supported, Modals will prevent the backup URL from redirecting people away from the current page.

    <a class="modal-toggle" data-target="#modal" href="backup-url.com">Modal Togglel</a>


## Browser Support

Modals requires [jQuery](http://jquery.com/).

It works in all modern browsers, and IE 7 and above. Because IE 8 and lower do not support media queries, all three modal sizes will look the same in those browsers. [Learn how to add media query support to with older versions of IE.](http://gomakethings.com/mobile-first-and-internet-explorer/)


## Changelog
* v1.1 (June 7, 2013)
  * Switched to MIT license.
* v1.1 (March 27, 2013)
  * Touchscreen bug fix.
* v1.0 (March 25, 2013)
  * Initial release.


## License
Modals is free to use under the [MIT License](http://gomakethings.com/mit/).
