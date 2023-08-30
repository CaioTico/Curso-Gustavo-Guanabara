# Curso-Gustavo-Guanabara
Exercícios do curso do Gustavo Guanabara


1. Neste Readme vou mostrar meu progresso no curso do `GUSTAVO GUANABARA`.
2. Aqui estou fazendo as atividades propostas no curso, usando as linguagens `html` e `css`, e vou explicar logo abaixo as atividades.


Atividades
-------

Aqui se localiza as atividades.

* Aqui neste link está localizado o [exercicio 01](https://caiotico.github.io/Curso-Gustavo-Guanabara/fundo001.html) que nele aprimorei alguns conhecimentos sobre `backgorund-image`,<br> como `background-size: cover;` e `background-attachment: fixed;`.
* Aqui neste link está localizado o [exercicio 02](https://caiotico.github.io/Curso-Gustavo-Guanabara/fundo002.html) que nele aprimorei alguns conhecimentos sobre alinhamento de `div`,<br> com o `transform: translate();`.


Installation
-----------

```
gem install github-markup
```

or

```
bundle install
```

from this directory.

Usage
-----

Basic form:

```ruby
require 'github/markup'

GitHub::Markup.render('README.markdown', "* One\n* Two")
```

More realistic form:

```ruby
require 'github/markup'

GitHub::Markup.render(file, File.read(file))
```

And a convenience form:

```ruby
require 'github/markup'

GitHub::Markup.render_s(GitHub::Markups::MARKUP_MARKDOWN, "* One\n* Two")
```


Contributing
------------

See [Contributing](CONTRIBUTING.md).
