# gSchool Blog


## Getting Started

* Fork this repository in the github interface (top right)

* Clone the repository using the SSH url for your repo

```
git clone git@github.com:YOURNAME/gschool-blog.git
```

* Get into the project directory
 
```
cd gschool-blog
```

* Install all the required dependencies

```
$ bundle install
```

## Creating an Article

```
$ middleman article "Article Title"
```

## Viewing Your Work

```
$ middleman
```

## Publishing to Heroku

```
$ heroku create --stack cedar
$ git push heroku master
```
