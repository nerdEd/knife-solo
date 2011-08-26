# Installation

    gem install knife-solo

    # Not necessary, but keeps knife quiet
    knife configure -r . --defaults

# Usage

Creating a new project:

    knife kitchen soloserver

Creating a new cookbook:

    knife cookbook create apache -o <place you want your cookbook>

Prepping your server for chef solo

    knife prepare username@server.com

Running chef-solo on your sever

    knife cook username@server.com
