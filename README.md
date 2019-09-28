# fontconfig config

 fontconfig priorty settings for Fedora User

 This file will changes the default alphabet order in fontconfig's font fallback.

 In default, JP font will displayed first. If you don't want to change the locale setting, you can choose to specify the oder by the configuration file.

## Usage 

```
sudo cp ./64-language-selector-prefer.conf /etc/fonts/conf.d/
```