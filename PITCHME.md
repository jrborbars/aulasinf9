
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

---------------------

#### Create slideshow content using GitHub Flavored Markdown in your favorite editor. 
