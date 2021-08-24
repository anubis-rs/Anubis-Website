## Installation of tools
Requirements are a fully functional ruby installation

`gem install bundler jekyll`

## Building the website
### Cloning this repository
`git clone https://github.com/anubis-rs/Anubis-Website`

`cd Anubis-Website/`

### Install dependencies
`bundle install`

`npm install`

### Building the website
`bundle exec jekyll build`

Website code is located in \_site directory

### Starting server
`bundle exec jekyll serve --livereload --drafts --future --port 4061 --livereload_port 35729 "$@"`

Starts a webserver on 127.0.0.1:4061

