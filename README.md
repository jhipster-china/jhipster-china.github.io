This is the source of JHipster's public [Web site](http://www.jhipster.tech/).
=======
译注：[中文版网站](https://jhipster-china.github.io/)

This Web site is rendered with GitHub pages.

To run this locally

* [Fork this](https://github.com/jhipster/jhipster.github.io/fork) repo and clone to your file system
* [Install Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
* Run `bundle install` if you are running it for the first time.
** If you install it into a vendor directory, do not forget to add that directory in the exclusions into _config.yml!
* Run `bundle exec jekyll serve` in the cloned repo folder（译注：中文 windows cmd 还需要先执行：chcp 65001，来切换显示 UTF-8 字符）
* you will be able to access the site at http://localhost:4000

Or with Docker (recommended way on Windows)
* [Fork this](https://github.com/jhipster/jhipster.github.io/fork) repo and clone to your file system
* `docker container run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 4000:4000 jekyll/jekyll:pages bundle exec jekyll serve`
* or on Windows: `docker container run --rm --label=jekyll --volume=%CD%:/srv/jekyll -it -p 4000:4000 jekyll/jekyll:pages bundle exec jekyll serve`
* you will be able to access the site at http://localhost:4000
