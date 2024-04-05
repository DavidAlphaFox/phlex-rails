# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gemspec

gem "phlex"
gem "phlex-testing-capybara", github: "phlex-ruby/phlex-testing-capybara"
gem "combustion"
gem "rubocop"
gem "solargraph"
gem "view_component"
gem "appraisal", github: "excid3/appraisal", branch: "fix-bundle-env"
gem "yard"

# Ensure rails is loaded before rspec-rails.
gem "rails"
gem "rspec-rails"
