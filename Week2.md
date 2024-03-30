#  Problema-1 (20-03-024)
-Dificulty to setup VCPKG with vs2022;
-Prasentation of equation of Chapman Richards https://moja-global.github.io/Handbook/Chapter2/section_one.html
-Chapter Chapter 5: Running a GCBM Simulation (Update the bounding box Next, we update the bounding box.'Need paragraph' The bounding box defines the study area of the plant simulation, and other spatial layers are cropped and reprojected to the area specified in the bounding box.),(Configure the mean annual temperature'Need paragraph' Next, we configure the mean annual temperature vector layer.)
-To add in handbook:
Preparação de dados tabulares (caderno jupyter)
Coisas a acrescentar:

informações sobre a função de crescimento de Chapman-Richards

Como funciona curve_fit função do Scipy

nota sobre a tentativa de diferentes palpites iniciais para parâmetros (pode explicar durante a próxima chamada)

mencione a importância da visualização de dados, European Beech é um exemplo

Nota sobre as espécies: Tem que verificar se as espécies relacionadas estão em **documentação:látex-bruto:espécies_names.csv**. ## Banco de dados de entrada geração (Recliner2GCBM)

Em seguida, precisamos gerar o banco de dados de entrada do projeto. Para criar o banco de dados de entrada, precisamos do seguinte:

Um banco de dados CBM3 ArchiveIndex (AIDB). O banco de dados ArchiveIndex é um banco de dados que contém referências não espaciais e espaciais Parâmetros. Esses parâmetros incluem, mas não estão limitados a: taxas, matrizes de perturbação, coeficientes de biomassa radicular etc.

Uma tabela de rendimento em ou / formato.csv.xls.xlsx