# AtividadeBancoDeDados

```sql
--questão 01--
select * from tabela_paises
```

--questão 02--
select pais, cidade from tabela_paises where pais = 'Brazil'
--questão 03--
select pais, regiao, cidade from tabela_paises where regiao = 'Ceará'
--questão 04--
select count(regiao) as total_regioes from tabela_paises where pais = 'China' group by paisp
--questão 05--
select count(regiao) as total_regioes from tabela_paises where pais = 'Canadá' group by pais
--questão 06--
select count(pais) as total_regioes from tabela_paises group by pais
--questão 07--
select count(distinct cidade) from tabela_paises where pais = 'Brazil'
--questão 08--
select pais, count(pais) as total_regioes from tabela_paises group by pais
--questão 09--
select count(nome) from tabela_paises where nome like 'João%'
--questão 10--
select count(nome) from tabela_paises where nome = 'Jhon'
--questão 11--
select distinct pais from tabela_paises order by pais ASC
![image](https://github.com/Samuelzr/AtividadeBancoDeDados/assets/111665246/8b102ca9-effe-49c8-877a-9356ed6ea310)

![image](https://imgur.com/BroXv2v.png)
