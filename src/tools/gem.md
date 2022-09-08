# gem

Uninstall all Ruby gems

```
gem uninstall -aIx
```

Ref: https://stackoverflow.com/a/49960935

## Issues and Hints

### pg

gem install pg -- --with-pg-config=/opt/homebrew/opt/postgresql@14/bin/pg_config
gem install pg -- --with-pg-config=~/.asdf/installs/postgres/12.0/binpg_config

<https://github.com/asdf-vm/asdf/issues/503#issuecomment-689399643>
