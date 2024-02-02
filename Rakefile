require 'html-proofer'

task :test do
  sh "web của diem ne"
  options = { :assume_extension => true, :only_4xx => true, :allow_hash_href => true}
  HTMLProofer.check_directory("./_site", options).run
end
