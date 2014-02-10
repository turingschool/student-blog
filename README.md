# gSchool Blog

1. Fork the repository to your own account and then clone it to your machine:

	```
	$ git clone git@github.com:YOURNAME/gschool-blog.git
	```

1. Use bundler to install all of the dependencies

	```
	$ cd gschool-blog
	$ bundle install
	```

1. Run the Middleman Blog and visit in your browser to make sure it works

	```
	$ middleman
	$ open http://localhost:4567
	```

1. Remove the existing articles

	```
	$ git rm source/2012-01-01-example-article.html.markdown
	$ git rm source/2013-01-23-introduction.html.markdown
	$ git commit -m "Removed old articles"
	```

1. Create your first article

	```
	$ middleman article "gSchool - Week 0"
	```

1. Write an article with your recap/reflections of the first week.

1. Save the article

	```
	$ git add source
	$ git commit -m "Wrote First Article"
	```

1. Create the Heroku application and deploy your blog.

	```
	$ heroku create
	$ git push heroku master
	```

1. Push your changes back to Github for safe keeping

	```
	$ git push origin master
	```

1. (Optional) Rename the blog to something other than the default Heroku name. You can do this via the Heroku console after you log in.