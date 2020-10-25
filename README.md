Helly1206 apt repository<br>
===================<br>

Execute the following commands to add the repository to the list and automatically update:<br>

Add key:<br>
wget -qO - https://Helly1206.github.io/hellyrepo/public_key | sudo apt-key add -<br>

Add repository to the list:<br>
For debian buster, but python packages will also work on earlier versions<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo.list | sudo tee /etc/apt/sources.list.d/hellyrepo_debian.list<br>

For ubuntu 20.04 focal fossa, but python packages will also work on earlier versions<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo.list | sudo tee /etc/apt/sources.list.d/hellyrepo_ubuntu.list<br>
