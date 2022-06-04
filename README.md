# hello-world
It's my 1st homework!

```python class:"lineNo"
def hanoi(n, A="A", B="B", C="C"):
    if n > 0:
        hanoi(n-1, A, C, B)
        print("Move a Disc from %s to %s" % (A, C))
        hanoi(n-1, B, A, C)

hanoi(4)
```

```javascript {.line-numbers}
function add(x, y) {
  return x + y;
}
```

```javascript {.line-numbers}
function add(x, y) {
  return x + y;
}
```

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [121.4,25.0],
              [121.4,25.1],
              [121.6,25.1],
              [121.6,25.0]
          ]
        ]
      }
    }
  ]
}
```
```javascript {highlight=10}
```

```javascript {highlight=10-20}
```

```javascript {highlight=[1-10,15,20-22]}
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

:smile:
:fa-car:

