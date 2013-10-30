# heroku-buildpack-timings

Use [multiple buildpacks on your app](https://github.com/ddollar/heroku-buildpack-multi) **+ get timings!**

## Usage

    $ heroku config:add BUILDPACK_URL=https://github.com/ryanbrainard/heroku-buildpack-timings.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git
