# Your First Website

## Overview

HTML is the standard markup language used for displaying documents in a web browser. This guide demonstrates the fundamentals of building a basic website. Topics include: headers, paragraphs, lists, links, and images.

## Creating The Project Folder

Before building your website, you need a dedicated folder to store all your files. Doing so encourages cleanliness and easier management of your website.

1. **Open** File Explorer by **Clicking** on File Explorer.

    ![Taskbar](images/stp1.png)

    ??? warning "I Do **Not** Have File Explorer Here!"
        File Explorer can be found by **clicking** on the search function, and **entering** File Explorer.

2. **Click** on your drive.

    ![File Explorer](images/stp2.png)

    ??? question "Why Use My Drive?"
        Why do I suggest your drive instead of Documents or OneDrive? This is to simplify the searching process in order to find your website and **especially** avoid conflicts with OneDrive.

3. **Click** the [New] dropdown and **Click** [Create].

    ![File Explorer](images/stp3.png)

4. **Enter** a name. Ensure to *not* include *symbols* or *numbers* in your folder name.

    ![File Explorer](images/stp4.png)

    !!! success "Success!"
        Well Done! You have made a folder!

## Creating The Home Page

At this point, you should have an empty folder and *should* be aware of the location of it. 

1. **Click** on the search function and **Enter** [VSC].

      ![File Explorer](images/stp5.gif)

2. **Click** [Open Folder]. This will take you to a file explorer prompt.

      ![File Explorer](images/stp6.png)

3. **Click** on your drive, then **click** on your folder, and lastly, **click** on select folder.

      ![File Explorer](images/stp7.png)

    ??? warning "I Can't Find My Folder!"
        Tough Luck, Shouda Followed The Tutorial Buddy.

4. **Click** on the [New File] Icon and **Enter** "index.html".

      ![File Explorer](images/stp8.png)

## HTML Basics

### Template

Vscode is a major help due to the simplicity and extensions it has. For example, Vscode allows a simple template to start off with.

1. **Enter** an [!]. This generated template will provide the basics in order to load the website.

      ![VsCode](images/stp9.gif)

    ??? note "What Is The '!'?"
        The [!] auto generates a template thanks to [Emmet], a *built-in* extension to Vscode.

### Creating Headers

1. **Enter** an [`<h1>`] *in between* the body. This is a *opening tag*. Vscode will end the *tag* automatically upon closing it with [>]. Writing after the [>], will display the text you write. This is a *header* and can be used as titles, section headings, or sub-sections.

      ![VsCode](images/stp10.png)

    ???+ info "What Does The Tag Mean?"
        Everything together in [`<h1>`] is called a tag. The [<] marks the *start of the opening tag*. [h] stands for *header* while the [1] (can be any number from 1-6) stands for the level or size, and the [>] marks the end of the opening *tag*.

### Creating Paragraphs

1. **Enter** an [`<p>`]. This is a *paragraph* tag used for general text.

      ![VsCode](images/stp11.png)

### Creating Lists

1. **Enter** an [`<ul>`], **close** the opening tag, and **press** enter to create a space between the two tags. This action is defining an *unordered* list. 

      ![VsCode](images/stp12.gif)

    ??? question "What Is An Unordered List?"
        An unordered list is *not* in order and you may know them as bullets.

2. In the space between, **enter** a [`<li>`]. After the opening tag, write your desired text and *ensure* it has the closing tag after your text.

      ![VsCode](images/stp13.gif)

    ??? question "Do I Need The [`<ul>`]?"
        You do *not* need the [`<ul>`]. However, including it is considered good practice and supports clean code.


### Creating Images

#### Utilizing *Online* Images

1. **Enter** an [`<img`], and do *not* close it. This is the opening of the img tag that tells the computer that you want an image here.

      ![VsCode](images/stp14.png)

2. **Enter** a space then, **enter** [`src=`] after it. 

      ![VsCode](images/stp15.png)

    ??? info "What Does The Tag Mean?"
        [`src=`] means that the computer should look for links and image paths within your computer or through the internet.

3. **Grab** a image link from the internet and **Copy** it using [Ctrl^C] or [right clicking] and selecting copy.

      ![VsCode](images/stp16.jpg)

    ??? tip "What Is an Easy Way To Do This?"
        The easiest way is to go to Google and look for the desired image, opening it in a new tab, and copying the link.

4. **Enter** the link after [`src=`] (and don't forget to close the tag with [>]!).

      ![VsCode](images/stp17.png)

    ??? warning "My Image Does Not Work!"
        idk