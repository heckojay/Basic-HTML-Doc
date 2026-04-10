# Style Your First Website

## Overview

In order to style your website, you need to use [CSS](../glossary.md).

This guide demonstrates how to apply styling built on the website you created. This includes fonts, colors, spacing and positioning.

## Implementing a CSS File

Before styling your website you need a separate file to store your CSS. This ensures cleanliness and readability for your website.

1. **Click** the *New File* :material-file-plus: icon.

      ![VS Code Explorer panel showing the New File icon circled in the MYWEBSITE folder toolbar](images/stp1css.png "The New File icon in the VS Code Explorer panel.")

      *Figure 1. The New File icon in the VS Code Explorer panel.*

2. **Enter** `style.css`.

      ![VS Code Explorer panel showing style.css being typed as the new file name](images/stp2css.png "Entering style.css as the new file name.")

      *Figure 2. Entering style.css as the new file name.*

    ??? warning "Why Not Name It Something Else?"
        You can, but using `style.css` is standard practice and avoids confusion later.

    !!! success "Success!"
        You have created a CSS file!

## Linking CSS to HTML

Your CSS file will *not* work unless it is connected to your HTML file.

1. **Open** `index.html`.

      ![VS Code Explorer panel showing index.html and style.css listed under MYWEBSITE with index.html selected](images/stp3css.png "The index.html file selected in the VS Code Explorer panel.")

      *Figure 3. The index.html file selected in the VS Code Explorer panel.*

2. **Enter** `<link rel="stylesheet" href="style.css">`.

      ![VS Code editor showing index.html with a completed HTML page including headings, a list, and an image tag, alongside the style.css tab open](images/stp4css.gif "The link tag connecting style.css added inside the head of index.html.")

      *Figure 4. The link tag connecting style.css added inside the head of index.html.*

    ??? info "What Does The Tag Mean?"
        `rel="stylesheet"` tells the browser that the linked file is a CSS stylesheet.  
        `href="style.css"` specifies the location of the CSS file.

    !!! success "Success!"
        You have linked your HTML and CSS files!

## Styling

### Styling Text (Headers or Paragraphs)

This section explains how to style text color, text position, and text size.

1. **Open** `style.css`.

      ![VS Code Explorer panel showing style.css highlighted in a red box under MYWEBSITE](images/stp5css.png "The style.css file selected in the VS Code Explorer panel.")

      *Figure 5. The style.css file selected in the VS Code Explorer panel.*

2. **Enter** `h1`.

3. **Enter** `{`.

      ![VS Code editor showing h1 followed by an opening curly brace typed on line 1 of style.css](images/stp6css.png "The h1 selector with an opening curly brace entered in style.css.")

      *Figure 6. The h1 selector with an opening curly brace entered in style.css.*

    ???+ info "How Does This Work?"
        To clarify, `h1` is selecting *all* occurrences of `<h1>` in your website. The `{}` is what you are modifying to these occurrences.

4. **Press** *Enter*.

      ![VS Code editor showing h1 with opening and closing curly braces on separate lines with an empty line between them](images/stp7css.png "An empty line created between the opening and closing curly braces of the h1 rule.")

      *Figure 7. An empty line created between the opening and closing curly braces of the h1 rule.*

    !!! success "Success!"
        You have made the base CSS for styling text!

#### Styling Text Color

To style text using CSS, you need to include the color you desire.

1. **Enter** `color: blue;` <br> (Do not forget to save your code using *Ctrl + S*! )

      ![VS Code editor on the left showing the h1 rule with color: blue added on line 2, and Live Preview on the right displaying the h1 heading in blue text with a red border highlight](images/stp8css.png "The color property set to blue inside the h1 rule, with the heading rendered in blue in Live Preview.")

      *Figure 8. The color property set to blue inside the h1 rule, with the heading rendered in blue in Live Preview.*

    ??? info "How About Other Colors?"
        You can input red, yellow, or cyan in place of blue to name a few. To utilize other colors, you can use *RGB* values. For more information, visit [W3Schools](https://www.w3schools.com/colors/default.asp).

    !!! success "Success!"
        You have made the text color blue!

#### Styling Text Position

To style the text position using CSS, you need to include the alignment you desire.

1. **Enter** `text-align: center;` below color.

      ![VS Code editor on the left showing text-align: center added on line 3 of the h1 rule highlighted in a red box, and Live Preview on the right displaying the heading centered on the page](images/stp9css.png "The text-align property set to center inside the h1 rule, with the heading centered in Live Preview.")

      *Figure 9. The text-align property set to center inside the h1 rule, with the heading centered in Live Preview.*

    ??? info "Are There Any Other Alignments?"
        You can input left, right, or justify. Left or right aligns text to their respective values while justify aligns each line so they have the same width.

    !!! success "Success!"
        You have centered the text!

#### Styling Font Size

To style text size using CSS, you need to include the size you desire in pixels.

1. **Enter** `font-size: 16px;` below text-align.

      ![VS Code editor on the left showing font-size: 16px added on line 4 of the h1 rule highlighted in a red box, and Live Preview on the right displaying the smaller centered blue heading](images/stp10css.png "The font-size property set to 16px inside the h1 rule, with the heading rendered at the new size in Live Preview.")

      *Figure 10. The font-size property set to 16px inside the h1 rule, with the heading rendered at the new size in Live Preview.*

    ??? info "What Is Font Size?"
        Font size is how big your text is. "px" are called pixels and are a unit of measurement for the size of the text.

    !!! success "Success!"
        You have modified the text size!

### Styling Lists

This section explains how to style the list type.

1. **Enter** `ul`.

2. **Enter** `{`.

      ![VS Code editor showing ul followed by an opening curly brace typed below the h1 rule in style.css](images/stp11css.png "The ul selector with an opening curly brace entered below the h1 rule in style.css.")

      *Figure 11. The ul selector with an opening curly brace entered below the h1 rule in style.css.*

3. **Press** *Enter*.

      ![VS Code editor showing ul with opening and closing curly braces on separate lines with an empty line between them](images/stp12css.png "An empty line created between the opening and closing curly braces of the ul rule.")

      *Figure 12. An empty line created between the opening and closing curly braces of the ul rule.*

    !!! success "Success!"
        You have made the base CSS for styling a list!

#### Styling List Type

To style the list type using CSS, you need to include the type you desire.

1. **Enter** `list-style-type: square;`.

      ![VS Code editor on the left showing list-style-type: square added inside the ul rule highlighted in a red box, and Live Preview on the right displaying the list with square bullet points highlighted in a red box](images/stp13css.png "The list-style-type property set to square inside the ul rule, with the list rendered with square bullets in Live Preview.")

      *Figure 13. The list-style-type property set to square inside the ul rule, with the list rendered with square bullets in Live Preview.*

    ??? info "Are There Other List Types?"
        Yes, there are circle (already by default), upper-roman, and lower-alpha.

    !!! success "Success!"
        You have modified the list type!

### Styling Images

This section explains how to style the image width and image height.

1. **Enter** `img`.

2. **Enter** `{`.

      ![VS Code editor showing img followed by an opening curly brace typed below the ul rule in style.css](images/stp14css.png "The img selector with an opening curly brace entered below the ul rule in style.css.")

      *Figure 14. The img selector with an opening curly brace entered below the ul rule in style.css.*

3. **Press** *Enter*.

      ![VS Code editor showing img with opening and closing curly braces on separate lines with an empty line between them](images/stp15css.png "An empty line created between the opening and closing curly braces of the img rule.")

      *Figure 15. An empty line created between the opening and closing curly braces of the img rule.*

    !!! success "Success!"
        You have made the base CSS for styling a image!

#### Styling Image Width

To style a image using CSS, you need to include the width you desire in pixels.

1. **Enter** `width: 300px;`.

      ![VS Code editor on the left showing width: 300px added inside the img rule highlighted in a red box, and Live Preview on the right displaying the cat image resized to 300px wide with a red border highlight](images/stp16css.png "The width property set to 300px inside the img rule, with the image resized in Live Preview.")

      *Figure 16. The width property set to 300px inside the img rule, with the image resized in Live Preview.*

    ???+ tip "How Can I Keep My Image Size Consistent?"
        The easiest way is to use "auto" in place of px. "auto" will maintain the proportions of the image automatically.

    !!! success "Success!"
        You have modified the image width!

#### Styling Image Height

To style a image using CSS, you need to include the height you desire in pixels.

1. **Enter** `height: 800px;`.

      ![VS Code editor on the left showing height: 800px added inside the img rule highlighted in a red box, and Live Preview on the right displaying the cat image stretched vertically to 800px](images/stp17css.png "The height property set to 800px inside the img rule, with the image stretched vertically in Live Preview.")

      *Figure 17. The height property set to 800px inside the img rule, with the image stretched vertically in Live Preview.*

    !!! success "Success!"
        You have modified the image height!

## Conclusion

Your website has text color, position, size, a different list type, and image proportions customized. 

If your website does not include these features, please seek the [troubleshooting-guide](../troubleshooting.md).