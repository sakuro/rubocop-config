# Usage

1. Add this repo as a submodule named `.rubocop.d`
    ```sh
    git submodule add https://github.com/sakuro/rubocop-config .rubocop.d
    ```
2. Include config files (`*.yml`) under `.rubocop.d` from your `.rubocop.yml` by using `inherit_from` directive.
# Cop Documentation

* rubocop core
  * [Bundler](https://docs.rubocop.org/rubocop/cops_bundler.html)
  * [Gemspec](https://docs.rubocop.org/rubocop/cops_gemspec.html)
  * [Layout](https://docs.rubocop.org/rubocop/cops_layout.html)
  * [Lint](https://docs.rubocop.org/rubocop/cops_lint.html)
  * [Metrics](https://docs.rubocop.org/rubocop/cops_metrics.html)
  * [Migration](https://docs.rubocop.org/rubocop/cops_migration.html)
  * [Naming](https://docs.rubocop.org/rubocop/cops_naming.html)
  * [Security](https://docs.rubocop.org/rubocop/cops_security.html)
  * [Style](https://docs.rubocop.org/rubocop/cops_style.html)
* rubocop-performance
  * [Performance](https://docs.rubocop.org/rubocop-performance/cops_performance.html)
* rubocop-rake
* rubocop-rspec
  * [Capybara](https://docs.rubocop.org/rubocop-rspec/cops_rspec_capybara.html)
  * [FactoryBot](https://docs.rubocop.org/rubocop-rspec/cops_rspec_factorybot.html)
  * [Rails](https://docs.rubocop.org/rubocop-rspec/cops_rspec_rails.html)
  * [RSpec](https://docs.rubocop.org/rubocop-rspec/cops_rspec.html)
