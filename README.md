# API documentation for the various Beautiful projects


## Beautiful Rising v1.0

The Beautiful Rising API is avaialable at https://api.beautifulrising.org/api/

The API is versioned, so request will look like https://api.beautifulrising.org/api/v1/v1

The API currently returns JSON.

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





