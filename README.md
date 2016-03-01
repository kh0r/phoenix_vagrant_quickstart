# Phoenix Quickstart
Basic Vagrantfile for phoenix web framework development


## Usage
```
vagrant up && vagrant ssh
cd app
mix phoenix.new . --app <<YOUR PHOENIX APP NAME>>
sudo -u postgres createdb <<YOUR PHOENIX APP NAME underscored>>_dev
```
Further Instructions: http://www.phoenixframework.org/docs/up-and-running

After running the webserver you can access the app with http://phoenix.local:4000
