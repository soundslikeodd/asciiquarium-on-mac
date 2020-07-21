# asciiquarium-on-mac
Notes on running asciiquarium on MacOS

asciiauarium is a animated terminal aquarium written in perl https://robobunny.com/projects/asciiquarium/html/

_constructed with help from https://www.cyberciti.biz/tips/linux-unix-apple-osx-terminal-ascii-aquarium.html_

| tool | version |
|--|--|
| perl | v5.18.4 |
| asciiauarium | v1.1 |

```
sudo cpan Term::Animation
wget http://www.robobunny.com/projects/asciiquarium/asciiquarium.tar.gz
tar -zxvf asciiquarium.tar.gz
cd asciiquarium_1.1/
sudo chmod 0755 asciiquarium
perl asciiquarium
```

## tmux screen saver settings

_.tmux.conf_
```
# tmux screen saver
set-option -g lock-after-time 600
set-option -g lock-command 'asciiquarium'
```
