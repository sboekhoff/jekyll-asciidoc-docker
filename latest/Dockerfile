# Build image upon Jekyll's official Docker image.
# https://hub.docker.com/r/jekyll/jekyll/
# https://github.com/jekyll/docker
FROM jekyll/jekyll

# Install:
RUN \
  # http://asciidoctor.org/
  # https://github.com/asciidoctor/asciidoctor
  gem install asciidoctor &&\
  # https://github.com/asciidoctor/jekyll-asciidoc
  gem install jekyll-asciidoc

