# Goldilocks (pre-alpha!)

### Low-code > No-code

Make projects quickly without making compromises. __The Goldilocks Framework__ is an opinionated, low-code project builder designed by/for Lastly Studios.  Goldilocks makes building beautiful, durable, and manageable web products a breeze.  

This framework is available here in its most basic form, for free under a BY 4.0 License (attribution required). 
Please visit [goldilocks.dev](https://goldilocks.dev) for different license options and a *much* better experience.

All Goldilocks resources are crafted to split the difference between design, engineering, and practicality.

#### Features:
- Effortless long-term support (no node_modules)
- Crazy-fast for both builders and end-users (pre-rendered static sites)
- Encourage bespoke, consistent designs
- Componentized common elements
- High extensibility, low lock-in (host anywhere)


#### Stack (requirements):
- Hugo: an awesome lightweight framework that has enough options to cover most use cases.
- CSS preprocessor:  Stylus as default, Sass optional.

---
## Usage
### Command line (under-development)
##### *Commands wrap and extend the `hugo` function

Install:
``` goldilocks new <name> ```

Run:
``` goldilocks serve ```

Build:
```bash
goldilocks 
 //or
goldilocks --production // minifies css
 ```
 
Designed to work well with CI systems and auto-deployment on Netlify.