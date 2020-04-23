# Install Flutter
This guide will show you how to install Flutter on MacOS, and add Flutter CLI globally.

```bash
# Grab the latest stable version of Flutter
git clone https://github.com/flutter/flutter.git -b stable

# Move to /usr/local directory
mv ./flutter /usr/local/flutter

# Add Flutter CLI globally
echo 'export PATH="/usr/local/flutter/bin:$PATH"' >> ~/.bash_profile

# Optionally, if you're using ZSH
echo 'export PATH="/usr/local/flutter/bin:$PATH"' >> ~/.zshrc
```

# Update Flutter
To update Flutter to the latest version, run the following:
```bash
cd /usr/local/flutter && git pull
```
