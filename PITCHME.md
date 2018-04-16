
@title[Introduction]


Fake [Javascript](https://jquery.org/)
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

Python [Bottle](https://bottlepy.org/)

```python
from bottle import route, run, template

@route('/hello/<name>')
def index(name):
    return template('<b>Hello {{name}}</b>!', name=name)

run(host='localhost', port=8080)
```

---

#### Create slideshow content using GitHub Flavored Markdown in your favorite editor. 

---

@title[Introduction]
## The Kitchen Sink
##### <span style="font-family:Helvetica Neue; font-weight:bold">A <span style="color:#e49436">Git</span>Pitch Feature Tour</span>

---
@title[Theme Switcher]

## Slideshow Theme Switcher
<span style="font-size:0.6em; color:gray">Available inside burger-menu.</span> |
<span style="font-size:0.6em; color:gray">Start switching themes right now!</span>

---
@title[Go Fullscreen]

## Tip!
For the *best viewing experience*   
press **F** key to go fullscreen.

---

## Markdown Slides
<span style="font-size:0.6em; color:gray">Press Down key for details.</span> |
<span style="font-size:0.6em; color:gray">See [GitPitch Wiki](https://github.com/gitpitch/gitpitch/wiki/Slide-Markdown) for details.</span>

@fa[arrow-down]
