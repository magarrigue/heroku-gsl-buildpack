
## how to?

```sh
heroku run bash
GSL_VERSION=2.1 bash -c 'wget https://raw.githubusercontent.com/magarrigue/heroku-gsl-buildpack/base/bin/build.sh -O - | bash'

#when compilation finished, you'll be prompt a url, grab it then
wget -O gsl-2.1.tar.gz [url]/gsl-2.1.tar.gz

# You now have the compiled gsl
```

