Aqui tem os comandos e intruções do projeto junto com anotações e explicações de suas funcionalidades.



///Configurações gerais///
git init <!-- Cria os arquivos necessário na pasta do repositório do computador -->
git remote add origin 'https://github.com/usuario/nomedorepositorio.git' <!-- Adiciona o endereço do repositório na nuvem -->
<!-- remote = conexão entre repositório local com a nuvem -->
<!-- origin = nome do repositório do github -->


///Comandos para manipular os arquivos/// 
git add (nome do arquivo(usando o '.' ele seleciona todos os arquivos)) <!-- Adiciona um arquivo para seleção -->
git commit -m "'comentário'" <!-- Entrega o/s arquivo/s  -->
git push -u origin main <!-- Manda os arquivos pra nuvem ('-u' só é necessário na primeira vez)-->
git status <!-- Mostra informações -->

<!--  -->

///Comandos diversos///
git branch -m "'nome'" <!-- Renomeia o nome da branch (no caso estava como master mas o github usa main) -->
rm -f ./.git/index.lock <!-- Resolveu os erros de "Unable to create..." e " Another git process seems to be running..." -->
git config --global user.name "Username" <!-- Usado para configurar o nome de usuário -->
git config --global user.email "email@example.com" <!-- Usado para configurar o email do usuário -->



///Nomenclaturas///
<!-- remote = conexão entre repositório local com a nuvem -->
<!-- origin = nome do repositório do github -->
