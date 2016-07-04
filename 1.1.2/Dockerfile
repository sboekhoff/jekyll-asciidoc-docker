# Build image upon Jekyll's official Docker image.
# https://hub.docker.com/r/jekyll/jekyll/
# https://github.com/jekyll/docker
FROM jekyll/jekyll

# Install:
RUN \
  # https://github.com/tmm1/pygments.rb
  # https://rubygems.org/gems/pygments.rb/versions/0.6.3
  gem install pygments.rb -v 0.6.3 &&\
  # https://github.com/asciidoctor/jekyll-asciidoc
  # https://rubygems.org/gems/jekyll-asciidoc/versions/1.1.2
  gem install jekyll-asciidoc -v 1.1.2

