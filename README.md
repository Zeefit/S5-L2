sudo nmap -O 192.168.1.130: Esegue una scansione per determinare il sistema operativo dell'host con IP 192.168.1.130,-O attiva il rilevamento del sistema operativo, utilizzando le risposte ai pacchetti inviati da Nmap per cercare di identificare quale OS è in esecuzione sull'host

sudo nmap -sS 192.168.1.130: Esegue una scansione SYN stealth sull'host specificato,Questo metodo invia pacchetti SYN e verifica se la porta risponde, determinando se è aperta, chiusa o filtrata. La scansione stealth è spesso usata per evitare il rilevamento

sudo nmap -sV 192.168.1.130: Rileva le versioni dei servizi in esecuzione sulle porte aperte,-sV, tenta di identificare non solo quali porte sono aperte, ma anche le versioni dei software o dei servizi attivi su tali porte
