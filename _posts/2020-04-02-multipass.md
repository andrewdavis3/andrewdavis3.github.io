# The mini-cloud for your workstation

Multipass - a mini-cloud on your workstation(https://multipass.run/). 
As tools like docker have helped with a temporary operating system enviroment. Which has aided
in getting tools in an enviroment working in symbosis. Sometimes it's nice to have an ubuntu
operating system already fire up to test out new tool. This is where multipass may come in handy. 
For my mac, I already had Virtualbox installed, I then installed multipass via brew `brew cask install multipass`. 
I then had to run `sudo multipass set local.driver=virtualbox` to get multipass to start up. 
If you want to expand CPU and RAM run `multipass launch --name primary --cpus 4 --mem 10G`.
