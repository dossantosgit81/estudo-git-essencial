Introdução: Comandos básicos do terminal
	//Mostra o diretorio atual
		pwd
	//Volta para o disco /c
		cd /c
	//Cria uma pasta
		mkdir nomeDaPasta
	//Cria um arquivo
		touch exemplo.txt
		touch diretorioTeste/exemplo.txt
	//Lista as pastas e arquivos do diretorio atual
		ls
	//Lista diretorios ocultos
		ls -a

Estudo git: Introdução e comandos básicos
	//Define um usuario do git
		git config --global user.name "Nome do usauario da silva"
		git config -- global user.email "emailexample@gmail.com"
	
	//Inicia um repositorio vazio
		git init

	//Verifica o estado atual dos commits e arquivos que ainda não são gerenciados pelo git
		git status
	
	//Adiciona os arquivos para ser gerenciados pelo git
		git add nomeDoArquivo.txt
		
		//Adiciona todos os arquivos para ser gerenciados pelo git
			git add . 



