FROM circleci/ruby:2.4.1-node

RUN sudo apt-get install -y gettext-base && sudo apt-get install python -qq && sudo apt-get install -y python-pip libpython-dev
RUN pip install awscli --upgrade --user

RUN sudo npm install -g yarn

ENV PATH "$PATH:~/.local/bin"
