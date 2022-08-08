Add this to the .zshrc file:

alias get-db='git clone --depth=1 --branch=master https://github.com/CAREEMER/docker-compose-database.git SOMEUNIQUEDIRTHATNOONEWILLEVERCREATE228 && cp SOMEUNIQUEDIRTHATNOONEWILLEVERCREATE228/docker-compose.yml docker-compose.yml && rm -rf SOMEUNIQUEDIRTHATNOONEWILLEVERCREATE228'
