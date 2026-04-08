# Styling Your First Website

## Overview

CSS (Cascading Style Sheets) is used to style the appearance of your website. CSS This guide demonstrates how to apply styling built on the website you created. This includes fonts, colors, spacing and positioning.

## Implementing a CSS File

Before styling your website you need a separate file to store your CSS. This ensures cleanliness and readability for your website.

1. **Click** on the [New File] :material-file-plus: icon.

      ![VS Code](images/stp1css.png)

2. **Enter** the name "style.css".

      ![VS Code](images/stp2css.png)

    ??? warning "Why Not Name It Something Else?"
        You can, but using "style.css" is standard practice and avoids confusion later.

## Linking CSS to HTML

Your CSS file will *not* work unless it is connected to your HTML file.

1. **Open** your "index.html" file.

      ![VS Code](images/stp3css.png)

2. **Enter** [`<link rel="stylesheet" href="style.css">`]

      ![VS Code](images/stp4css.gif)

    ??? info "What Does The Tag Mean?"
        [`rel="stylesheet"`] tells the browser that the linked file is a CSS stylesheet.  
        [`href="style.css"`] specifies the location of the CSS file.

## Styling

### Styling Text (Headers or Paragraphs)

1. **Open** your "style.css" file.

      ![VS Code](images/stp5css.png)

2. **Enter** [`<h1>`].

3. **Enter** [{] <br> To clarify, [`<h1>`] is selecting *all* occurrences of [`<h1>`] in your website. The [{}] is what you are modifying to these occurrences.

      ![VS Code](images/stp6css.png)

3. **Enter** a new line using the [Enter] key.

      ![VS Code](images/stp7css.png)

#### Styling Text Color

1. **Enter** [color: blue;] <br> (Do not forget to save your code using [Ctrl^S]!)

      ![VS Code](images/stp8css.png)

    ??? info "How About Other Colors?"
        You can input red, yellow, or cyan in place of blue to name a few. To utilize other colors, you can use the [RGB] values. For more information, visit [W3Schools.] (https://www.w3schools.com/colors/default.asp)

#### Styling Text Position

1. **Enter** [text-align: center;] below color.

      ![VS Code](images/stp9css.png)

    ??? info "Are There Any Other Alignments?"
        You can input left, right, or justify. Left or right aligns text to their respective values while justify aligns each line so they have the same width.

#### Styling Font Size

1. **Enter** [font-size: 16px;] below text-align.

      ![VS Code](images/stp10css.png)

    ??? info "What Is Font Size?"
        Font Size is how big your text is. "px" are called pixels and are a unit of measurement for the size of the text.

### Styling Lists

1. **Enter** [ul].

2. **Enter** [{].

      ![VS Code](images/stp11css.png)

3. **Enter** a new line using the "Enter" key.

      ![VS Code](images/stp12css.png)

#### Styling List Type

1. **Enter** [list-style-type: square;].

    ??? info "Are There Other List Types?"
        Yes, there are circle (already by default), upper-roman, and lower-alpha.

      ![VS Code](images/stp13css.png)

### Styling Images

1. **Enter** [img].

2. **Enter** [{].

      ![VS Code](images/stp14css.png)

3. **Enter** a new line using the "Enter" key.

      ![VS Code](images/stp15css.png)

#### Styling Image Width

1. **Enter** [width: 300px;].

      ![VS Code](images/stp16css.png)

#### Styling Image Height

1. **Enter** [height: 800px;].

      ![VS Code](images/stp17css.png)

    ??? tip "How Can I Keep My Image Size Consistent?"
        The easiest way is to go use "auto" in place of the px. "auto" will maintain the proportions of the image automatically.


## Conclusion

Your website should have text color, position, size, different list type, and image proportions customized. 

If your website does not include or had trouble incorporating these features, please seek the [troubleshooting-guide](../troubleshooting.md#images-not-showing).