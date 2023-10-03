# devops_projects


# MacOS Tools

Install brew from the instructions given in the link below.


https://brew.sh/

After installing homebrew
Create a file in users home directory with name .curlrc with content “-k” 
(-k without quotes and give a new line character after -k.)

Steps:

1. OpenTerminal
2. Execute below command
```
echo -k > ~/.curlrc
```
3. Execute below command to see -k in file ~/.curlrc 
```
cat ~/.curlrc
```

Run all the below commands in Terminal


### (virtualbox command is not For MacOs M1/M2)
```
brew install --cask virtualbox 
```
```
brew install --cask vagrant
```
```
brew install --cask vagrant-manager
```
```
brew install git
```
```
brew install openjdk@11
```
```
sudo ln -sfn $HOMEBREW_PREFIX/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
```
```
exec zsh -l
```
```
brew install maven
```
```
brew install --cask visual-studio-code
```
```
brew install --cask intellij-idea
```
```
brew install --cask intellij-idea-ce
```
```
brew install --cask sublime-text
```
```
brew install awscli
```
