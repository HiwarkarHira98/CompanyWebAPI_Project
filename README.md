# ASP.NET MVC Compnay_Web_API

## Overview
This is a simple **ASP.NET MVC** application that demonstrates how to use **Model-View-Controller (MVC)** architecture to manage products. The application displays a list of products, showcasing how models, controllers, and views work together.

## Features
- Displays a list of products.
- Uses **Model objects** to store product data.
- Demonstrates **Controller logic** for passing data to the View.
- Uses **Views** to render product details.

## Technologies Used
- **ASP.NET MVC**
- **C#**
- **Razor View Engine**


## Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-repo-url.git
   ```
2. **Open in Visual Studio** and build the project.
3. **Run the application** (Press `F5` or click on `Start`).

## How It Works
### 1️⃣ Model (`Product.cs`)
```csharp
public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public double Price { get; set; }
}
```
### 2️⃣ Controller (`ProductController.cs`)
```csharp
public class ProductController : Controller
{
    public ActionResult Index()
    {
        List<Product> productList = new List<Product>
        {
            new Product { Id = 1, Name = "Laptop", Price = 50000 },
            new Product { Id = 2, Name = "Mobile", Price = 20000 }
        };
        return View(productList);
    }
}
```
## License
This project is **free to use** and open-source under the MIT license.

## Author
Hira Hiwarkar

