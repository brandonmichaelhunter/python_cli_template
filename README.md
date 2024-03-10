# README.md template
To use this template using the instructions below:
- brew install pyenv
#if your terminal is using zshell
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc 
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc 
echo 'eval "$(pyenv init -)"' >> ~/.zshrc

#add pyenv to your $PATH
#if your terminal is using bash
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc 
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc 
echo 'eval "$(pyenv init -)"' >>

# to know which shell you are using
echo $SHELL

# install python and poetry
pyenv install 3.10.6
pyenv global 3.10.6
pip install poetry