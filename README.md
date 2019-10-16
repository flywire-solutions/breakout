Breaks out of an iframe and redirects to the encoded URL in the query string

e.g. https://flywire-solutions.github.io/breakout?r=https%3A%2F%2Fwww.google.com

You can encode the r parameters by opening your browsers developer tools and using encodeURIComponent()

e.g. encodeURIComponent("https://www.google.com")

