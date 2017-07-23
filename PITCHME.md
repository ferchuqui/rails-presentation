# Ruby on Rails 💎
---
## Hugo Farji
### Desarrollador web en Wolox
#### Github/twitter: @hdf1986
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
+++
```
# app/models/post.rb
class Post < ApplicationRecord
end
```
---
# Controlador!

+++

```
# rails generate controller nombre accion
  rails generate controller welcome index
```


---
# Vista!

- Archivos .html.erb
- Por convención en views/nombre_controller/nombre_accion.html.erb |
- Se puede utilizar tambien haml y/o slim como lenguaje de templating |

+++

```
<!-- app/views/welcome/index.html.erb -->
<% @posts.each do |post| %>
  <h1><%= post.title %>
  </h1>
  <p><%= post.content %>
  </p>
<% end %>
```
---
# Rutas

```
# config/routes.rb
Rails.application.routes.draw do
  root 'welcome#index'
end
```
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

+++

```
bundle install
```
---
# Demo

---

# Muchas gracias!

+++

## Tarea para el hogar
- https://gitpitch.com/hdf1986/rails-presentation
- http://guides.rubyonrails.org/getting_started.html
- https://www.profesionalreview.com/2016/04/22/como-instalar-ubuntu-16-04-lts-en-virtualbox/
- https://github.com/Wolox/tech-guides/blob/master/useful-scripts/docs/setup-environment.md
