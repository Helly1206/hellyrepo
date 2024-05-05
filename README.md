Helly1206 apt repository<br>
===================<br>

Execute the following commands to add the repository to the list and automatically update:<br>

Add key:<br>
wget -qO - https://Helly1206.github.io/hellyrepo/public_key | sudo apt-key add -<br>

Add repository to the list:<br>
For debian bookworm, but python packages will also work on earlier versions<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo_debian.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>

For ubuntu 24.04 noble numbat, but python packages will also work on earlier versions<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo_ubuntu.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>

In case of expired key:<br>
sudo apt-key del BAD95BBE342B55E5<br>
wget -qO - https://Helly1206.github.io/hellyrepo/public_key | sudo apt-key add -<br>

Older distros:<br>
debian buster<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo_debian_buster.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>
ubuntu 22.04 jammy jellyfish<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo_ubuntu_jammy.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>
ubuntu 20.04 focal fossa<br>
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo_ubuntu_focal.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>
