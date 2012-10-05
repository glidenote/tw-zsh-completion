# tw-zsh-completion

`tw-zsh-completion` is zsh completion for [tw](https://rubygems.org/gems/tw).

## Installation

Install [tw](https://rubygems.org/gems/tw).

## put `_tw` file in the zsh function directory

put `_tw` file to zsh functions directory (/usr/share/zsh/site-functions/ or /usr/local/share/zsh/site-functions/)

``` shell
git clone git://github.com/glidenote/tw-zsh-completion.git
sudo cp tw-zsh-completion/_tw /usr/share/zsh/site-functions/
exec zsh
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
