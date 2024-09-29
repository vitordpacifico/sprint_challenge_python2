<h1>Sprint de Python</h1>

<h2>Membros:</h2>

<p>Anthony Motobe - RM-558488</p>

<p>Arthur Rodrigues - RM-555342</p>

<p>Guilherme Abe - RM-554743</p>

<p>Gustavo Paulino - RM-554779</p>

<p>Victor Dias - RM-558017</p>


<h2>Descrição do Projeto</h2>

<p>O código, quando executado, apresenta ao usuário uma interface simples em linha de comando que exibe uma lista de equipes da Fórmula E. O usuário escolhe uma equipe digitando o número correspondente, e então são exibidas informações detalhadas da equipe, como títulos conquistados e curiosidades. Após isso, são listados os pilotos dessa equipe, permitindo que o usuário selecione um piloto para visualizar mais informações, incluindo o número de vitórias, títulos, e curiosidades específicas sobre o piloto. Toda interação é registrada em um arquivo de log, incluindo as seleções de equipe, piloto e eventuais erros de entrada. O usuário pode, ao fim da interação, retornar ao menu principal ou encerrar a aplicação. </p>

<h2>Instruções de Uso</h2>

<p>Para utilizar o código o usuário deve escolher uma das equipes exibidas no menu, em seguida será mostrado informações relevantes da equipe junto com seus respectivos pilotos, os quais é possível acessar digitando o número correspondente do piloto e assim será exibida mais informações sobre o piloto escolhido. Caso deseje ver informações de outra equipe, será necessário clicar "1", já se deseja encerrar o programa, clicar "0", o sistema irá gravar o percurso feito pelo usuário adentro dele salvando em arquivos .txt as decisões do usuário. E ele irá passar por automações e por um try exept.</p>

<h2>Dependências</h2>

<p>O código que será necessário se encontra no repositório do Github. É recomendado utilizar na versão Python 3.11.9

<h2>Requisitos</h2>

<p>Aconselhamos o usuário a possuir a versão mais recente de Python instalado em sua maquina, e uma IDE como Pycharm ou VSCode.

<h2>Diagrama em blocos do código</h2>

<p>Início da aplicação: O sistema é iniciado e mostra um menu de seleção de equipes para o usuário</p>
                            
                            V
<p>Seleção de Equipe: O usuário pode escolher uma equipe da lista para ver informações</p>
                           
                            V
<p>Se o número digitado for inválido, ele irá retornar ao menu de seleção de equipes</p>
                          
                            V
<p>Seleção de Pilotos: O usuário escolhe um piloto da equipe selecionada para se obter informações</p>
                           
                            V
<p>Se o número digitado for inválido, ele irá retornar ao menu de seleção de piloto</p>
                           
                            V
<p>Se for válido, irá exibir as informações detalhadas do piloto escolhido</p>
                            
                            V
<p>Retornar ao Menu Principal: O usuário pode optar por voltar ao menu principal ou sair do sistema</p>
                            
                            V
<p>Logs: Cada interação do usuário com o sistema (seleção de equipe, piloto, ou erros) é registrada em um arquivo de log que será salvo como .txt</p>

<h2>Link do video apresentação do código</h2>
<p>https://youtu.be/8uk5UzGoOWk</p>
