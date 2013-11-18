# jquery-markdown

## About

jQuery Markdown provides necessary wrapper functions for a markdown editor so anybody can create his/her own markdown editor using this plugin.

## Example

Example is attached with the source code under `example` folder, or you can check out the [demo](http://www.cangelis.com/jquery-markdown/demo)

## Documentation

**Note:** All the parameters defined here are **optional**.

### Bold

    $(editor).mdBold({
        default: "Text Here"
    });

`default` represents the text that will be wrapped when no text is selected in the `textarea`.

### Italic

    $(editor).mdItalic({
        default: "Text Here"
    });

### Header

    $(editor).mdHeader({
        default: "Heading Text",
        number: 1
    });

`number` represents the header size. For example: 1 -> `# Heading Text`, 2 -> `## Heading Text`

### Code

    $(editor).mdCode({
        default: "Code here"
    });

### Quote

    $(editor).mdQuote({
        default: "Quote here"
    });

### Link

    $(editor).mdLink({
        default_text: "Link Text Here",
        default_url: prompt('Enter URL please')
    });

### Image

    $(editor).mdImage({
        default_alt_text: "",
        default_image_url: prompt('Enter Image URL please'),
        default_image_title: ""
    });

### Numbered List

    $(editor).mdNumberedList({
        default: "List Item"
    });

### Bullet List

    $(editor).mdBulletList({
        default: "List Item"
    });

## Licence

    The MIT License (MIT)

    Copyright (c) 2013 Can Geliş

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
