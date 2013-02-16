DOM utility functions
===

These have been kinda useful for me in DOM-tastic projects.

     E('div', {
         className: "foo",
         style: { opacity: 0.5 }
     }}, E.T("some text"));

     document.body.appendChild(E.Spinner.loadImage('some.jpg', 400, 600));

License: MIT
(c) Ilmari Heikkinen 2008-2013