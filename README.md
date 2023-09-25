# AtividadeBancoDeDados

```sql
--questão 01--
select * from tabela_paises
```
![image](https://imgur.com/kIMy0A6l.png)
```sql
--questão 02--
select pais, cidade from tabela_paises where pais = 'Brazil'
```
![image](https://imgur.com/DHFtJA3l.png)
```sql
--questão 03--
select pais, regiao, cidade from tabela_paises where regiao = 'Ceará'
```
![image](https://imgur.com/mZxvSt8l.png)
```sql
--questão 04--
select count(regiao) as total_regioes from tabela_paises where pais = 'China' group by pais
```
![image](https://imgur.com/XNGO0ihl.png)
```sql
--questão 05--
select count(regiao) as total_regioes from tabela_paises where pais = 'Canadá' group by pais
```
![image](https://imgur.com/YmNZn3el.png)
```sql
--questão 06--
select count(pais) as total_regioes from tabela_paises group by pais
```
![image](https://imgur.com/5aJDOl1l.png)
```sql
--questão 07--
select count(distinct cidade) from tabela_paises where pais = 'Brazil'
```
![image](https://imgur.com/4zdK3M3l.png)
```sql
--questão 08--
select pais, count(pais) as total_regioes from tabela_paises group by pais
```
![image](https://imgur.com/2FXbaC8l.png)
```sql
--questão 09--
select count(nome) from tabela_paises where nome like 'João%'
```
![image](https://imgur.com/ISMlwH3l.png)
```sql
--questão 10--
select count(nome) from tabela_paises where nome = 'Jhon'
```
![image](https://imgur.com/1Y2ZJ0Rl.png)
```sql
--questão 11--
select distinct pais from tabela_paises order by pais ASC
```
![image](https://imgur.com/M2Kzfp9l.png)
