# RaizeDataEngineeringTest ALTERADO

Repository for Raízen Data Engineering Test resolution. 

My name is Cynthia Saturnino dos Santos and I received this challenge link from Pedro Adamo.

### Dependencies

* Execute the create table statements below, before executing Python script:

        #CRIA DATABASE
        create database raizen;
        
        #CRIA TABELAS
        drop table if exists raizen.tb_Oil_By_UF_type;
        create table raizen.tb_Oil_By_UF_type ( 
        	yearmonth datetime
        	,uf varchar(2)
        	,product varchar(100)
        	,unit varchar(15)
        	,volume decimal(21,5)
        	,created_at datetime
        	,primary key (yearmonth, uf, product)
        );
        drop table if exists raizen.tb_Oil_By_UF_prod;
        create table raizen.tb_Oil_By_UF_prod ( 
        	yearmonth datetime
        	,uf varchar(2)
        	,product varchar(100)
        	,unit varchar(15)
        	,volume decimal(21,5)
        	,created_at datetime
        	,primary key (yearmonth, uf, product)
        );
