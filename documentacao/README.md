[Projeto Agência de Viagens - Etapa 3- 20-09-21.docx](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2021-2-e2-proj-bpm-t2-agenciadeviagem/files/7424911/Projeto.Agencia.de.Viagens.-.Etapa.3-.20-09-21.docx)
# Documentação do projeto

Liste os documentos disponibilizados nesta pasta com uma breve descrição do conteúdo de cada um deles.

* relatorio_final.pdf - Relatório do projeto.
* apresentacao.mkv - Vídeo de apresentação do projeto.
* slides.pptx - Slides da apresentação final do projeto.
 

Resumo. O tema escolhido pelo grupo foi Agência de viagem. Este trabalho tem por finalidade entender e propor melhorias nos processos desenvolvidos na comercialização de produtos e seus desafios diante das novas tecnologias e do novo cenário pós-pandemia, visto que foi a partir desses fatos que se iniciou toda uma reestruturação no mercado de agências. 

 

1. Introdução 

 

O turismo é uma das principais atividades econômicas do Brasil. Para atender a demanda do setor muitas empresas se valeram dos serviços de agências que faziam todo o trabalho de hospedagem, transporte, alimentação e etc. E com o aumento das atividades e serviços cada vez mais diversificados as agências enfrentaram e enfrentam desafios para atender os clientes.  

Além da adequação as novas tecnologias do setor turístico assim como todos os outros setores enfrentam agora os desafios impostos pela pandemia de acordo com a Forbes (2021) “O turismo foi um dos setores mais afetados pela pandemia de Covid-19 e um dos primeiros a sentir os impactos negativos causados pelas políticas de restrições, cancelamento de viagens e fechamento de fronteiras. 

Em dezembro de 2020, a OMT (Organização Mundial do Turismo) divulgou uma nota informando que o período entre janeiro e outubro do ano passado perdeu 900 milhões de turistas internacionais, impacto que se traduz na perda de US$ 935 bilhões em receitas.” [der 1.drawio-alterado 27-11-21.pdf](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2021-2-e2-proj-bpm-t2-agenciadeviagem/files/7657242/der.1.drawio-alterado.27-11-21.pdf)


Segundo os especialistas do setor, a recuperação dos índices positivos apresentados antes da pandemia será demorada visto que apesar da imunização as incertezas ainda permeiam a recuperação do setor.  A pandemia criou algumas tendências e acelerou outras, como por exemplo a aplicação da tecnologia para melhor gerenciamento e personalização da oferta dos produtos das agências.  

Diante dos desafios que estão por vir e os que já estão enfrentando esse setor nosso grupo irá, embasado em pesquisas e estudos, propor melhorias para o desenvolvimento dos processos de negócios no setor do turismo.
 
 2. Participantes do processo de negócio
Stakeholders ou partes interessadas são qualquer pessoa envolvida com um projeto, organização ou setor específico, no caso, envolvidos com o projeto de "Agência de Viagem". Os Stakeholders, portanto podem ser uma pessoa individual, como um turista ou um grupo de turistas. Podem ser um grupo de pessoas, podem ser uma empresa ou pessoas da 3° idade. Não necessariamente estamos falando de um agente diretamente envolvido financeiramente com o negócio.  

 
 3.1Modelagem dos Processos Atuais (AS-IS)
 Processo 1- Cadastrar cliente -AS-IS 
 
 
![image](https://user-images.githubusercontent.com/81273050/139176533-48e040eb-9b9d-41ab-8929-53506a82267e.png)

Processo 2- Cadastrar hotéis-AS-IS 


![image](https://user-images.githubusercontent.com/81273050/139176832-49dacc4d-7d57-44ff-a92a-928ce6824857.png)

Processo 3- Cadastrar pacotes-AS-IS 


![image](https://user-images.githubusercontent.com/81273050/139176925-6f7f935d-ab44-4168-9f51-f6adcff6c6e3.png)

 
Processo 4 – Reservar pacotes –AS-IS 


![image](https://user-images.githubusercontent.com/81273050/139177387-d3dfb33d-2cee-415c-a660-b54ee72d6d09.png)



3.2.  Modelagem dos processos aprimorados (TO-BE) 
Proposta de melhorias:
1. Os pacotes de agências, em parte geral, são prontos e não são maleáveis. 
R: Propor, no site da agência, uma forma pela qual o usuário possa montar seu pacote de viagem, podendo este escolher o hotel, as condições de tráfego, as condições internas de locação e outras opções adicionais.
2. As agências de viagem não possuem um sistema pelo qual um dono de um hotel ou similar possa cadastrar seu hotel e se candidatar como possível hospedagem nos sistemas.
R: Em regra, as agências de viagem possuem planos integrados com hotéis consagrados e que normalmente possuem um alto valor agregado para viagem. A ideia seria criar um sistema para que o pequeno proprietário possa cadastrar seu  estabelecimento no sistema da agência para que ele também possa entrar no mercado e atender o consumidor que não queira gastar tanto em hospedagem.
3. Altas taxas aplicadas, em geral, pelas agências tradicionais, é de fato um venerável. É necessário que se busque diminuir as altas taxas cobradas para que o usuário se sinta confortável para contratar um serviço que não é essencial como é deste ramo.
R: Ao invés do cliente pagar as altas taxas integralmente como de praxe, há de se pensar na possibilidade de cobrar pequenas taxas dos estabelecimentos que estão cadastrados no sistema. Com isso, o cliente se sentiria mais confortável ao ver que está contratando um serviço eficiente e que também não está aumentando consideravelmente o gasto da viagem. Isso incentivaria o mercado e aumentaria a quantidade de clientes interessados.

Modelagem da solução proposta (modelo TO-BE) realizada com o apoio da ferramenta baseada em BPM Sydle One. 
Processo 1- Cadastrar cliente 


![image](https://user-images.githubusercontent.com/81451748/139040997-7da7e8f7-bc01-482f-964b-601fcc87626d.png)



Processo 2- Cadastrar hotéis


![image](https://user-images.githubusercontent.com/81451748/139041106-e0980249-d71b-40dc-8f1f-f6200f8bd996.png)


Processo 3- Cadastrar pacotes


![image](https://user-images.githubusercontent.com/81451748/139041291-04f0f746-a701-45ea-b662-d51a1cc06d26.png)


Processo 4- Reservar pacote


![image](https://user-images.githubusercontent.com/81451748/139041527-112f1072-2e60-464e-b508-e5849f328368.png)

 . Projeto da arquitetura de dados da solução proposta
![image](https://user-images.githubusercontent.com/81451748/142345651-fa9e634d-baf8-45a9-b034-0ff159e6ef55.png)

4ª Atividade: Descrever como propriedades dos processos e de suas atividades
3o Passo: Gravar um vídeo apresentando, na ferramenta Sydle One, as classes criadas na atividade anterior, as propriedades dos processos modelados e de suas respectivas atividades. Esse vídeo de ter duração de, no máximo, 6 minutos e formato mp4.




https://user-images.githubusercontent.com/81273050/141032467-7058badb-ae18-4b63-b969-f7c57fea8cac.mp4





https://user-images.githubusercontent.com/81273050/141031522-c5b54f07-e48e-4fe8-86ef-77622ca7b1a1.mp4


Em material de apoio, você encontrará uma videoaula explicando como criar as propriedades dos processos e de suas respectivas atividades. Utilize-a como referência para realizar essa atividade.

4.2. Impactos da implementação em um banco de dados NoSQLAvaliem e descrevam as possibilidades, riscos e impactos do emprego de um banco de dados NoSQL para implementação da solução proposta: 

O NoSQL tem muitas vantagens para ser utilizado. Mas não é por isso que devemos utilizá-lo em todas as situações. Em muitos sistemas, você pode (e até deve) usar o modelo relacional. O NoSQL é mais indicado para aqueles sistemas que tenham necessidades maiores de armazenamento e desempenho.  

O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados. Sendo assim, você pode usar ambas as soluções para diferentes casos de uso. Por isso, o mais comum em soluções escalares de sucesso é a utilização de uma arquitetura híbrida, aproveitando o melhor dois dois modelos. 

4.3. Modelo relacional
![image](https://user-images.githubusercontent.com/81451748/139042077-9cc2ab69-984a-4a06-85ff-c316b2106aa5.png)


Etapa 5 - Indicadores de desempenho para o processo de negócio

 5 Relatórios analiticos      




Relatório destinos mais procurados
![image](https://user-images.githubusercontent.com/81451748/142738965-ad960a84-479e-4853-af9e-6aea0285a59f.png)
 

Relatório forma de pagamento
![image](https://user-images.githubusercontent.com/81451748/142739018-2a6c5fb5-4ada-4b67-b99c-3b09194462da.png)
Relatório forma de pagamentoV Relatório cadastro X vendaimage](https://user-images.githubusercontent.com/81451748/142739061-3d821590-04ab-41d7-8a93-958f3c595445.png)Relatório venda X finalização


![image](https://user-images.githubusercontent.com/81451748/142739071-c82c3369-092b-495e-a98b-050aeaebee33.png)

Relatório pacotes mais procurados 
 ![image](https://user-images.githubusercontent.com/81451748/142739075-afe10cd3-4e8d-4c2a-b46e-f0975d7c6e3c.png)

Relatório média notas
![image](https://user-images.githubusercontent.com/81451748/142739077-69d2fa6d-b330-442a-8cba-18506b64beb5.png)
![image](https://user-images.githubusercontent.com/81451748/142739082-8edf1db3-2b1f-43fc-b646-425c3d3e74e2.png)
![image](https://user-images.githubusercontent.com/81451748/142739088-1cce9a42-5182-416e-b02f-46bff985abf8.png)

Relatório cliente X venda
 ![image](https://user-images.githubusercontent.com/81451748/142739091-e3d70076-1917-4d12-abd3-e36a976a2c0f.png)

Relatório venda de pacotes anual
![image](https://user-images.githubusercontent.com/81451748/142739096-2d797bfc-0d35-4c4f-8eca-30b0ab2f17dd.png)
![image](https://user-images.githubusercontent.com/81451748/142739104-065f1f72-0e1d-4f23-ae7a-91014950caab.png)

5-1 - Associação de comandos SQL com relatórios analiticos




SELECT ANO( A.data_da_criação), B nome, COUNT(*) AS Qtde, SUM(A.Dados bancários)AS Quantidade
FROM CADASTRO A, TURISTA B
WHERE A.id_cliente=B.id_cliente
GROUP BY B.data_de_criacao 


SELECT DESTINO, DATA DE ENTRADA
COUNT(*) AS Qtde, SUM(A.Destinos)AS Quantidade
FROM DESTINOS MAIS PROCURADOS A, DATA DE ENTRADA B
WHERE A.destino<> B.data_entrada

SELECT ANO(A.data_da criação), B.nome,COUNT(*)AS Qtde, SUM(A.Valor)AS Somatorio FROM PAGAMENTO A, CLIENTE B WHERE A.id_cliente=B.id_cliente 
GROUP BY ANO(A.data_da criação,B.nome)

SELECT B. nota, AVG(A.ValorTotalDaNota) AS Media FROM PAGAMENTOA, CLIENTE B WHERE A.id_clienteTurista=B.id_clienteTurista
 GROUP BY B.nota
 
 
SELECT MONTH(DataVenda) AS 'Mes',
COUNT(TipoDePagamento) AS 'QtdPorMes'
FROM TIPO DE PAGAMENTO 
WHERE DataVenda > 01/01/2021
GROUP BY MONTH(DataVenda)
ORDER BY MONTH(DataVenda);




https://user-images.githubusercontent.com/81451748/144772182-1206c133-21be-4a7c-80eb-45cf0428ef48.mp4

