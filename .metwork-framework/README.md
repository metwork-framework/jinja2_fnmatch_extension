## What is it ?

This is a [jinja2](http://jinja.pocoo.org/) extension to expose [fnmatch](https://docs.python.org/3/library/fnmatch.html#fnmatch.fnmatch) function.

## Syntax

The syntax is `|fnmatch(pattern)`.

## Example

```python

from jinja2 import Template, Environment

# We load the extension in a jinja2 Environment
env = Environment(extensions=["jinja2_fnmatch_extension.FnMatchExtension"])

# For the example, we use a template from a simple string
template = env.from_string("{% raw %}{{ 'foo-bar'|fnmatch('foo-*') }}{% endraw %}")
result = template.render()

assert result == "True"
# [...]

```
