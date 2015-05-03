# -*- ruby -*-

desc "Upload"
task :upload do
  sh("jekyll", "build")
  sh("rsync",
     "-avz",
     "_site/",
     "taiyaki@taiyaki.ru:public_html/")
end
