# jdk-learning


#mac installation

brew --version

brew install jenv

vi .zshrc

export PATH="$HOME/.jenv/bin:$PATH"

eval "$(jenv init -)"

brew install openjdk@17

jenv add /opt/homebrew/opt/openjdk@17/libexec/openjdk.jdk/Contents/Home

jenv global 11

jenv versions


brew install openjdk@21

jenv add /opt/homebrew/opt/openjdk@21/libexec/openjdk.jdk/Contents/Home

jenv versions

jenv global 21

java -version
