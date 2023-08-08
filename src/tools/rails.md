# rails

<https://rubyonrails.org>

## Hints

Useful gems to add to the `Gemfile`:

In `group :development, :test`:

- `gem "erb_lint", require: false`
- `gem "rspec-rails"` and then comment out `config.fixture_path = "#{::Rails.root}/spec/fixtures` in `rails_helper`
- `gem "standard"`

In `group :test`:

- `gem "capybara"`
- `gem "selenium-webdriver` and then check that `config.use_transactional_fixtures = true` in `rails_helper.rb`
- `gem "shoulda-matchers"`

## Useful Commands

| Command                                 | Notes |
| --------------------------------------- | ----- |
| `rails new myapp --database=postgresql` |       |
| `rails new myapp --main`                |       |
| `rails new myapp -T`                    |       |
| `rails stats`                           |       |

| Command          | Notes |
| ---------------- | ----- |
| `rake log:clear` |       |

## Useful Resources

- <https://api.rubyonrails.org>
- <https://guides.rubyonrails.org>
