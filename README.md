# gSchool Blog


## Getting Started

* Fork this repository
* Clone the repository
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