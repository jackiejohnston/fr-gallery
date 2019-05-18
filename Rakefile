require 'rake'

desc "Run on localhost with auto-refreshing."
task :liveserve do
  sh "JEKYLL_ENV=testing jekyll serve --livereload --trace --baseurl ''"
end

desc "Run on localhost without auto-refreshing."
task :serve do
  sh "JEKYLL_ENV=testing jekyll serve --trace --baseurl ''"
end

desc "Deploy to GitHub Pages."
task :ghpages do
  sh "git subtree push --prefix _site origin gh-pages"
end