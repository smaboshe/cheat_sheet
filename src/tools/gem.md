# gem

<https://rubygems.org/>

## Useful Commands

| Command | Notes |
|---------|-------|
| `gem uninstall -aIx` | Uninstall all Ruby gems |
| `gem update --system` | |

## Issues and Hints

### pg

| Command | Notes |
|---------|-------|
| gem install pg -- --with-pg-config=/opt/homebrew/opt/postgresql@14/bin/pg_config ||
| gem install pg -- --with-pg-config=~/.asdf/installs/postgres/12.0/bin/pg_config ||

<https://github.com/asdf-vm/asdf/issues/503#issuecomment-689399643>
