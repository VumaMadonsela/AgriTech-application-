Download the files then open them on your desktop using Viusal studio, 
After opening the Application the DataBase is in the Models. 
To Configue the database, go to tools to add the needed database framework; go to Nuget manager >> Download Microsoft enitity framworkCore. and Entity Framework. 
type: under ProductsDbContext.cs

Public class ProductsDbContext : DbContext
DbSet<Products> Products {get ; set; }
Public object Products {get; internal set; }
public ProductsDbContext(DbContextOptions<ProductsDbContext> options) : base(options) 
