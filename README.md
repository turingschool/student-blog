# Turing Student Blog

1. Fork the repository to your own account and then clone it to your machine:

	```
	$ git clone git@github.com:YOURNAME/turing-blog.git
	```

1. Use bundler to install all of the dependencies

	```
	$ cd turing-blog
	$ bundle install
	```

1. Run the Middleman Blog

	```
	$ middleman
	```

1. Open the blog in your browser to make sure it works.  You can do this from a new terminal tab with:

	```
	$ open http://localhost:4567
	```

1. Check out the existing articles for an example of how to write a blog post. Make note that you can
add a tag to the article using the 'tag' setting at the top of an article. See http://middlemanapp.com/basics/blogging/#toc_1
for more information about adding dates and tags to each article.

1. Remove the existing articles

	```
	$ git rm source/2012-01-01-example-article.html.markdown
	$ git rm source/2013-01-23-introduction.html.markdown
	$ git commit -m "Removed old articles"
	```

1. Create your first article with some title:

	```
	$ middleman article "First Article"
	```

1. Add your content to the generated file.

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
