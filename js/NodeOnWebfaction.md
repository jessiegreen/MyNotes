# Set up notes

- export PATH=$PWD/bin:$PATH //adds app bin path to path temporarily fixing the /usr/bin/env: node: No such file or directory issue
- webfaction default has a cronjob to run hello-world.js so disable using crontab -e
- Install forever and start via npm start using: PORT=17345 forever start -c "npm start" /home/jessie/webapps/hobomarks_app/jessietest/
- install npm,express,and forever
