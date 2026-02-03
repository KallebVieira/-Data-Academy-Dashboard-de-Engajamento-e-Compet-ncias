# 📊 Data Academy: Dashboard de Engajamento e Competências

## 📝 Visão Geral
Este projeto analisa o comportamento de alunos em uma plataforma de ensino de dados (EdTech). 
O objetivo é transformar dados brutos de um banco SQLite em insights sobre consumo de cursos e perfis técnicos.

## 🛠️ Tecnologias Utilizadas
* **SQL (SQLite):** Extração e tratamento de dados.
* **Power BI:** Modelagem, DAX e Visualização.
* **Markdown:** Documentação do projeto.

## 🗄️ Estrutura do Banco de Dados
O banco de dados original contém as seguintes tabelas:
* `cursos`: Catálogo de treinamentos.
* `cursos_episodios`: Detalhes das aulas.
* `cursos_episodios_completos`: Log de progresso dos alunos.
* `habilidades_usuarios`: Mapa de competências técnicas.

## 🚀 Etapas do Projeto

### 1. Extração de Dados (SQL)
Nesta etapa, filtrei apenas as informações relevantes para o negócio, evitando sobrecarga no Power BI.
[AQUI ENTRARÁ O SEU RELATO DOS DESAFIOS QUE RESOLVEMOS]

### 2. Modelagem de Dados
Utilizei o conceito de *Star Schema* para relacionar as tabelas de fatos e dimensões...
[AQUI ENTRARÁ O PRINT DO SEU MODELO NO POWER BI]

### 3. O Dashboard (4 Páginas)
1. **Visão Geral:** KPIs de performance global.
2. **Análise de Conteúdo:** Rankings de cursos.
3. **Mapa de Skills:** Perfil técnico dos talentos.
4. **Ficha do Aluno:** Visão individualizada.

## 🛠️ 1. Extração e Higienização de Dados (SQL)

Nesta fase inicial, utilizei **SQL (SQLite)** para extrair as tabelas brutas e garantir que apenas dados relevantes fossem levados ao Power BI. Isso otimiza a performance do modelo e garante a integridade das métricas.

<br>

<div align="center">
  <img src="./caminho-para-seu-print/print-sql-01.png" alt="Consulta SQL de Cursos" width="80%">
  <p><i>Figura 1: Query para extração da dimensão de cursos ordenada por ano.</i></p>
</div>

<br>

### 🔍 Notas Técnicas de Junior:
* **Limpeza:** Selecionei apenas colunas de texto e data, ignorando chaves de sistema que não agregam valor ao negócio.
* **Ordenação:** Apliquei o `ORDER BY` para facilitar a conferência dos dados logo na importação.

---

