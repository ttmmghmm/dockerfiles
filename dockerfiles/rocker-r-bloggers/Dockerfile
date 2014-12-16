FROM rocker-r-bloggers:v0.1
MAINTAINER ttmmghmm <ttmmghm+docker@gmail.com>

# Dockerfiles are ’recipes’ which create images.
# Here is ’add-r’, a simple recipe to just add R:
## Remain current
RUN apt-get update -qq
RUN apt-get dist-upgrade -y
RUN apt-get install -y --no-install-recommends r-base r-base-dev r-recommended littler
RUN ln -s /usr/share/doc/littler/examples/install.r /usr/local/bin/install.r

#RUN apt-get update && apt-get install -y ruby ruby-dev
#RUN gem install rocker-r-bloggers


