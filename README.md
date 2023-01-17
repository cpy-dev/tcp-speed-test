# tcp-speed-test
Test private network speed on your local machine using TCP protocol

It is reqired Python 3 to run this script

## Usage

Always make sure to have execution permissions 


	$ sudo chmod +x ./tcp-speed-test


Then execute normally

	$ ./tcp-speed-test

If you want, you can build a compiled executable for your machine following the procedure:
	
	$ python3 -m pip install pyinstaller && pyinstaller --onefile tcp-speed-test && mv ./dist/tcp-speed-test . && rm -rf build dist tcp-speed-test.spec

## DISCLAIMER
This tool tests speed on local machine, so the resultant speed depends on both your network's and devices's capabilities
