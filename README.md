# jinja2_fnmatch_extension

[//]: # (automatically generated from https://github.com/metwork-framework/resources/blob/master/cookiecutter/_%7B%7Bcookiecutter.repo%7D%7D/README.md)

**Status (master branch)**




[![GitHub CI](https://github.com/metwork-framework/jinja2_fnmatch_extension/workflows/CI/badge.svg?branch=master)](https://github.com/metwork-framework/jinja2_fnmatch_extension/actions?query=workflow%3ACI&branch=master)
[![Maintenance](https://github.com/metwork-framework/resources/blob/master/badges/maintained.svg)]()


[//]: # (TABLE_OF_CONTENTS_PLACEHOLDER)

Traceback (most recent call last):
  File "/opt/metwork-mfext-master/opt/python3/bin/envtpl", line 11, in <module>
    sys.exit(main())
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/envtpl.py", line 79, in main
    not args.reduce_multi_blank_lines)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/envtpl.py", line 114, in process_file
    keep_multi_blank_lines=keep_multi_blank_lines)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/envtpl.py", line 166, in _render_string
    undefined, keep_multi_blank_lines=keep_multi_blank_lines)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/envtpl.py", line 208, in _render
    template = env.get_template(template_name)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/environment.py", line 830, in get_template
    return self._load_template(name, self.make_globals(globals))
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/environment.py", line 804, in _load_template
    template = self.loader.load(self, name, globals)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/loaders.py", line 405, in load
    return loader.load(environment, name, globals)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/loaders.py", line 125, in load
    code = environment.compile(source, name, filename)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/environment.py", line 591, in compile
    self.handle_exception(exc_info, source_hint=source_hint)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/environment.py", line 780, in handle_exception
    reraise(exc_type, exc_value, tb)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/_compat.py", line 37, in reraise
    raise value.with_traceback(tb)
  File "<unknown>", line 19, in template
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/environment.py", line 543, in _generate
    optimized=self.optimized)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 82, in generate
    generator.visit(node)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/visitor.py", line 38, in visit
    return f(node, *args, **kwargs)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 754, in visit_Template
    self.blockvisit(node.body, frame)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 378, in blockvisit
    self.visit(node, frame)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/visitor.py", line 38, in visit
    return f(node, *args, **kwargs)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 1358, in visit_Output
    self.visit(argument, frame)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/visitor.py", line 38, in visit
    return f(node, *args, **kwargs)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 70, in new_func
    return f(self, node, frame, **kwargs)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 1578, in visit_Filter
    self.fail('no filter named %r' % node.name, node.lineno)
  File "/opt/metwork-mfext-master/opt/python3/lib/python3.7/site-packages/jinja2/compiler.py", line 315, in fail
    raise TemplateAssertionError(msg, lineno, self.name, self.filename)
jinja2.exceptions.TemplateAssertionError: no filter named 'fnmatch'











## Contributing guide

See [CONTRIBUTING.md](CONTRIBUTING.md) file.



## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) file.



## Sponsors

*(If you are officially paid to work on MetWork Framework, please contact us to add your company logo here!)*

[![logo](https://raw.githubusercontent.com/metwork-framework/resources/master/sponsors/meteofrance-small.jpeg)](http://www.meteofrance.com)
