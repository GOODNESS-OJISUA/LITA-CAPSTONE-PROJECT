# LITA-CAPSTONE-PROJECT

**EXCEL ASSIGMENT**

<img width="172" alt="TOTAL SALES BY REGION" src="https://github.com/user-attachments/assets/b5d9a20a-f0ca-48e4-93a4-9646099f085c" />
<img width="166" alt="TOTAL SALES BY PRODUCT" src="https://github.com/user-attachments/assets/5a8a2892-8b44-472e-8594-e4a0abb5d14e" />
<img width="170" alt="TOTAL SALES BY MONTH" src="https://github.com/user-attachments/assets/0ba7f816-e551-4c72-8890-bb9691ec173e" />

<img width="949" alt="picture2" src="https://github.com/user-attachments/assets/0f967ed5-ae9a-4a4f-a3fd-14a39240f702" />
<img width="955" alt="picture 1" src="https://github.com/user-attachments/assets/96062e3d-5b53-4bdb-9e62-9ab3c23b8a87" />



...**SQL ASSIGNMENT**
```
SELECT TOP (1000) [OrderID]
      ,[Customer_Id]
      ,[Product]
      ,[Region]
      ,[OrderDate]
      ,[Quantity]
      ,[UnitPrice]
  FROM [LITACAPSTONE_DB].[dbo].[LITA PROJECT 1]

 alter table [LITACAPSTONE_DB].[dbo].[LITA PROJECT 1] add Revenue decimal (10,3)

 select * from [litacapstone_db].[dbo].[lita project 1]

 update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID = '1001'

 
 update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID = '1002'

  update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID = '1003'

   update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID = '1004'

     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1005'
 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1006'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1007'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1008'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1009'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1010'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1011'

     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1012'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1013'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1014'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1015'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1016'
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1017'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1018'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1019'
	 
     update [litacapstone_db].[dbo].[lita project 1] set Revenue = quantity * unitprice where ORDERID ='1020'

	 QUESTION 1
	 SELECT * FROM [litacapstone_db].[dbo].[lita project 1]

	 select SUM (revenue)
	 AS
	 'totalsale' from [litacapstone_db].[dbo].[lita project 1] where product = 'shirt'

	 select SUM (revenue)
	 AS
	 'totalsale' from [litacapstone_db].[dbo].[lita project 1] where product = 'shoes'

	 select SUM (revenue)
	 AS
	 'totalsale' from [litacapstone_db].[dbo].[lita project 1] where product = 'jacket'


	 QUESTION 2
	  SELECT * FROM [litacapstone_db].[dbo].[lita project 1]

	  select SUM (Quantity)
	 AS
	 'totalsaletransacton' from [litacapstone_db].[dbo].[lita project 1] where region = 'north'

	   select SUM (Quantity)
	 AS
	 'totalsaletransacton' from [litacapstone_db].[dbo].[lita project 1] where region = 'south'

	 
	   select SUM (Quantity)
	 AS
	 'totalsaletransacton' from [litacapstone_db].[dbo].[lita project 1] where region = 'West'

	 
	   select SUM (Quantity)
	 AS
	 'totalsaletransacton' from [litacapstone_db].[dbo].[lita project 1] where region = 'E

```
  
