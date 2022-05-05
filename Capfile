require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rails'
require 'capistrano/bundler'
require 'capistrano/rbenv'

require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git

require 'capistrano/puma'
install_plugin Capistrano::Puma

# Depending on your server, you may need a different plugin
# For a Digital Ocean deploy, 'Daemon' will work
# Documentation: https://github.com/seuros/capistrano-puma
# From the documentation: "If you using puma daemonized (not supported in Puma 5+)""
# install_plugin Capistrano::Puma::Daemon

# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }

# # Load DSL and set up stages
# require "capistrano/setup"
# require "capistrano/deploy"
# require "capistrano/bundler"
# require "capistrano/rails"
# require "capistrano/rbenv"

# require "capistrano/scm/git"
# install_plugin Capistrano::SCM::Git

# require "capistrano/puma"
# install_plugin Capistrano::Puma

# # Include default deployment tasks
# # require "capistrano/deploy"

# # Load the SCM plugin appropriate to your project:
# #
# # require "capistrano/scm/hg"
# # install_plugin Capistrano::SCM::Hg
# # or
# # require "capistrano/scm/svn"
# # install_plugin Capistrano::SCM::Svn
# # or
# # require "capistrano/scm/git"
# # install_plugin Capistrano::SCM::Git

# # Include tasks from other gems included in your Gemfile
# #
# # For documentation on these, see for example:
# #
# #   https://github.com/capistrano/rvm
# #   https://github.com/capistrano/rbenv
# #   https://github.com/capistrano/chruby
# #   https://github.com/capistrano/bundler
# #   https://github.com/capistrano/rails
# #   https://github.com/capistrano/passenger
# #
# # require "capistrano/rvm"
# # require "capistrano/rbenv"
# # require "capistrano/chruby"
# # require "capistrano/bundler"
# # require "capistrano/rails"
# # require "capistrano/rails/migrations"
# # require "capistrano/puma"
# #install_plugin Capistrano::Puma::Daemon
# set :rbenv_ruby, '3.1.2'

# # Load custom tasks from `lib/capistrano/tasks` if you have any defined
# Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
