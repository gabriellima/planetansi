Planeta NSI
===========

Agregador dos feeds de blogs e githubs de membros, ex-membros e agregados diversos do Núcleo de Pesquisa em Sistemas de Informação (NSI) do Instituto Federal Fluminense (IFF), em Campos dos Goytacazes/RJ.

As URLs dos feeds (no momento) são:

http://planetansi.heroku.com/feeds (para os blogs)

http://planetansi.heroku.com/feeds/githubs (adivinhe)


Maiores informações sobre o NSI em http://nsi.iff.edu.br


Como instalar
-------------

Supondo que você tenha o Ruby instalado (com RVM ou não)::


    $ apt-get install openssl libreadline5 libreadline-dev zlib1g zlib1g-dev libssl-dev sqlite3 libsqlite3-0 libsqlite3-dev libxml2-dev libxslt1-dev libcurl3-dev

    $ gem install bundler --no-ri --no-rdoc

    $ bundle install



Como rodar testes
-----------------

Testes de aceitação::

    $ cucumber

Testes de unidade::

    $ rspec spec

