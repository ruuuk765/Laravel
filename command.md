# Setup WSL2
wsl --set-default Ubuntu-20.04
wsl --set-version Ubuntu-20.04 2
wsl --list --verbose

# Clone laravel sail
wsl
sudo curl -s https://laravel.build/my-app| bash

# Tips
./vendor/bin/sail up -d
./vendor/bin/sail stop
./vendor/bin/sail down
./vendor/bin/sail down --rmi all --volumes --remove-orphans