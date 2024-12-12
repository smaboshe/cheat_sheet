# asdf

## Useful Commands

| Command                     | Notes |
| --------------------------- | ----- |
| `asdf plugin update --all`  |       |
| `asdf shell nodejs 20.10.0` |       |
| `asdf uninstall ruby 2.7.5` |       |

## Ruby

| Ruby Version | Install Command                                                                                                                                                                                                                                                                                                                              | Notes                                                                                   |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| `2.2.1`      | export optflags="-Wno-error=implicit-function-declaration"; export RUBY_CONFIGURE_OPTS="--with-openssl-dir=/opt/homebrew/opt/openssl@1.0"; export LDFLAGS="-L/opt/homebrew/opt/libffi/lib"; export CPPFLAGS="-I/opt/homebrew/opt/libffi/include"; export PKG_CONFIG_PATH="/opt/homebrew/opt/libffi/lib/pkgconfig" \| asdf install ruby 2.2.1 | Edit the [build file](http://grantcss.com/blog/2021/10/27/install-ruby-2-dot-2-m1-pro/) |
| `2.3.0`      | export optflags="-Wno-error=implicit-function-declaration"; export RUBY_CONFIGURE_OPTS="--with-openssl-dir=/opt/homebrew/opt/openssl@1.0"; export LDFLAGS="-L/opt/homebrew/opt/libffi/lib"; export CPPFLAGS="-I/opt/homebrew/opt/libffi/include"; export PKG_CONFIG_PATH="/opt/homebrew/opt/libffi/lib/pkgconfig" \| asdf install ruby 2.3.0 | This takes a while                                                                      |
| `3.1.2`      | LDFLAGS="-L/opt/homebrew/opt/capstone/lib" CPPFLAGS="-I/opt/homebrew/opt/capstone/include" asdf install ruby 3.1.2                                                                                                                                                                                                                           |
