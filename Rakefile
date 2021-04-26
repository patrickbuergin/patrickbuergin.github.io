require 'html-proofer'

task :test do
  sh "bundle exec jekyll build"
  HTMLProofer.check_directory("./_site", {
    :assume_extension => true,
    :enforce_https => true,
    :internal_domains => ["www.patrickbuergin.com"],
    :log_level => :info,
    :url_ignore => [
        /linkedin\.com\//,
        /twitter\.com\//,
        "#",
    ],
  }).run
end
