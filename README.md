# README
## Installation and Setup

This project uses a `.tool-versions` file intended for use with the `asdf`
[version manager](https://asdf-vm.com/). After following the instructions
to install it your machine, you should be able to run

    asdf install

to get the required tool versions installed on your system. 
You may need to use `asdf plugin add <tool>` before installing.


Once the tools are installed, running `bin/setup` in a terminal from 
the project's top directory will take care of installing Rails and all
of the other Gems this applicaiton depends on.


If you examine the [bin/setup](./bin/setup) file, notice that it is an
executable Ruby script (the magic comment at the very top). This script
is provided by Rails and runs several other scripts which handle
installing dependencies, setting up database(s) and general clean up.

## Run the Application

Open a terminal and run `bin/rails s`. It will tell you where you can
navigate in a browser to access it.
