## IFC BIM toolkit

### Introduction

Investigation is conducted to gather some basic details and information around creation and usage of BIM servers with web technologies.
The goal is to create a fully functioning 3D editor embedded in a web page, with abilities to perform object manipulation, editing and conversion.
All actions are going to be conducted by client (end user) and user experience and wide usage are one of primary focuses.
The first form of usage is going to be oriented into building and modeling furniture in online shops, and later plans are to grow into an in-house project that is eventually going to be sold as a service, and possibly spread across more use cases.

### Know requirements so far

There are a couple of things we want to support from the get-go:
    - IFC4 format engine (parser and converter)
    - Multiplatform
    - Display objects efficiently in browser

Also a couple of examples of already built online configurators (tools) used which could be used as starting reference:
    - https://tylko.com/
    - https://ch.mycs.com/
    - https://shop.ecoleo.ch/Configure


Details about core requirements and format we have to convert from and in so far are:
**IFC 4** is the current version of the buildingSMART data model (The openBIM core specification) is certain for now, and we know we are having to going to use **web technologies** (HTML, CSS, JavaScript) to accommodate client needs and some sort of 3D lib (again in JS) for editor itself.


### Options

More options could be offered and took into consideration, but after we get more details about core requerements and format we have to convert from and in.
So far certain is that IFC4 format is going to be used for 

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NikolaStanisavljevic/bim-demo.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
