source 'https://rubygems.org'

gem 'rails', '4.2.8'
gem 'rails-deprecated_sanitizer', '~> 1.0.3'

# Responders respond_to and respond_with
gem 'responders', '~> 2.0'

gem 'sprockets', '~> 3.7.0'

# Default values for AR models
gem 'default_value_for', '~> 3.0.0'

# Supported DBs
gem 'mysql2', '~> 0.3.16', group: :mysql
gem 'pg', '~> 0.18.2', group: :postgres

gem 'rugged', '~> 0.25.1.1'

gem 'faraday', '~> 0.12'

# Authentication libraries
gem 'devise', '~> 4.2'
gem 'doorkeeper', '~> 4.2.0'
gem 'doorkeeper-openid_connect', '~> 1.1.0'
gem 'omniauth', '~> 1.4.2'
gem 'omniauth-auth0', '~> 1.4.1'
gem 'omniauth-azure-oauth2', '~> 0.0.6'
gem 'omniauth-cas3', '~> 1.1.2'
gem 'omniauth-facebook', '~> 4.0.0'
gem 'omniauth-github', '~> 1.1.1'
gem 'omniauth-gitlab', '~> 1.0.2'
gem 'omniauth-google-oauth2', '~> 0.4.1'
gem 'omniauth-kerberos', '~> 0.3.0', group: :kerberos
gem 'omniauth-oauth2-generic', '~> 0.2.2'
gem 'omniauth-saml', '~> 1.7.0'
gem 'omniauth-shibboleth', '~> 1.2.0'
gem 'omniauth-twitter', '~> 1.2.0'
gem 'omniauth_crowd', '~> 2.2.0'
gem 'omniauth-authentiq', '~> 0.3.0'
gem 'rack-oauth2', '~> 1.2.1'
gem 'jwt', '~> 1.5.6'

# Spam and anti-bot protection
gem 'recaptcha', '~> 3.0', require: 'recaptcha/rails'
gem 'akismet', '~> 2.0'

# Two-factor authentication
gem 'devise-two-factor', '~> 3.0.0'
gem 'rqrcode-rails3', '~> 0.1.7'
gem 'attr_encrypted', '~> 3.0.0'
gem 'u2f', '~> 0.2.1'

# GitLab Pages
gem 'validates_hostname', '~> 1.0.6'

# Browser detection
gem 'browser', '~> 2.2'

# LDAP Auth
# GitLab fork with several improvements to original library. For full list of changes
# see https://github.com/intridea/omniauth-ldap/compare/master...gitlabhq:master
gem 'gitlab_omniauth-ldap', '~> 1.2.1', require: 'omniauth-ldap'

# Git Wiki
# Required manually in config/initializers/gollum.rb to control load order
gem 'gollum-lib', '~> 4.2', require: false
gem 'gollum-rugged_adapter', '~> 0.4.4', require: false

# Language detection
gem 'github-linguist', '~> 4.7.0', require: 'linguist'

# API
gem 'grape', '~> 0.19.0'
gem 'grape-entity', '~> 0.6.0'
gem 'rack-cors', '~> 0.4.0', require: 'rack/cors'

# Disable strong_params so that Mash does not respond to :permitted?
gem 'hashie-forbidden_attributes'

# Pagination
gem 'kaminari', '~> 0.17.0'

# HAML
gem 'hamlit', '~> 2.6.1'

# Files attachments
gem 'carrierwave', '~> 1.1'

# Drag and Drop UI
gem 'dropzonejs-rails', '~> 0.7.1'

# for backups
gem 'fog-aws', '~> 0.9'
gem 'fog-core', '~> 1.44'
gem 'fog-google', '~> 0.5'
gem 'fog-local', '~> 0.3'
gem 'fog-openstack', '~> 0.1'
gem 'fog-rackspace', '~> 0.1.1'
gem 'fog-aliyun', '~> 0.1.0'

# for Google storage
gem 'google-api-client', '~> 0.8.6'

# for aws storage
gem 'unf', '~> 0.1.4'

# Seed data
gem 'seed-fu', '~> 2.3.5'

# Markdown and HTML processing
gem 'html-pipeline', '~> 1.11.0'
gem 'deckar01-task_list', '2.0.0'
gem 'gitlab-markup', '~> 1.5.1'
gem 'redcarpet', '~> 3.4'
gem 'RedCloth', '~> 4.3.2'
gem 'rdoc', '~> 4.2'
gem 'org-ruby', '~> 0.9.12'
gem 'creole', '~> 0.5.0'
gem 'wikicloth', '0.8.1'
gem 'asciidoctor', '~> 1.5.2'
gem 'asciidoctor-plantuml', '0.0.7'
gem 'rouge', '~> 2.0'
gem 'truncato', '~> 0.7.8'
gem 'bootstrap_form', '~> 2.7.0'

# See https://groups.google.com/forum/#!topic/ruby-security-ann/aSbgDiwb24s
# and https://groups.google.com/forum/#!topic/ruby-security-ann/Dy7YiKb_pMM
gem 'nokogiri', '~> 1.6.7', '>= 1.6.7.2'

# Diffs
gem 'diffy', '~> 3.1.0'

# Application server
group :unicorn do
  gem 'unicorn', '~> 5.1.0'
  gem 'unicorn-worker-killer', '~> 0.4.4'
end

# State machine
gem 'state_machines-activerecord', '~> 0.4.0'
# Run events after state machine commits
gem 'after_commit_queue', '~> 1.3.0'

# Issue tags
gem 'acts-as-taggable-on', '~> 4.0'

# Background jobs
gem 'sidekiq', '~> 5.0'
gem 'sidekiq-cron', '~> 0.6.0'
gem 'redis-namespace', '~> 1.5.2'
gem 'sidekiq-limit_fetch', '~> 3.4'

# Cron Parser
gem 'rufus-scheduler', '~> 3.4'

# HTTP requests
gem 'httparty', '~> 0.13.3'

# Colored output to console
gem 'rainbow', '~> 2.2'

# GitLab settings
gem 'settingslogic', '~> 2.0.9'

# Misc

gem 'version_sorter', '~> 2.1.0'

# Cache
gem 'redis-rails', '~> 5.0.1'

# Redis
gem 'redis', '~> 3.2'
gem 'connection_pool', '~> 2.0'

# HipChat integration
gem 'hipchat', '~> 1.5.0'

# JIRA integration
gem 'jira-ruby', '~> 1.1.2'

# Flowdock integration
gem 'gitlab-flowdock-git-hook', '~> 1.0.1'

# Gemnasium integration
gem 'gemnasium-gitlab-service', '~> 0.2'

# Slack integration
gem 'slack-notifier', '~> 1.5.1'

# Asana integration
gem 'asana', '~> 0.6.0'

# FogBugz integration
gem 'ruby-fogbugz', '~> 0.2.1'

# Kubernetes integration
gem 'kubeclient', '~> 2.2.0'

# d3
gem 'd3_rails', '~> 3.5.0'

# underscore-rails
gem 'underscore-rails', '~> 1.8.0'

# Sanitize user input
gem 'sanitize', '~> 2.0'
gem 'babosa', '~> 1.0.2'

# Sanitizes SVG input
gem 'loofah', '~> 2.0.3'

# Working with license
gem 'licensee', '~> 8.7.0'

# Protect against bruteforcing
gem 'rack-attack', '~> 4.4.1'

# Ace editor
gem 'ace-rails-ap', '~> 4.1.0'

# Keyboard shortcuts
gem 'mousetrap-rails', '~> 1.4.6'

# Detect and convert string character encoding
gem 'charlock_holmes', '~> 0.7.3'

# Faster JSON
gem 'oj', '~> 2.17.4'

# Parse time & duration
gem 'chronic', '~> 0.10.2'
gem 'chronic_duration', '~> 0.10.6'

gem 'webpack-rails', '~> 0.9.10'
gem 'rack-proxy', '~> 0.6.0'

gem 'sass-rails', '~> 5.0.6'
gem 'coffee-rails', '~> 4.1.0'
gem 'uglifier', '~> 2.7.2'

gem 'addressable', '~> 2.3.8'
gem 'bootstrap-sass', '~> 3.3.0'
gem 'font-awesome-rails', '~> 4.7'
gem 'gemojione', '~> 3.0'
gem 'gon', '~> 6.1.0'
gem 'jquery-atwho-rails', '~> 1.3.2'
gem 'jquery-rails', '~> 4.1.0'
gem 'request_store', '~> 1.3'
gem 'select2-rails', '~> 3.5.9'
gem 'virtus', '~> 1.0.1'
gem 'net-ssh', '~> 3.0.1'
gem 'base32', '~> 0.3.0'

# Sentry integration
gem 'sentry-raven', '~> 2.5.3'

gem 'premailer-rails', '~> 1.9.7'

# I18n
gem 'ruby_parser', '~> 3.8', require: false
gem 'rails-i18n', '~> 4.0.9'
gem 'gettext_i18n_rails', '~> 1.8.0'
gem 'gettext_i18n_rails_js', '~> 1.2.0'
gem 'gettext', '~> 3.2.2', require: false, group: :development

# Perf bar
gem 'peek', '~> 1.0.1'
gem 'peek-gc', '~> 0.0.2'
gem 'peek-host', '~> 1.0.0'
gem 'peek-mysql2', '~> 1.1.0', group: :mysql
gem 'peek-performance_bar', '~> 1.2.1'
gem 'peek-pg', '~> 1.3.0', group: :postgres
gem 'peek-rblineprof', '~> 0.2.0'
gem 'peek-redis', '~> 1.2.0'
gem 'peek-sidekiq', '~> 1.0.3'

# Metrics
group :metrics do
  gem 'allocations', '~> 1.0', require: false, platform: :mri
  gem 'method_source', '~> 0.8', require: false
  gem 'influxdb', '~> 0.2', require: false

  # Prometheus
  gem 'prometheus-client-mmap', '~>0.7.0.beta5'
  gem 'raindrops', '~> 0.18'
end

group :development do
  gem 'foreman', '~> 0.78.0'
  gem 'brakeman', '~> 3.6.0', require: false

  gem 'letter_opener_web', '~> 1.3.0'
  gem 'rblineprof', '~> 0.3.6', platform: :mri, require: false

  # Better errors handler
  gem 'better_errors', '~> 2.1.0'
  gem 'binding_of_caller', '~> 0.7.2'

  # thin instead webrick
  gem 'thin', '~> 1.7.0'
end

group :development, :test do
  gem 'bullet', '~> 5.5.0', require: !!ENV['ENABLE_BULLET']
  gem 'pry-byebug', '~> 3.4.1', platform: :mri
  gem 'pry-rails', '~> 0.3.4'

  gem 'awesome_print', '~> 1.2.0', require: false
  gem 'fuubar', '~> 2.0.0'

  gem 'database_cleaner', '~> 1.5.0'
  gem 'factory_girl_rails', '~> 4.7.0'
  gem 'rspec-rails', '~> 3.5.0'
  gem 'rspec-retry', '~> 0.4.5'
  gem 'spinach-rails', '~> 0.2.1'
  gem 'spinach-rerun-reporter', '~> 0.0.2'
  gem 'rspec_profiling', '~> 0.0.5'
  gem 'rspec-set', '~> 0.1.3'

  # Prevent occasions where minitest is not bundled in packaged versions of ruby (see #3826)
  gem 'minitest', '~> 5.7.0'

  # Generate Fake data
  gem 'ffaker', '~> 2.4'

  gem 'capybara', '~> 2.6.2'
  gem 'capybara-screenshot', '~> 1.0.0'
  gem 'poltergeist', '~> 1.9.0'

  gem 'spring', '~> 2.0.0'
  gem 'spring-commands-rspec', '~> 1.0.4'
  gem 'spring-commands-spinach', '~> 1.1.0'

  gem 'rubocop', '~> 0.47.1', require: false
  gem 'rubocop-rspec', '~> 1.15.0', require: false
  gem 'scss_lint', '~> 0.47.0', require: false
  gem 'haml_lint', '~> 0.21.0', require: false
  gem 'simplecov', '~> 0.14.0', require: false
  gem 'flay', '~> 2.8.0', require: false
  gem 'bundler-audit', '~> 0.5.0', require: false

  gem 'benchmark-ips', '~> 2.3.0', require: false

  gem 'license_finder', '~> 2.1.0', require: false
  gem 'knapsack', '~> 1.14.0'

  gem 'activerecord_sane_schema_dumper', '0.2'

  gem 'stackprof', '~> 0.2.10'
end

group :test do
  gem 'shoulda-matchers', '~> 2.8.0', require: false
  gem 'email_spec', '~> 1.6.0'
  gem 'json-schema', '~> 2.6.2'
  gem 'webmock', '~> 2.3.2'
  gem 'test_after_commit', '~> 1.1'
  gem 'sham_rack', '~> 1.3.6'
  gem 'timecop', '~> 0.8.0'
  gem 'concurrent-ruby', '~> 1.0.5'
end

gem 'octokit', '~> 4.6.2'

gem 'mail_room', '~> 0.9.1'

gem 'email_reply_trimmer', '~> 0.1'
gem 'html2text'

gem 'ruby-prof', '~> 0.16.2'

# OAuth
gem 'oauth2', '~> 1.4'

# Soft deletion
gem 'paranoia', '~> 2.3.1'

# Health check
gem 'health_check', '~> 2.6.0'

# System information
gem 'vmstat', '~> 2.3.0'
gem 'sys-filesystem', '~> 1.1.6'

# Gitaly GRPC client
gem 'gitaly', '~> 0.14.0'

gem 'toml-rb', '~> 0.3.15', require: false

# Feature toggles
gem 'flipper', '~> 0.10.2'
gem 'flipper-active_record', '~> 0.10.2'
