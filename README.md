Seafile init script
===================

This file is part of the guide [Deploying Seafile with nginx and MySQL on Debian Wheezy](https://github.com/hadret/Texts/blob/master/deploying_seafile_with_nginx_and_mysql_on_debian.md). Feel free to report [issues](https://github.com/hadret/Texts/issues) and/or [pull requests](https://github.com/hadret/Texts/pulls).

* * *

INSTALLATION
============

Fairly straight-forward. If you need latest available release, type:

    sudo wget https://github.com/hadret/Scripts/raw/master/seafile/seafile -O /etc/init.d/seafile
    sudo chmod +x /etc/init.d/seafile
    sudo update-rc.d seafile defaults 21

If you are aiming into some particular version, check out available [branches](https://github.com/hadret/Scripts/branches) and modify link accordingly. Here's an example for stable-1.7.0 branch:

    sudo wget https://github.com/hadret/Scripts/raw/stable-1.7.0/seafile/seafile -O /etc/init.d/seafile

* * *

AUTHORS
=======

* Filip "Hadret" Chabik <hadret@gmail.com>
* [itsme-](https://github.com/itsme-)

_(Remember to add yourself when pull requesting)._
