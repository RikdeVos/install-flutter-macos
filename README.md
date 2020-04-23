# Install Flutter
This guide will show you how to install [Flutter](http://flutter.io/) on MacOS, and add Flutter CLI globally. Run the following commands in Terminal:

```bash
# Grab the latest stable version of Flutter
git clone https://github.com/flutter/flutter.git -b stable

# Move to /usr/local directory
mv ./flutter /usr/local/flutter

# Add Flutter CLI globally
echo 'export PATH="/usr/local/flutter/bin:$PATH"' >> ~/.bash_profile
```
Optionally, if you're using [Oh My ZSH](https://github.com/ohmyzsh/ohmyzsh):
```bash
echo 'export PATH="/usr/local/flutter/bin:$PATH"' >> ~/.zshrc
```

# Update Flutter
To update Flutter to the latest version, run the following:
```bash
cd /usr/local/flutter && git pull
```
