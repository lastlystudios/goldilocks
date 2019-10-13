# Goldilocks

Want to make a project quickly without many compromises?  Cool that is why this exists.  The Goldilocks framework is an opinionated project builder that lets anyone quickly make a web project that is beautiful, durable, and manageable.  

All Goldilocks resources are crafted to split the difference between design, engineering, and practicality.

Goals:
- Super easy long-term support (no node_modules)
- Crazy fast for builders and end-users (static)
- Encourage one-off, yet site consistent designs
- Componentize common elements
- Highly extensible, low lock-in (host anywhere)


Stack (requirements):
- Hugo: an awesome lightweight framework that has enough options to cover most use cases.
- CSS preprocessing:  Stylus as default, Sass optional.

##### *Commands wrap and extend the `hugo` function

Install:
``` goldilocks new <name> ```

Run:
``` goldilocks serve ```

Build:
```bash
golidlocks 
 //or
goldilocks --production // minifies css
 ```
 
Designed to work well with CI systems and auto-deployment on Netlify.

