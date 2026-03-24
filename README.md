# perspectiva-dados
Repositório para Aulas e Labs de PCD, para acompanharmos a evolução na programação em python, linux e git.

17/03 - Aprendemos a colocar um arquivo da nuvem para a máquina (git clone),
 alterar o arquivo na máquina e verificar as diferenças (git status e git diff),
 e adicionar as alterações na nuvem novamente (git add, git commit, git push).
 
 
20/03 - Aprendemos a entrar nops arquivos pelo terminal "ls" ve quais são as pastas disponiveis e o "cd (nome da pasta)"
adiciona a pasta no terminal para modificação.
  Também iremos usar a apartir de agora, um git add "arquivo" e não o ".", para conseguirmos alterar as
  coisas em tempos diferentes.
  O "git restore --stage (arquivo)" retira algum documento do "add".
  O "git restore" retira todas as alteraçõpes feitas no arquivo local mesmo.
  git log também, mas nao sei oq faz.
  
  
  24/03 - instalando UV que é um gerenciador de pacotes do Python. Usamos o UV init para 
  iniciar o projeto e 'cat' para imprimir oq a pasta está escrito.
  'uv add' instala os pacotes do python.
  Da proxima vez usar somente uv sinc em vez de uv init.
  Como iniciar o jupyter no google. Vamos usar uv run jupyter notebook para programar localmente.
  
  Para ignorar alguns arquivos no na pasta nossa (como versoes de python e tudo mais), 
  vamos colocar no terminal "touch .gitignore" e colocar os nomes do arquivos dentro desse txt
  para ignorar eles no status.
  