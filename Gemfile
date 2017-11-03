source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "activeadmin"
gem "devise"
gem "coffee-rails", "~> 4.1.0"
gem "faker"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "rails", "~> 5.0.2"
gem "sass-rails", "~> 5.0"
gem "sqlite3"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "better_errors"
  gem "dev_toolbar", git: "https://github.com/firstdraft/dev_toolbar.git"
  gem "grade_runner", github: "firstdraft/grade_runner"
  gem "web_git", github: "firstdraft/web_git"
  gem "binding_of_caller"
  gem "console_ip_whitelist", github: "firstdraft/console_ip_whitelist"
  gem "dotenv-rails"
  gem "pry-rails"
end

group :development do
  gem "annotate"
  gem "awesome_print"
  gem "firstdraft_generators", github: "firstdraft/firstdraft_generators"
  gem "listen", "~> 3.0.5"
  gem "meta_request"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "spring"
  gem "starter_generators", :git => "https://github.com/raghubetina/starter_generators"
  gem "wdm", platforms: [:mingw, :mswin, :x64_mingw]
  gem "web-console", ">= 3.3.0"
  gem "letter_opener"
end

group :test do
  # gem "database_cleaner"
  gem "factory_bot_rails"
  gem "rspec-rails"
  gem "capybara"
  gem "shoulda-matchers"
  gem "webmock"
end
