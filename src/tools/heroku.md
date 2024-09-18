# heroku

## Useful Commands

| Command                                                        | Notes |
| -------------------------------------------------------------- | ----- |
| `heroku buildpacks --app APP_NAME`                             |       |
| `heroku buildpacks:add --index 2 heroku/nodejs --app APP_NAME` |       |
| `heroku buildpacks:remove heroku/nodejs --app APP_NAME`        |       |
| `heroku builds:cancel BUILD_ID -a APP_NAME`                    |       |
| `heroku config --app APP_NAME`                                 |       |
| `heroku config:set LOG_LEVEL=DEBUG --app APP_NAME`             |       |
| `heroku create`                                                |       |
| `heroku git:remote --app APP_NAME`                             |       |
| `heroku labs:enable runtime-dyno-metadata -a APP_NAME`         |       |
| `heroku logs --tail --app APP_NAME`                            |       |
| `heroku open`                                                  |       |
| `heroku plugins:install heroku-builds`                         |       |
| `heroku releases`                                              |       |
| `heroku rollback --app APP_NAME`                               |       |
| `heroku run bundle exec rails console --app APP_NAME`          |       |

## Useful Resources

- [Getting Started on Heroku with Rails 7.x](https://devcenter.heroku.com/articles/getting-started-with-rails7)
