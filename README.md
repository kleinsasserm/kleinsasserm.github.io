My personal [Jekyll](https://jekyllrb.com/) page.

### Do not fork this repository!
### It is not useful for you because it cotains my page and not yours :) !

If you like to see how it is made, check [this link for the source](https://github.com/sharu725/online-cv).

### Build information for me

``` docker run -ti --rm --volume=$PWD:/srv/jekyll jekyll/jekyll:latest bash ```

``` docker run -ti --rm --name some-nginx -p 1234:80 -v $(pwd)/_site:/usr/share/nginx/html:ro nginx ```

