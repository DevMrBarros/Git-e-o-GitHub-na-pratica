# Git e o GitHub na prática
Git e o GitHub na prática:

Este guia fornece uma visão geral dos passos básicos para começar a usar o Git e o GitHub. O Git é um sistema de controle de versão amplamente utilizado, enquanto o GitHub é uma plataforma on-line que hospeda repositórios Git e oferece recursos adicionais de colaboração.

# Passo 1: Instalação

1.	Baixe e instale o Git em https://git-scm.com/downloads de acordo com o seu sistema operacional.
2.	Siga as instruções de instalação padrão para concluir a instalação.

# Passo 2: Configuração

1.	Abra o terminal (no Windows, use o Git Bash que foi instalado junto com o Git) ou use o prompt de comando do seu sistema operacional.
2.	Configure seu nome de usuário global usando o seguinte comando:
- git config --global user.name "Seu Nome"

3.	Configure seu email global usando o seguinte comando:  
- git config --global user.email "seu-email@example.com"

Essas informações serão anexadas aos commits que você fizer.

# Passo 3: Criação de um repositório local

1.	Navegue até o diretório onde deseja iniciar um novo repositório.
2.	Inicie um novo repositório Git usando o seguinte comando:
- git init

3.	Agora você tem um repositório Git vazio pronto para uso.

# Passo 4: Adicionar e confirmar alterações

1.	Adicione arquivos ao seu repositório usando o seguinte comando:	
- git add nome_do_arquivo

Você também pode usar git add . para adicionar todos os arquivos modificados.

2.	Confirme as alterações no repositório usando o seguinte comando:
- git commit -m "Mensagem de confirmação"

Forneça uma mensagem clara e descritiva que resuma as alterações feitas.

# Passo 5: Criação de um repositório remoto

1.	Crie um novo repositório em sua conta do GitHub.
2.	Copie a URL do repositório recém-criado.

# Passo 6: Conectar o repositório local ao repositório remoto

1.	No terminal, adicione o URL do repositório remoto usando o seguinte comando:
- git remote add origin URL_do_repositório_remoto

Substitua URL_do_repositório_remoto pela URL que você copiou anteriormente.

2.	Envie suas alterações locais para o repositório remoto usando o seguinte comando:
- git push -u origin master

# Passo 7: Trabalhando com branchs

1.	Para criar uma nova branch, use o seguinte comando:
- git branch nome_da_branch
2.	Mude para a nova branch usando o seguinte comando:
- git checkout nome_da_branch
3.	Faça suas alterações na nova branch e confirme-as como antes.
4.	Envie a nova branch para o repositório remoto usando o seguinte comando:
- git push origin nome_da_branch

Agora seu repositório local está conectado ao repositório remoto e suas alterações foram enviadas.

# Passo 8: Atualizando seu repositório local

1.	Baixe as alterações mais recentes do repositório remoto para o seu repositório local usando o seguinte comando:
- git pull origin master

Isso sincronizará seu repositório local com o estado atual do repositório remoto.
Essas são apenas algumas das funcionalidades básicas do Git e GitHub. Existem muitos outros recursos avançados, como mesclar branchs, resolver conflitos e colaborar com outros desenvolvedores. Recomendo explorar mais sobre essas ferramentas para aproveitar ao máximo sua capacidade de gerenciamento de código-fonte e colaboração.
