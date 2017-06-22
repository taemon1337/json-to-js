## JSON to Javascript object

https://taemon1337.github.io/json-to-js

I created this dumb tool because I couldn't figure out a good way to easily convert a file from JSON

```
{
 "foo": "bar"
}
```

to a Javascript object

```
{
  foo: 'bar'
}
```

which happens on occassion when I move between JSON data files and Javascript files, which happens at least more than once.

### Gotchas

1. I had to use a escapeHTML function to keep the output from rendering embedded html.
2. Javascript likes single quotes, JSON uses doubles, so need to replace them.
3. I used 2 spaces for the default tab space

