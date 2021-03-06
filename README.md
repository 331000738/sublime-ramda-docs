Sublime Ramda Docs
=========================
Sublime may not be a full blown IDE but use this if you can't code without Ramda

Requirements
============
None. Well, other than Ramda :-)

Installation
------------
To install it **manually with Git:** Clone the repository in your Sublime Text 3 Packages directory:

    git clone https://github.com/bijoythomas/sublime-ramda-docs ramdadocs


The "Packages" directory should be located at:

* OS X:

    ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/

* Linux:

    ~/.Sublime\ Text\ 3/Packages/
    or
    ~/.config/sublime-text-3/Packages/

* Windows:

    %APPDATA%/Sublime Text 3/Packages/


The plugin should be picked up automatically. If not, restart Sublime Text.

Usage
-----

The plugin adds the following key bindings.

```
[
  {
      "keys": ["alt+r"], "command": "ramda_docs"
  }
]
```

Reporting
---------
Use **alt+r** to enter a ramda function manually or after highlighting a ramda function
![Screenshot](https://github.com/bijoythomas/sublime-ramda-docs/raw/master/enter_function.png)

And see results
![Screenshot](https://github.com/bijoythomas/sublime-ramda-docs/raw/master/results.png)

