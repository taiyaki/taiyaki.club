# -*- ruby -*-

desc "Upload"
task :upload do
  sh("jekyll", "build")
  sh("rsync",
     "-avz",
     "_site/",
     "taiyaki@taiyaki.club:public_html/")
end
