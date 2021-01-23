# aptrepo-amd64

Howto: 
1. wget -qO - https://legendary-cookie.github.io/aptrepo-amd64/public.key | sudo apt-key add -
2. sudo echo "deb [trusted=true] http://legendary-cookie.github.io/aptrepo-amd64 stable main" >> /etc/apt/sources.list
