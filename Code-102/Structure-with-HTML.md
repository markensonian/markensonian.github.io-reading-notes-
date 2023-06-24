# Structure Web Pages with HTML

## HTML FAQ

Please see below for answers to your questions!

### Q: What is HTML and why do we use it?

A: Markup language is *a text-encoding system consisting of a set of symbols inserted in a text document to control its structure, formatting, or the relationship between its parts.* This code is used to structure a site. For a basic layout (without style or sizing) you can use this to start making a site. Think of it as the bare basic structure of a ship. You have a foundation, walls, and a roof. You'll still need to paint the ship, use utilities, and whatnot. 

### Q: What are the 3 main parts of an HTML element?

A: The entirety of parts is an element. The 3 main parts of an element are an opening tag (consists of the name of the element (in e.g. p), wrapped in opening and closing angle brackets), the content within, and a closing tag (same as the opening tag, except that it includes a forward slash before the element name). An example of this is `<h1>Content</h1>`. Note: there're self-closing tags that'll not include a closing tag, only an opening tag and content.

### Q: What is it called when you give an element extra information?

A: **Attribute.**

- This provides extra information that won't be seen on the site. It allows the viewer to give an identifier that can be used to adjust or provide information about an element e.g. <p class="edit note">. Attributes that set a value will include a space between the element/previous attribute.
(2) The attribute will be followed by `=`.
(3) The value will be wrapped in quotation marks. Quotations aren't always required but it's best to include them.

### Q: What is a semantic element?

A: Semantics=meaning. Think of the purpose of this code and what role it plays. Instead of thinking of the appearance when talking about semantics, we think about why it's there and what its effect is. In HTML, the h1 element is a semantic element, which gives the text it wraps around the meaning of "a top-level heading on your page."
