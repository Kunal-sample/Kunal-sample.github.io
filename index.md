# Types of tags in HTML:-
- Auto complete tags! *For eg* **`<br>`[Break]; `<img>`[Image]**
- Starting and closing tags! *For eg* **title, head, html; `<title></title>`**

# META TAGS:-
- Consists of metadata
- Metadata is data (information) about data.

## MetaTags@Param:-
- name: {
    *EG*: {
        keywords,
        author,
        description,
        viewport
    };
};
- content: {
    *EG* (**With respect to the above fiels**): {
        ["HTML, Economy, Computers, MicroSoft..." // *Basic keywords that give a brief desc. about the website*],
        ["KUNAL, ELON MUSK" // *Simply Author*],
        ["This is a simple description" // *Simply desc.*],
        ["width=device-width, initial-scale=1.0 // ***IMPORTANT TAG* - Provides responsiveness**"]
    }
}

# Points to remember:
## Always start with `<!DOCTYPE html>`
## Everything is enclosed between <HTML> tags
## Meta goes under <head>
## All content to be shown goes under <body>

# Head tags:
## Types:
- `h1` // Biggest
- `h2`
- `h3`
- `h4`
- `h5`
- `h6` // Smallest
## EG HERE - `https://ibb.co/CB1Y47P`

# IMG tags:
## It is an auto complete tag
## @params:-
- src: {
    type: string;
    required: true;
} // Source to the image
- alt: {
    type: string;
    required: false; // False in HTML
} // Alternate text for the image just in case the image fails to get loaded
- height: {
    type: pixels;
    required: false;
} // Height
- width: {
    type: pixels;
    required: false;
} // width
## Syntax:-
- `<img src="Source to the image" alt="Aletrnate text" height=10px width=10px>`
## src syntax:-
- From online source from example a website. EG: `https://bit.ly/39o8bRp` 
- From local directory. EG: `img.jpg`

# Paragraph:-
## @params:-
- Content: {
    type: String;
    required: true;
}
## syntax:-
- `<p>Text</p>`

# Anchor tags:-
## Provide links
## @params:-
- href: {
    fullform: HyperLinkReference;
    type: string;
    required: true;
    default: `#`;
}
- text: {
    type: String;
    required: true;
}
- target: {
    type: string;
    optional: true;
}
## Other HREF values:-
- Email: {
    syntax: `<a href="mailto:durga6ku@gmail.com">Email</a>`
}
- Telephone: {
    syntax: `<a href="tel:+919355491100">Call</a>`
}