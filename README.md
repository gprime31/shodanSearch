# Shodan Search Script
Shodan script for easy search on Shodan.

First by first you need change API key, with your API key in code. 

Usage;

	python3 shodanScript.py -f dorkList.txt -o output.txt
	python3 shodanScript.py -k "net:'210.214.0.0/16'" -o output.txt
	python3 shodanScript.py -k "http.title:'ID_VC_Welcome' country:'EN'" -o output.txt
	
-h, --help  show this help message and exit

	-k  Just give keyword, Dork and it search for you
	-w  Just give wordlist, dork list
 	-o  Output!
 
If you dont redirect output, it will create the file in the current directory by default
