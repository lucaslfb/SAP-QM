<div align="center">
  <h1>SAP QM - ETL</h1>
  <img align="middle" src=https://github.com/user-attachments/assets/b56b6ce6-6724-40d5-85fd-4c7e9acb833c

>
</div>



<h2>Descrição 📃</h2>
<p>Esse código é responsável por extrair, transformar e carregar dados através do Pentaho com destino ao SAP.</p>

<p>O ETL realiza a extração de dados de um excel no formato XML, efetua a transformação dos dados para futura carga nas duas
  tabelas SAP do objeto Inspection Method que pertence ao módulo de QM. As tabelas são: QMTB e QMTT, sendo a primeira
  Inspection Method Master Eecords e a segunda Inspection Method Texts.</p>

<p>O Job desenvolvido faz conexão com o SQL Server para armazenar os dados durante as etapas citadas. As tabelas do SAP, QMTB e
  QMTT são simuladas na última etapa, a de carga, afim de representar as Staging Tables presente no SAP FIORI (Migration
  Cockpit).</p>

<p>O Job está completamente em inglês para uma compreensão global, porém ao entender o significado de ETL torna-se fácil o
  entendimento.</p>


<h2>Status do Projeto ⌛</h2>
   
 ![Static Badge](https://img.shields.io/badge/status-finished-green)


<h2>Como usar 👣</h2>
<p>Para executar o Job, basta abrí-lo no Pentaho Data Integrator, configurar a conexão do banco de dados, configurar a variável
  de Path e criar as tabelas utilizadas em cada etapa, é aconselhável criar as tabelas através das próprias Table Outputs para
  agilizar o processo.</p>

  
<h2>Tecnologias usadas ⌨</h2>
  
 ![Pentaho](https://img.shields.io/badge/Pentaho-005073?style=for-the-badge&logo=pentaho&logoColor=white) ![SAP](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)

<h2>Autores</h2>

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/128868356?s=400&u=e46a4a066ab7c8789bb2ba1d68758a5471565aec&v=4" width=115><br><sub>Lucas Bezerra</sub>](https://github.com/lucaslfb)
