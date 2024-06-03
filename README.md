# ls -l ~/.ssh
ssh-add ~/.ssh/id_ed25519
ssh-add -l
cat ~/.ssh/id_ed25519.pub
cd ~
mkdir repos
cd repos
git clone
cd github_pages_101 
ls
cd docs
ls
cat index.html
sudo apt install net-tools

ifconfig | grep -ioE  "inet(6?)\s[a-z0-9:.]*" | sed -e 's/$/<p>/'      > temp.html
cat temp.html | grep -viE "(127.0.0.1 |::1) "       > ipaddresses.html

echo $(date +"%d-%m-%Y %H:%M:%S %Z    %s") >>  ipaddresses.html
cat /etc/machine-id >>  ipaddresses.html
cat  ipaddresses.html 
