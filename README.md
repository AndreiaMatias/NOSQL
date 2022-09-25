#Bancos de dados NoSQL e SQL

NoSQL significa not only SQL. Abrange diversar tecnologias não relacionais.

Enquanto no SQL, há relacionamento e a estrutura é rígida, no NoSQL, não há essa necessidade. Esses banco de dados são úteis para dados semiestruturados e não estruturados.

Os BD relacionais geralmente escalam de forma vertical, já os NoSQL utilizam o horizontal (o mais conhecido é o sharding).

os schemas de BD relacionais é rígida e precisa moldar previamente. No noSQL não há necessidade de pré-definir o que será incluído.

A performance de BD NoSQL depende do tamanho do cluster e da latência da rede.

Com relação às transações, no SQL, são observadas as propriedades ACID (Atomicidade, consistência, isolamento, durabilidade). Se houver algum erro, é feito o rollback. O noSQL não observa essas propriedades. Suas propriedades são BSE (basically available, soft-state e eventually consistent).

Os bancos de dados no SQL não substituem os BD relacionais
Dependendo do contexto, é necessário escolher o banco de dados NoSQL mais adequado às necessidades.

Os tipos de BD NoSQL são: baseados em documentos, de chave-valor, orientados a colunas, grafos (utilizados em redes sociais, detecção de fraudes). 

Os dados podem ser armazenados em um datalake para consumo em outro momento.
Num ambiente de dados há pelo menos cinco capacidades básicas: ingestão, armazenamento, processamento, disponinilidade, segurança/governaça.

