# 🚀 Python-Pyspark_Lib

Repositório dedicado ao estudo e aplicação prática do **PySpark**, abrangendo desde os conceitos fundamentais de processamento distribuído de dados até técnicas avançadas de análise de dados e Machine Learning utilizando o ecossistema Apache Spark.

O conteúdo foi desenvolvido com foco em aprendizado progressivo, permitindo explorar RDDs, DataFrames, Spark SQL, tratamento de dados, agregações analíticas e pipelines de Machine Learning com MLlib.

---

# 📚 Conteúdo do Repositório

## ⚙️ 1. Testando PySpark

**Notebook:** `Testando_Pyspark.ipynb`

### Objetivo

Validar a instalação e configuração do ambiente PySpark.

### Tópicos abordados

* Instalação do PySpark
* Inicialização da SparkSession
* Verificação da versão do Spark

---

## 🏁 2. PySpark Básico

**Notebook:** `Pyspark Básico.ipynb`

### Objetivo

Apresentar os conceitos iniciais para leitura, gravação e consulta de dados.

### Tópicos abordados

* Configuração do Java JDK 11 e PySpark
* Leitura de arquivos CSV
* Inferência automática de schema
* Escrita e leitura em formato Parquet
* Criação de tabelas com `saveAsTable`
* Consultas SQL utilizando `spark.sql()`

---

## 📥 3. Definição e Coleta de Dados

**Notebook:** `Pyspark_Definição_e_Coleta_de_Dados.ipynb`

### Objetivo

Explorar a criação e manipulação de RDDs e DataFrames.

### Principais conceitos

#### 🔹 Trabalhando com RDDs

* SparkContext
* parallelize()
* Particionamento de dados
* Operações com Lambda Functions
* first(), take() e collect()

#### 🔹 Transformações e Ações

* map()
* flatMap()
* reduceByKey()
* saveAsTextFile()

#### 🔹 Leitura de Arquivos

* CSV com parâmetros avançados
* inferSchema
* mode="DROPMALFORMED"

#### 🔹 Estruturação de Dados

* StructType
* StructField
* StringType
* FloatType
* DateType
* createDataFrame()

#### 🔹 Escrita e Catálogo

* Exportação para CSV, JSON, Parquet e ORC
* Views temporárias
* Gerenciamento de bancos de dados Spark

---

## 🧼 4. Tratamento de Dados

**Notebook:** `Pyspark_Tratamento_de_Dados.ipynb`

### Objetivo

Aplicar técnicas de limpeza, transformação e validação de dados.

### Principais conceitos

#### 🔹 Limpeza de Dados

* na.fill()
* na.drop()
* dropDuplicates()

#### 🔹 Transformação

* withColumn()
* cast()
* upper()
* Tratamento de datas
* Conversão de formatos brasileiros

#### 🔹 Integração de Dados

* Inner Join
* Left Join
* Right Join
* Outer Join
* concat()
* lit()

#### 🔹 Validação e Qualidade

* when().otherwise()
* isin()
* left_anti
* Expressões regulares com rlike()
* Auditoria de dados

---

## 🤖 5. Projeto de Machine Learning

**Notebook:** `Projeto_Pyspark_Tratamento.ipynb`

### Objetivo

Construção de um pipeline completo de preparação de dados e treinamento de modelos preditivos.

### Técnicas aplicadas

* StringIndexer
* VectorAssembler
* MinMaxScaler
* PCA (Principal Component Analysis)
* randomSplit()
* LinearRegression

### Métricas avaliadas

* RMSE
* R² (Coeficiente de Determinação)

---

## 📊 6. Projeto de Agregações

**Notebook:** `Projeto_Pyspark_Agregações.ipynb`

### Objetivo

Desenvolver análises analíticas utilizando agregações e Window Functions.

### Técnicas aplicadas

* groupBy()
* avg()
* count()
* variance()
* format_number()
* count_distinct()

### Window Functions

* Window.partitionBy()
* orderBy()
* rowsBetween()

### Aplicações

* Médias acumuladas
* Métricas temporais
* Indicadores de negócio

---

# 🛠️ Tecnologias Utilizadas

| Tecnologia          | Descrição                        |
| ------------------- | -------------------------------- |
| 🐍 Python 3         | Linguagem principal              |
| ⚡ Apache Spark      | Processamento distribuído        |
| 🔥 PySpark          | API Python do Spark              |
| 📊 Spark SQL        | Consultas e manipulação de dados |
| 🤖 Spark MLlib      | Machine Learning                 |
| 📓 Jupyter Notebook | Ambiente de desenvolvimento      |
| ☁️ Google Colab     | Execução em nuvem                |

---

# 🚀 Como Executar

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/AlderARS/Python-Pyspark_Lib.git
```

### 2️⃣ Instale o PySpark

```bash
pip install pyspark
```

### 3️⃣ Verifique a instalação do Java

Certifique-se de possuir o Java 11 ou superior instalado e configurado na variável de ambiente:

```bash
JAVA_HOME
```

### 4️⃣ Execute os notebooks

```bash
jupyter notebook
```

ou faça upload dos arquivos para o Google Colab.

---

# 🎯 Competências Desenvolvidas

* Processamento Distribuído de Dados
* Engenharia de Dados
* ETL
* Spark SQL
* Machine Learning
* Data Wrangling
* Data Validation
* Feature Engineering
* Window Functions
* Big Data Analytics

---

# 👨‍💻 Autor

Desenvolvido por **AlderARS** como parte dos estudos em:

📊 Engenharia de Dados
⚡ Apache Spark
🤖 Machine Learning
🐍 Python para Big Data

