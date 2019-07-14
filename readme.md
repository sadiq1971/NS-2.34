Step by step installation of ns-2.34 on ubuntu

* Install the basic packages required to install the ns2

`sudo apt-get update`
`sudo apt-get install build-essential autoconf automake libxmu-dev`


* clone the repository or download it.

`git clone https://github.com/sadiq1971/NS-2.34.git`


* To install ns2  go to ns-allinone-2.34 directory and run ./install on terminal

`cd ns-allinone-2.34/`
`./install`

it will take 20- 30 min or may be more time to install


* After this go to base directory and following command

`cd ns-2.34`
`sudo make install`


* Run ns

`ns`

It will show % sign
type exit to exit

Thats all.


Every time you modify the code you have to run two command from ns-2.34 directory to modify the executable `ns`

`make`
`sudo make install`
