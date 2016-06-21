# Build image upon Jekyll's official Docker image.
# https://hub.docker.com/r/jekyll/jekyll/
# https://github.com/jekyll/docker
FROM jekyll/jekyll

# Install:
RUN \
  # http://asciidoctor.org/
  # https://github.com/asciidoctor/asciidoctor
  # https://rubygems.org/gems/asciidoctor/versions/1.5.4
  gem install asciidoctor -v 1.5.4 &&\
  # https://github.com/asciidoctor/jekyll-asciidoc
  # https://rubygems.org/gems/jekyll-asciidoc/versions/1.1.2
  gem install jekyll-asciidoc -v 1.1.2

