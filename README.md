# audiobook

[![Join the chat at https://gitter.im/audiobook/Lobby](https://badges.gitter.im/audiobook/Lobby.svg)](https://gitter.im/audiobook/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## setup via vagrant

To start a project, run the following commands:

    vagrant up
    vagrant ssh
    cd /home/vagrant/audiobook
    python3 manage.py createsuperuser
    python3 manage.py runserver 0.0.0.0:8000