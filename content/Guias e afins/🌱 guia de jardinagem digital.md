#### ... para webJardineiros de primeira viagem.

Um guia simples e mastigadinho pra quem quer começar um jardim digital e gostaria de um passo-a-passo que não vai sobrecarregar. Para iniciantes sem nenhuma experiência com código ou publicação online. Ah, e de graça, também. Escrito enquanto eu descobria um jeito fácil de montar o meu. :)

> ⚠️ **AVISO:** Esse é definitivamente um hobby para [[🤓 eu amo nerds]]! Eu tentei simplificar o processo ao máximo, mas ainda tem algumas partes que podem ser desafiadoras pra quem não tem muita familiaridade com tech-coisinhas e nerdolagens digitais. Não dá pra fazer milagre!
### Ferramentas de jardinagem
Todos os recursos que você vai precisar.
#### 1. Obsidian: sua terra fértil.
O Obsidian é um software livre para organizar anotações, pastas e arquivos de forma geral. Ele é tipo o primo comunista do Notion, mais ou menos. Você pode usar o Notion pra isso também, mas com o Obsidian você vai ter tudo salvo direto no seu computador, tudo seu mesmo, e você também pode usar ele pra armazenar coisas de forma privada, se quiser. Eu gosto muito do Obsidian. 
#### 2. GitHub + Quartz: entrada do jardim.
Aqui é o que vai te ajudar a receber visitantes e a mostrar sua plantação pra outras pessoas. São essas duas ferramentas que te permitem tornar o seu jardim público gratuitamente, colocando ele na web pra ser acessado através de um link. Você sempre decide o que você quer deixar público direto na organização do seu Obsidian, eu vou explicar isso também.
#### 3. Sementes de pensamento
As sementes que você vai plantar no seu jardim dependem de você. Cada pensamento, ideia, projeto, textinho etc. é uma sementinha que você pode continuar regando com o tempo e vendo ela crescer e se conectar com outras ideias pra gerar novos frutos. Mas eu vou te ajudar a começar com algumas ideias e recursos para os seus primeiros passos, caso você ainda não tenha decidido o que plantar primeiro.

### Mãos na terr@
Um passo-a-passo compreensível que vai te levar até a sua primeira sementinha.
#### 1. Prepare seu lote online com [Quartz](https://quartz.jzhao.xyz/) e o GitHub Pages
Não coça a cabeça não, é coisa simples. Dá pra fazer do jeito mais complexo, claro, se você for nerdola e gostar de futucar as coisas. Pra isso você vai precisar instalar alguns [pré-requisitos](https://quartz.jzhao.xyz/getting-started/#prerequisites) e saber o básico (básico mesmo) de git, e se você sabe isso você provavelmente consegue se virar com o [tutorial da página oficial do Quartz](https://quartz.jzhao.xyz/getting-started/). Do contrário, pra quem gosta das coisas fáceis (same tbh), vou te mostrar o jeito simples de clonar um projeto do GitHub e usar a sua conta de lá para deixar suas notas online através do GitHub Pages
##### Tutorial dentro do tutorial
**(com mais tutorial dentro (a boneca russa de tutoriais))**

1. [Instale o Git](https://git-scm.com/install/windows)
	
	Oh meu deus!! Que papo de nerd é esse!!?
	
	Não se desespere, jovem. Confia que esse é o caminho fácil.
	
	Se você não souber o que tá fazendo, baixe a versão atualizada pra Windows no primeiro link da página de download e siga essa colinha na instalação:
	
	Use the Nano editor by default $\textrightarrow$ Let Git decide $\textrightarrow$ Git from the command line and also from 3rd-party software $\rightarrow$  Use bundled OpenSSH $\rightarrow$ Use the OpenSSL library $\rightarrow$ Checkout Windows-style, commit Unix-style line endings $\rightarrow$ Use MinTTY (the default terminaL of MSYS2) $\rightarrow$ Fast-forward only $\rightarrow$ Git Credential Manager $\rightarrow$ Enable file system caching
	
	E pronto, só isso tudo. Marca Open Git Bash no final e ele já vai abrir a telinha pra você ir direto para o próximo passo. Nem doeu, viu só?
	
	*P.S.: eu não estou afirmando que esse é o melhor jeito de configurar o Git. Eu tô só improvisando e tentando facilitar a vida de quem também não sabe muito bem o que tá fazendo mas quer brincar. Agradeço a compreensão.*
   
2. [Crie uma conta no GitHub](https://github.com/signup) e faça login
	
	Essa parte é fácil, mas faça com atenção. Eu perdi um código de recuperação da minha primeira conta no GitHub e tive que abandonar ela. Ainda bem que não tinha quase nada lá mesmo.
   
3. Clone um [template Quartz](https://github.com/sosiristseng/template-quartz) para um repositório próprio
	
	Basicamente vamos pegar um projeto em que alguém já configurou a coisa toda, copiar e colar dentro da nossa própria conta, pra depois só jogar as anotações lá dentro. Ótimo, né? Também achei.
	
	**Por que esse template em específico?**
	
	Não seja chato. É o que eu usei e eu tô facilitando pra você. 🙄 Mas esse é um bom template porque ele integra o projeto original do Quartz com atualizações automáticas através de um bot e facilita a integração com o GitHub Pages (que é o que vai deixar a gente colocar o jardim online de graça) e com o Obsidian (que é, veja só, justamente o que estamos usando, se você vem me acompanhando até aqui). Tendeu?
	
	**E como eu clono isso?**
	
	No link do template que eu deixei ali em cima (ou em qualquer outro template Quartz do GitHub) você vai encontrar um botão verde que diz $\textquotedblleft$*Use this template*$\textquotedblright$. Geralmente no lado direito da tela, no topo da página. Clique nele! Vai surgir um menuzinho flutuante onde você vai selecionar a opção $\textquotedblleft$Create new repository$\textquotedblright$.
	
	Na página seguinte, o template `sosiristseng/template-quartz` deve estar selecionado e no passo `1. General` você deve ver o seu nome de usuário / um espaço em branco intitulado `Repository name`, que é exatamente o que diz na etiqueta. O meu se chama `garden`, apenas. A descrição é opcional. No passo `2. Configuration` você seleciona se seu repositório é público ou privado; como estamos fazendo algo que vai para a web, vai ficar público aqui. Depois é só dá-le no botão verde `create repository`. Tá pronto o sorvetinho!
   
4. Configure o GitHub Pages no seu repositório
	
	Logo depois de clonar o template você deve ser direcionado pro seu novo repositório, mas você consegue achá-lo também a qualquer momento em `https://github.com/*nome_de_usuario*/*nome_do_repositorio*`. Nessa página, clique no botão `More` $\textrightarrow$ `Settings`, que vai estar no canto superior direito da tela.
	
	Na página seguinte, o menu à direita terá a sessão *Code, planning, and automation*, e nela você encontra a opção `Pages`. Dentro dela, abaixo de *Build and deployment* você encontra a configuração de `Source`. Selecione ali a opção `GitHub Actions`.
   
5. De volta ao Git para colocar suas notas no GitHub
	
	Calma, vai dar tudo certo. Tá quase acabando agora. Vai lá na telinha estilo cmd do Git (que talvez você tenha deixado aberta desde a instalação) e, primeiramente, selecione a pasta do seu PC onde você vai armazenar os arquivos desse projeto usando o comando `cd` (eu esqueci de fazer isso na primeira vez e fiquei caçando a minha pasta depois rs). No meu caso, ficou assim:
	
	`cd /D/*pasta_pessoal*/github`
	
	Agora que você tá no lugar certo, coloque o seguinte comando **apropriadamente editado** né cabeção:
	
	`git clone --recursive https://github.com/*nome_de_usuario*/*nome_do_repositorio*.git`
	
	*Dica: dá pra colar com o botão direito.* 👍
	
	Depois disso você vai ver algumas linhas surgirem no seu terminal (especificamente 13 linhas, no meu caso; faz o L). Se surgir algum erro, o próprio terminal deve te avisar junto com alguma informação que você possa usar pra pesquisar a solução no Substack, no Reddit ou perguntar pro DeepSeek seilar. Aqui deu tudo certo. 
#### 2. [Instale o Obsidian](https://obsidian.md/download) e configure a pasta do seu jardim como um cofre
Aeee, a parte chatinha acabou! Sério!! Agora é mole, diversão. Vai até a pasta do seu diretório que você clonou pro seu PC (ela vai estar exatamente naquele caminho que você selecionou com o comando `cd` no passo anterior) e confira que dentro dela deve existir uma pasta chamada `content`. Viu ela lá? Perfeito.

Ao instalar o Obsidian, você vai precisar selecionar uma pasta no seu computador para ser um seu Cofre/Vault. Essa pasta é onde você encontra todas as anotações que você criar no Obsidian, tudo em formato de texto markdown, o que torna bem fácil de copiar, fazer backup, trocar de lugar etc. Se você não usa e não pretende usar o Obsidian para notas privadas, você pode selecionar direto aqui aquela pasta `content` como seu cofre.

Do contrário, caso você já tenha um cofre privado no Obsidian, é só você clicar no nome do seu cofre na parte inferior do menu lateral esquerdo do seu Obsidian, clicar em *Gerenciar cofres* e selecionar *Abrir pasta como um cofre.* Daí é só navegar até aquela pasta que você selecionou com `cd`, entrar na pasta com o nome do repositório e localizar a pasta `content` lá dentro.
#### 3. Escreve alguma coisa aí
Tá pronto o sorvetinho! Quer dizer, mais ou menos. Mas você já tem o seu canto fresco e fértil. Escreve qualquer coisa, pra ter o que enviar pra testar se tá tudo funcionando direitinho.

O que você quiser, po. No meu caso, eu escrevi isso aqui que você tá lendo, e também a homepage, pra começar. Não tem como ter um jardim sem nada plantado, né? Suas primeiras notas são suas primeiras sementes. Tem algumas ideias ali embaixo caso você esteja [pouco pensamento cabeça de vento](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGy9hvAl6SPpcQHR9ZhzMqFsp6foHqYmuouYFwD6FjrokDB81KN8KdjgY&s=10).

Ah, e é bom notar que a nota chamada **index** que já vem na sua pasta `content` é a página inicial do seu jardim. Então você pode editar ela e é o que você colocar ali que vai aparecer ao visitarem `https://*seu_user*.github.io/*seu_repositorio*/`.
#### 4. Envie o seu conteúdo novo para o GitHub
Ok, eu menti só um pouquinho quando eu disse que a parte chatinha tinha acabado. Você vai ter que voltar pro terminal do Git aqui. E toda vez que quiser publicar algo novo também. Mas é coisa pouca! E agora você tá familiarizado com o programa, né? Não precisa ficar intimidado.

Na primeira vez, você vai precisar configurar o acesso à sua conta do GitHub dentro do Git com os seguintes comandos:

- `git config --global user.email "seu_email@provedor.com"`: não surpreendentemente, esse aqui vai dizer pro git qual é o seu e-mail usado no GitHub. Inclua as aspas!
- `git config --global user.name "seu_user"`: pra ser sincero eu não tenho certeza se isso é uma configuração interna do Git ou se é obrigatório colocar exatamente o nome de usuário do GitHub aqui, mas foi o que eu fiz. Na dúvida, faça o mesmo. Aspas aqui também!

Aí uma nova janela deve ser aberta no seu navegador padrão te indicando pra fazer login no GitHub e autorizar o acesso. Você só precisa fazer isso uma vez (a princípio)!

Depois disso, **toda vez que você fizer novas notas e/ou alterações no seu jardim, você vai enviar essas mudanças pro GitHub** assim:

- `cd /DISCO/pasta/repositorio/`: você precisa usar o comando `cd` pra navegar pra pasta do seu repositório dentro do seu PC. É o mesmo caminho que usamos lá em cima, porém uma pasta mais "fundo", porque vamos entrar naquela pasta que importamos, a que tem o nome do seu repositório. Quando você estiver na pasta certa, vai ver um `(main)` em turquesa surgir acima da linha de comando no Git, ao lado do caminho onde você está.
- `git add .`: adiciona todos os arquivos modificados a área do Git onde eles precisam estar para serem enviados, que é chamada _staging area._ Sim, o espaço e ponto final fazem parte do comando!
- `git commit -m "Comentario"`: aqui você faz um novo commit no seu projeto e adiciona algum comentário explicando o que tem de novo dessa vez.
- `git push origin main`: é o comando que vai enviar tudo que existe de novo pro GitHub, que por sua vez vai automaticamente disponibilizar no seu endereço `https://*seu_user*.github.io/*seu_repositorio*/`através do GitHub Pages.

### E é isso!! Nem foi difícil, né? :)
Um pouco chato, talvez. Alguma coisinha aqui ou ali. Mas daqui pra frente, a manutenção é mais fácil: é só continuar cultivando seus pensamentos e plantando novas ideias através das notas do Obsidian, e mandar elas pra web usando três ou quatro comandinhos no terminal do Git. Suave!

*Dica: dá pra "voltar" e repetir comandos anteriores no terminal apertando  setinha pra cima.* 