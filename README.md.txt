Trabalho de probabilidade(IMD0033)

Professor:
Ivanovitch Medeiros Dantas da Silva

Alunos:
Vanessa Sayuri Uchida
vanessa_sayuri@hotmail.com

Felipe Douglas Cavalcante Marinho de Vasconcelos
felipedcmv_@hotmail.com

Jesse Grazianny Pinheiro de Albuquerque
jessealbuquerque92@gmail.com

Motivação e objetivo:
Neste trabalho referente à parte da nota da segunda unidade da disciplina de probabilidade, nosso objetivo é, através dos dados coletados, agrupar e exibir de uma forma intuitiva e simples um grande volume de dados referentes ao desempenho dos alunos do curso de BTI em diversas disciplinas(escolhemos as disciplinas obrigatórias dos três primerios semestres). A pesquisa foi realizada com o intuito de investigar os índices de reprovação, trancamento e desistência nas matérias escolhidas, bem como fomentar uma discussão sobre as causas dos números apresentados. Todos os dados foram retirados do  portal de dados abertos da UFRN(http://dados.ufrn.br). As bibliotecas pandas, numpy e matpotlib foram utilizadas para o tratamento dos dados.

Descrição:
O primeiro dataframe utilizado foi extraído do link "http://dados.ufrn.br/dataset/02526b96-cf40-4507-90b0-3afe5ddd53e7/resource/a10bc434-9a2d-491a-ae8c-41cf643c35bc/download/cursos-de-graduacao.csv", que contém todos os cursos da UFRN e os seus códigos de identificação. Descartamos dados adicionais que não foram necessários para a nossa pesquisa.
Através do id do curso de BTI, que encontramos no dataframe mencionado, foi possível encontrar a situação dos alunos de todas as turmas do curso em um dado semestre(começamos por 2017.2) no link "http://dados.ufrn.br/dataset/c8650d55-3c5a-4787-a126-d28a4ef902a6/resource/55dfe713-ff7c-4fa8-8d1d-d4294a025bff/download/matricula-componente-20172".
A situação das turmas no semestre foi obtida através de "http://bit.do/turmas_ufrn_2017_2". Assim foi possível saber quais turmas estavam consolidadas e quais foram canceladas, por exemplo.
Para selecionar as disciplinas do curso, utilizamos o dataframe do link "http://dados.ufrn.br/dataset/3fea67e8-6916-4ed0-aaa6-9a8ca06a9bdc/resource/9a3521d2-4bc5-4fda-93f0-f701c8a20727/download/componentes-curriculares-presenciais.csv".
Através do comando merge, foi possível mesclar os dados que nos interessavam, mantendo um dataframe mais limpo e objetivo.
Por fim, na escolha por uma forma de representação gráfica de dados que fosse capaz de condensar todas as variáveis de nossa pesquisa, optamos por um gráfico de barras.

O vídeo com a apresentação do trabalho pode ser encontrado no link:
https://youtu.be/Q0dqh3Cb3Bk




