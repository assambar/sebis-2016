# SQL синтаксис.
Трябва да можете да обясните какво прави коя да е от съхранените процедури в базата ви.
 - Базови знания за `SELECT`, `INSERT`, `UPDATE`, `FROM`, `WHERE`, `ORDER BY`, `JOIN`, etc.
Обща представа какво правят следните фрагменти от заявки
 - `CREATE PROCEDURE CatalogGetDepartments AS`
 - `	[DepartmentID] [int] IDENTITY(1,1) NOT NULL,`
 - `CONSTRAINT [PK_Department] PRIMARY KEY CLUSTERED (DepartmentID))`
 - `ALTER TABLE ProductCategory  WITH CHECK ADD CONSTRAINT FK_ProductCategory_Category`
 - `SET IDENTITY_INSERT Category ON`
 - `DECLARE @Products TABLE`
 - `SELECT ROW_NUMBER() OVER (ORDER BY Product.ProductID),`
 - `CASE WHEN LEN(Description) <= @DescriptionLength THEN Description ELSE SUBSTRING(Description, 1, @DescriptionLength) + '...' END`
 - `SELECT 1, 1, 'White' UNION ALL SELECT 2, 1, 'Black' UNION ALL`
 - `CREATE FULLTEXT CATALOG BalloonShopFullText AS DEFAULT`
 - `CREATE FULLTEXT INDEX ON Product(Name, Description) KEY INDEX PK_Product ON BalloonShopFullText`
 - `SELECT COALESCE(NameResults.[KEY], DescriptionResults.[KEY]) AS [KEY],`
 - `SET @OrderID = @@IDENTITY`
 

# По структурата на базата данни
# По структурата на проекта
# В App_Code
