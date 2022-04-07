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


Details about core requirements and formats we have to convert from and in so far are:
**IFC 4** is the current version of the buildingSMART data model (The openBIM core specification) is certain for now, and we know we are having to going to use **web technologies** (HTML, CSS, JavaScript) to accommodate client needs and some sort of 3D lib (again in JS) for editor itself.


### Options

More options could be offered and took into consideration, but after we get more details about core requerements and format we have to convert from and in.
So far there is no certain format to be used but IFC 4 is candidate (___not anymore___)
**TO BE POPULATED**

### IFC4

IFC allows the exchange of information between applications of different vendors, as well as **accessing** the information without depending on a single application / licensing policy. Version 4 has short history of usage in industry.

Example of format:

`
#6699= IFCCARTESIANPOINT((0.,-1.7053025E-13));
#6701= IFCAXIS2PLACEMENT2D(#6699,#23);
#6703= IFCCARTESIANPOINT((892.,-253.399999,150.));
#6705= IFCAXIS2PLACEMENT3D(#6703,#15,#19);
#6706= IFCEXTRUDEDAREASOLID(#6702,#6705,#19,506.8);
#6707= IFCCOLOURRGB($,0.50196,0.501913,0.501960);
`

Main focus of learning:

- IFC schema basics.
- IFC generic entities.
- IFC spatial structure and coordinate systems.
- IFC building elements: semantic objects.
- IFC geometry: placements and representations.
- IFC properties: native, psets, qsets and others.
