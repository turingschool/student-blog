# gSchool Blog

```
$ git clone git@github.com:YOURNAME/gschool-blog.git
```

* Download all the project dependencies

```
$ cd gschool-blog
$ bundle install
```

* Run the Middleman Blog

```
$ middleman
```

* Visit the [blog](http://localhost:4567) in your browser

* Remove the existing articles

```
$ git rm source/2012-01-01-example-article.html.markdown
$ git rm source/2013-01-23-introduction.html.markdown
$ git commit -m "Removed old articles"
```

* Create your first article

```
$  middleman article "gSchool - Week 0"
```

* Write an article with your recap/reflections of the first week.

* Save the article

```
$ git add source
$ git commit -m "Wrote First Article"
```

* Create a Heroku Account
* Add your SSH key to your [Heroku account](https://dashboard.heroku.com/account)

* Install the heroku tools
* Create a heroku server

```
$ gem install heroku
$ heroku create --stack cedar
$ git push heroku master
```

* Push your changes back to Github

```
$ git push origin master
```