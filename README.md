setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/kwong22/setup.git
chmod +x setup/setup.sh
./setup/setup.sh   
```

The setup script was adapted from the [Startup Engineering course](https://www.coursera.org/course/startup) to quickly setup a developer environment.
