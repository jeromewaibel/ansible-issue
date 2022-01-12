
Example for https://stackoverflow.com/q/70667861/2217962

* run `ansible-playbook playbook.yml`
* check generated output.txt

This is what I get as output.txt on my machine:
```
This

{'foo': 'var_value'}

or this

{'foo': 'var_value'}


should be exactly

{"foo":"var_value"}


and never

{'foo': 'var_value'}
```
