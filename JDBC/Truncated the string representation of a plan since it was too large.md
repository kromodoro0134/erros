#### PROBLEMA
Ao renderizar uma consulta muito grande pode ser retornada a mensagem "Truncated the string representation of a plan since it was too large."

#### SOLUÇÃO
Adicionar a linha abaixo antes de acessar a base de dados
```
spark.conf.set("spark.sql.debug.maxToStringFields", 1000)
```

#### LINK
(Spark: "Truncated the string representation of a plan since it was too large." Warning when using manually created aggregation expression)[https://stackoverflow.com/questions/43759896/spark-truncated-the-string-representation-of-a-plan-since-it-was-too-large-w]
