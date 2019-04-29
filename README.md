# oauth
oauth authorization with ruby--------------------------------------------------------------------------------------
This file demonstrates how we can authorize a user into the github accounts by using oauth authorization framework.
oauth is a framework where users do not need to use their usernames and passwords to get services .
facebook is a typical example for oauth service.There are applications which ask you if they can get your facbook profile images etc.All you have to do is to agree and on the background the oauth authorization framework will function and you do not have to provide your facebook password and username.

Steps for testing

1.Create a project at Github develpoer oauth API and get the secreat key and the ID
2.Install the ruby from https://rubyinstaller.org/
3.Install the sinathra gem file from the command prompt
4.run the server.rb from the command prompt "ruby server.rb"
5.run the index.rb from you browser and the sinathra port is localhost:4567
6.you should get the token at localhost:4567/callback  which is located at the server.rb/callback
7.If you have been successfully authorized you will be redirected to basic.erb page


goodluck...............


