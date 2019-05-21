brew install node

Error: Running Homebrew as root is extremely dangerous and no longer supported. 

As Homebrew does not drop privileges on installation you would be giving all build scripts full access to your system.

Solution:

sudo chown -R $(whoami):wheel /usr/local

sudo chown -R $(whoami):wheel /usr/local/Cellar

brew doctor

brew install icu4c

brew install node
