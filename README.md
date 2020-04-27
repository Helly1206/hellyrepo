Helly1206 apt repository<br>
===================<br>

Execute the following commands to add the repository to the list and automatically update:<br>

Add key:<br>
wget -qO - https://Helly1206.github.io/hellyrepo/public_key | sudo apt-key add -<br>

Add repository to the list:<br>
<<<<<<< HEAD
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>
=======
wget -qO - https://Helly1206.github.io/hellyrepo/hellyrepo.list | sudo tee /etc/apt/sources.list.d/hellyrepo.list<br>
>>>>>>> 14d9442d4c7a7475ed600dd39500a9851128f0ea
