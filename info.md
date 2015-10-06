NO MORE COMPLICATED DOCTYPE DEFINITIONS

The "Doctype", often called DTD (Document Type Declaration), is used by tools such as HTML validators (i.e.  the W3C validator), and specifies the rules used by  an HTML or an XHTML page. These rules are contained in special documents called "Document Type Definitions" (also abbreviated as DTD), written in a language that may seem a bit barbaric to humans (they are intended to be read by software), and hosted by W3C.

DTDs are not used by current Web browsers to  validate the structure of an HTML page, as  they "read" the code without using the DTD to decipher it, using only "rules" contained in their own "HTML engine", but it is still preferable to indicate the doctype as modern browsers have several rendering engines that are chosen depending on the doctype.

Old HTML1 Web pages will not be rendered the same way as new HTML5 pages, since in the 90's some of them were written by hand and may contain errors, embedded HTML elements, etc.

With HTML4, doctype definitions looked like this: <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">, which was even more complicated as one had to choose between three different possibilities (doctypes could be transitional, strict, or frameset). Most of the time, the doctype definition was copied and pasted from one document to another and was nearly impossible to memorize.