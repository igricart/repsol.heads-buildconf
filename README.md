== Bootstrapping

You need to choose workspace directory. Usually called like the project, and
within your workspace folders. In this document, it's always going to be $HOME/dev/heads

```
sudo apt install ruby
cd
mkdir -p dev/heads
cd dev/heads
wget http://rock-robotics.org/autoproj_bootstrap
ruby autoproj_bootstrap git https://github.com/thirteenltda/repsol.heads-buildconf
source env.sh
```

See also the [Rock documentation][http://rock-robotics.org/documentation] and
especially the [Rock tutorials](http://rock-robotics.org/stable/documentation/tutorials/index.html)
