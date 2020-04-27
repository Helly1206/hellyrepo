Helly1206 apt repository
========= === ==========

Execute the following commands to add the repository to the list and automatically update:

Add key:
wget -qO - https://Helly1206.github.io/hellyrepo/public_key | sudo apt-key add -

Add repository to the list:
wget -q0 - https://Helly1206.github.io/hellyrepo/hellyrepo.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list