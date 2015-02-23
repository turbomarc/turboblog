# Based on [Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/)

## Getting Started

lessc --clean-css="--compatibility=ie8 --advanced" main.less ../css/main.min.css

uglifyjs main.js -o main-min.js

uglifyjs /home/doe/work/foo/src/js/file1.js \
/home/doe/work/foo/src/js/file2.js \
-o foo.min.js

grunt serve
