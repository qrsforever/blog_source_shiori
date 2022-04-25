# shiori_blog_post
# shiori bookmarks archive files storage
# lidong:m8

# [submodule "archive/1970"]
# 	active = true
# 	url = git@git.zhlh6.cn:qrsforever/shiori_archive_1970.git
  
git submodule update --init --recursive
git submodule foreach --recursive git checkout master
git submodule foreach --recursive git pull
