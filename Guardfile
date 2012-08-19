guard 'rspec', :version => 2 do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})     { "spec" }
  watch('spec/spec_helper.rb')  { "spec" }

  # Rails example
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^app/(.+)\.rb$})                           { "spec" }
  watch(%r{^app/(.*)(\.erb|\.haml)$})                 { "spec" }
  watch(%r{^lib/(.+)\.rb$})                           { "spec" }
  watch(%r{^app/controllers/(.+)_(controller)\.rb$})  { "spec" }
  watch(%r{^spec/support/(.+)\.rb$})                  { "spec" }
  watch('spec/spec_helper.rb')                        { "spec" }
  watch('config/routes.rb')                           { "spec" }
  watch('app/controllers/application_controller.rb')  { "spec" }
  # Capybara request specs
  watch(%r{^app/views/(.+)/.*\.(erb|haml)$})          { "spec" }
end
