# heroku-buildpack-timings

Use [multiple buildpacks on your app](https://github.com/ddollar/heroku-buildpack-multi) and get line-by-line timings in the left margin, like this:

```
2013-10-30T22:39:01+0000  -----> Grails 2.2.0 app detected
2013-10-30T22:39:04+0000  -----> Installing OpenJDK 1.6...done
2013-10-30T22:39:05+0000  
2013-10-30T22:39:05+0000  | Loading Grails 2.2.0
...
```

## Usage

    $ heroku config:add BUILDPACK_URL=https://github.com/ryanbrainard/heroku-buildpack-timings.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git
