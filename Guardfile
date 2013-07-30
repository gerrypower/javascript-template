guard 'livereload' do
  watch(%r{.+\.(css|html)})
  watch(%r{(js|spec)/.+\.js})
end

guard 'markdown', :convert_on_start => true do
  watch ('TODO.md') { "./TODO.md|./TODO.html" }
  watch ('README.md') { "./README.md|./README.html" }
end


guard 'coffeescript', :input => 'js'
guard 'coffeescript', :input => 'spec'
