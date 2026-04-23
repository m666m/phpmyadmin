# phpmyadmin

Containerized running of PHPMYAdmin(quay.io/linuxserver.io/phpmyadmin).

Usage:

    $ git clone --depth=1 https://github.com/m666m/phpmyadmin

    $ cd phpmyadmin && mkdir config

    Modify compose.yaml, set your local port, default 8010.

    $ docker compose config
    
    $ docker compose up -d

Browser open <http://localhost:8010>.
