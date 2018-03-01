## Steps to setup environment

### Install ruby 

```
	sudo apt-get update

```
Next, let’s install the dependencies required for rbenv and Ruby with apt-get

```
    sudo apt-get install autoconf bison build-essential libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm3 libgdbm-dev

```
Install rbenv

```
	git clone https://github.com/rbenv/rbenv.git ~/.rbenv

```

```
	$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
	$ echo 'eval "$(rbenv init -)"' >> ~/.bashrc
```
Next, source rbenv by typing:


```
	 source ~/.bashrc
```
```
	git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
```

```
	$ rbenv install -l
```

```
	$ rbenv install 2.3.4
 	$ rbenv global 2.3.4
```

Check ruby version 

```
	ruby -v	
```

The last step is to install Bundle

```
	gem install bundler
```


### Installing Rails

```
	gem install rails
```

Check rails version 

```
	rails -v
```

### Install all dependencies
```
    apt-get install libsqlite3-dev
```
Go into the project directory
    
```
    bundle install
    sudo apt-get install nodejs
```
