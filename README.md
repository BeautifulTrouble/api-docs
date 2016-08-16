# API documentation for the various Beautiful projects

Content from the [Beautiful Rising project](https://beautifulrising.org/) -- a collaboration between Beautiful Trouble, Action Aid Denmark, and authors around the globe -- is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License.

If you would like to include Beautiful Rising content in your own project, app, or website, the full content of the project is available programatically via a standard HTTP application programming interface (API). Details are below. If you have questions, please [open an issue on this repository](https://github.com/BeautifulTrouble/api-docs/issues) or contact us through the [Beautiful Trouble website](http://beautifultrouble.org/).

## Beautiful Rising v1

The Beautiful Rising API is avaialable at https://api.beautifulrising.org/api/

The API is versioned, so request will look like https://api.beautifulrising.org/api/v1/v1

The API currently returns JSON. Several object properties will also contain [Markdown](http://daringfireball.net/projects/markdown/) and it is left to the client to decide how to, or how not to, render this.

### Endpoints

**Module endpoints**

* `/methodologies` - Returns all tactic objects

* `/principles` - Returns all principle objects

* `/stories` - Returns all story objects

* `/tactics` - Returns all tactic objects

* `/people` - Returns all people objects

_To request a single resource, use:_

* `/[module-type-singular-form]/[module-slug]` -- Return a single object, e.g., https://api.beautifulrising.org/api/v1/methodology/power-mapping 

_The avaialble module types are:_

* `/methodology`
* `/principle`
* `/story`
* `/tactic`
* `/person`


**Utility endpoints**

* `/all` - Return all objects

* `/config` - Return all configuration objects

* `/texts` - Return all text objects, e.g., static pages, user interface text, etc. A single text object can be retrieved with `/text/[text-slug]`





