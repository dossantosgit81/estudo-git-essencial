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

	//Verifica o estado atual dos commits e arquivos que ainda não são "observados" pelo git
		git status
	
	//Adiciona os arquivos para ser "observados" pelo git

		git add nomeDoArquivo.txt
		
		//Adiciona todos os arquivos para ser "observados" pelo git

			git add . 

		//Mostra o histórico de commits

			git log

			//Aqui mostra apenas os setes primeiros números que são necessarios para identificação do commit

				git log  --oneline

			//Nodo de commits

			git log --graph

			//Nodo de commits simplificado

			git log --oneline --graph
	
			//Adicione o os arquivos para serem "observados(Container)" pelo git e adiciona ao repositorio, ou seja onde ele de fato será gerenciado pelo git

			git commit -am "Creation file teste"

			//Rastreando commit de uma versão anterior, para uma nova branch

			git checkout -b 3421fd1


			//Removendo comitt

				//Deleta o commit e todas as modificações
			git reset --hard "hash do commit"

				//Desfaz o commit, e volta para a versão do commit do hash
			git reset --soft "hash do commit"

			//Criando uma branch
			//A branch teste, herda todos os commits da branch master

			git checkout -b teste




