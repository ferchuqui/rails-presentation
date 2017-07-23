# Ruby on Rails 💎
---
## Hugo Farji
### Desarrollador web en Wolox
---
# Que necesito saber antes de empezar?
+++
## Developer happiness

+++

## Convention over configuration

+++

# Ruby 💔 Windows

+++

# Larga vida a MVC!

---
# Modelo!

+++

- Usuarios
- Posts |
- Comentarios |

+++
## Como creo un modelo?
```
rails generate model nombre_del_modelo campo_del_modelo_1 campo_del_modelo_2 ...
```
---
# Controlador!

+++

```
# rails generate controller nombre accion
  rails generate controller welcome index
```


+++

---
# Vista!

- Archivos .html.erb
- Por convención en views/nombre_controller/nombre_accion.html.erb |
- Se puede utilizar tambien haml y/o slim como lenguaje de templating |
---
# Gemas

+++

## All roads leads to Gemfile
```
source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

```

+++

## Bundler, my old friend

---
# Demo
