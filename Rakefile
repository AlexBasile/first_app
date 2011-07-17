# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'rake'
# If you named your application something other than SampleApp, change that below
module::FirstApp
    class Application
        include Rake::DSL
    end
end

module::RakeFileUtils
    extend Rake::FileUtilsExt
end

FirstApp::Application.load_tasks
