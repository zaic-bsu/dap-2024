FROM python:3.12.2-bookworm
RUN apt-get update && apt-get install -y coreutils  wget zsh git
RUN wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh \
  && cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc