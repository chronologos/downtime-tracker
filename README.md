Combination of work from [here](https://gist.github.com/waleedahmad/326ec53f76646dccec299910a7fb4f2b) and [here](http://blog.scphillips.com/posts/2013/07/getting-a-python-script-to-run-in-the-background-as-a-service-on-boot/).

# Setup
0. Clone repo.
1. `sudo cp downtime.sh /etc/init.d`
2. `chmod 755 downtime.py`
3. `chmod 755 /etc/init.d/downtime.sh`
4. `sudo update-rc.d downtime.sh defaults`
5. `sudo /etc/init.d/downtime.sh start`
