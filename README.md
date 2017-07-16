# o0TT0o.github.io
***


# Dependents:
- [jekyll/jekyll-paginate](https://github.com/jekyll/jekyll-paginate)
- [BlackrockDigital/startbootstrap-clean-blog-jekyll](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll)

***

# Techs:

## 1、Install Ruby & Jekyll(Windows - The Tough Way)

### Reference
- [Run Jekyll on Windows](http://jekyll-windows.juthilo.com/5-running-jekyll/)
- [jekyll本地环境搭建(Windows)](http://www.cnblogs.com/yevon/p/3308158.html)

### Experience
- Ruby Install
> 1、Ruby version **MUST** >= 2.1

> 2、A Common **ssl-issue** Problem , see:

> 	http://guides.rubygems.org/ssl-certificate-update/#manual-solution-to-ssl-issue

> 3、Using Mac OS or Linux System can make the process **EASIER**... : )

### Command
- Install Ruby & Jekyll
> Get Ruby for Windows
> Get the Ruby DevKit
```bash
> cd C:\RubyDevKit
> ruby dk.rb init
> ruby dk.rb install
> gem install jekyll
> gem install rouge
> highlighter: rouge
> gem install wdm
> jekyll serve
```

### Congurations
- If U see this, U are **SUCCESS** 
```output
> Configuration file: [your project path]/_config.yml
            Source: [your project path]
       Destination: [your project path]/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.209 seconds.
 Auto-regeneration: enabled for '[your project path]'
    Server address: http://127.0.0.1:4000/[your project name]/
  Server running... press ctrl-c to stop.
```

##  2、Add Jekyll Plugins

### Reference
- [下载了一个jekyll主题，但是在输入jekyll serve运行时，却报错？](https://www.zhihu.com/question/41617679)
- [Jekyll Doc - Plugins](http://jekyll.com.cn/docs/plugins/)

### Experience
- Jekyll Plugin Install
> 1、 Just Use **gem** add *bundle*、 *jekyll-paginate*、 *jekyll-feed* 

### Command
- Add Plugins ( for "Clean Blog Theme" )
```bash
> gem install bundle
> gem install jekyll-paginate
> gem install jekyll-feed
```

### Congurations
- If U see this, U are **SUCCESS** 
```output
> 1 gem installed
```

##  3、Startup Jekyll Server

### Command
- Startup Jekyll Server
```bash
> jekyll serve
```

### Congurations
- If U see this, U are **SUCCESS** 
```output
> Configuration file: [your project path]/_config.yml
            Source: [your project path]
       Destination: [your project path]/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.209 seconds.
 Auto-regeneration: enabled for '[your project path]'
    Server address: http://127.0.0.1:4000/[your project name]/
  Server running... press ctrl-c to stop.
```
***

