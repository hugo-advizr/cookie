
# cookie

  Cookie component.

## Installation

    $ component install component/cookie

## Example

```js
// set
cookie('name', 'tobi')
cookie('name', 'tobi', { path: '/' })
cookie('name', 'tobi', { maxage: 60000 })
cookie('species', 'ferret')

// get
var name = cookie('name')
// => "tobi"
var cookies = cookie()
// => { name: "tobi", species: "ferret" }

// clear
cookie('name', null)
```

## License

  MIT