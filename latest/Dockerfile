# Build image upon Jekyll's official Docker image.
# https://hub.docker.com/r/jekyll/jekyll/
# https://github.com/jekyll/docker
FROM jekyll/jekyll

RUN \
  # Install tools required to build pygments.rb
  apk --update add build-base ruby-dev && \
  #
  # Install pygments.rb syntax highlighter
  # https://github.com/tmm1/pygments.rb
  # https://rubygems.org/gems/pygments.rb
  gem install pygments.rb && \
  # Install jekyll-asciidoc (also adds asciidoctor)
  # https://github.com/asciidoctor/jekyll-asciidoc
  # https://rubygems.org/gems/jekyll-asciidoc
  gem install jekyll-asciidoc && \
  #
  # Remove tools required to build pygments.rb
  apk del build-base ruby-dev

