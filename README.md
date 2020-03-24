# subito-it-searcher

BeautifulSoup toy example running queries and scraping results on a popular italian ad website

forked from morrolinux -> https://www.youtube.com/watch?v=qyZ-E-6TPD8
updated in order to work with new subito.it website (03/2020)


install and configure telegram:

--> sudo pip3 install telegram_send 

--> telegram-send --configure


example usage:

--> sudo python3 subito-searcher.py --help

--> sudo python3 subito-searcher.py --name="macbookpro" --url="https://www.subito.it/annunci-italia/vendita/usato/?q=macbookpro&from=top-bar"



to run continuously use subito-searcher-daemon.sh