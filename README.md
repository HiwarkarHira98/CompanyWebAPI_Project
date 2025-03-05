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
﻿namespace CompanyApiJwt.Model
{
    public class LoginModel
    {
      
            public required string Username { get; set; }
            public required string Password { get; set; }
        
    }
}
---------------------------------------------------------------------------------------
using System.ComponentModel.DataAnnotations;
namespace CompanyApiJwt.Model
{
    public class Company
    { 
        public required string CompanyName { get; set; }
        public required string CompanyAddress { get; set; }
        public required string CompanyGSTN { get; set; }
        public required string CompanyCode { get; set; }
        public required string CompanyUserId { get; set; }
        public required string CompanyStatus { get; set; }
        public DateTime CompanyStartDate { get; set; }
        public required string CompanyNatureOfWork { get; set; }
    }
}

```

## License
This project is **free to use** and open-source under the MIT license.

## Author
Hira Hiwarkar

