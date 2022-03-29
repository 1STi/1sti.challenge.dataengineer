## Desafio Engenharia de Dados - Nível Júnior

### Objetivo
Arquiteturar solução utilizando Apache Airflow com o objetivo de coletar dados da [16º OBMEP](http://premiacao.obmep.org.br/16aobmep/mapa.htm) e obter insights por meio de consultas em tabelas no AWS Athena.

### Etapas

1. Coletar dados dos medalhistas de ouro, prata, bronze e menções honrosas das escolas públicas e privadas;
2. Converter as diferentes tabela em um único arquivo no formato parquet;
3. Criar tabela no AWS Athena utilizando o arquivo gerado no item anterior;
4. Obter insights via consultas SQL no Athena.

### Insights

1. Quais são as escolas públicas e privadas com o maior número de medalhistas?
2. Quais são os estados com o maior número de medalhistas?
3. Quais são as cidades com o maior número de medalhistas?
