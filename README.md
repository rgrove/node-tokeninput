YUI 3 Node TokenInput Plugin
============================

YUI 3 Node plugin that turns a text input field into a tokenized input field
similar to Cocoa's NSTokenField control.

  * [Source](https://github.com/rgrove/node-tokeninput)
  * [API docs](http://rgrove.github.com/node-tokeninput/api/)
  * [Examples](http://rgrove.github.com/node-tokeninput/examples/)
  * [Bugs](https://github.com/rgrove/node-tokeninput/issues)

Basic Usage
-----------

    <div class="yui3-skin-sam">
        <input type="text" id="tags">
    </div>

    <script src="http://yui.yahooapis.com/3.4.0/build/yui/yui-min.js"></script>
    <script>
    YUI({
        gallery: 'gallery-2011.08.24-23-44'
    }).use('gallery-node-tokeninput', function (Y) {

        // Turn #tags into a tokeninput field.
        Y.one('#tags').plug(Y.Plugin.TokenInput);

    });
    </script>
