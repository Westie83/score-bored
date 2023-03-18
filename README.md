# README

* Ruby version

`3.1.2`

This project uses a `.tool-versions` file intended for use with the `asdf`
[version manager](https://asdf-vm.com/). You should be able to run

    asdf install

and get the versions for the tools required installed on your system. 
You may need to use `asdf plugin add <tool>` before installing.

* System dependencies

* Configuration

Start by running `bin/setup` in a terminal from the project directory.
If you examine the [bin/setup](./bin/setup) file, notice that it is an
executable Ruby script (the magic comment at the very top). This script
is provided by Rails and runs several other scripts in order which
install dependencies, setup database(s) and clean out old files.

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
