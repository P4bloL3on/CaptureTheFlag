# Rickdiculously Easy CTF
### Este repo pretende recoger mi walkthrough por la maquina [Rickdiculously Easy 1](https://www.vulnhub.com/entry/rickdiculouslyeasy-1,207/).

## Flags:
| Flag Text | Points | Comments |
| --------- |:------:|----------|
| There is no zeus, in your face! | 10 | Visitando _http://machine-ip:9090_
| Whoa this is unexpected | 10 | Visitando _ftp://machine-ip_
| Yeah d- just don't do it. | 10 | Visitando _http://machine-ip/passwords/password.html_ (path discovered using nikto)
| Get off the high road Summer! | 10 | conexión ssh "Summer" password "winter".
| TheyFoundMyBackDoorMorty | 10 | 
| Flip the pickle Morty! | 10 | Netcat a la _machine-ip_ puerto 60000 
| 131333 | 20 | Argumento del binario "safe".
| And Awwwaaaaayyyy we Go! | 20 | Ejecutando el binario "safe" con 131333 cmd arg
| Ionic Defibrillator | 30 | Logueandonos como RickSanchez y ejecutando "sudo -i" (RickSanchez estaba en sudoers)
