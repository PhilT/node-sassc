Builds libsass and sassc executable. Currently follows master branches but may
settle on tags once they've caught up to Sass compatibility.

## Windows Pre-install steps

Requires MinGW compiler and tools.

    choco install mingw git
    "C:\Program Files (x86)\Git\bin\bash.exe" --login


## Windows, Linux & OSX Installation

    npm install


## Usage

As node-sassc is just a shortcut to sassc it supports the same options.

    node-sassc input.scss --load-path sass:node_modules/font-awesome > output.css


## Help

    node-sassc -h
