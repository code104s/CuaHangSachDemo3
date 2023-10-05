﻿#Demo asp.net

##Install packages
- EntityFramework (design,sqlserver,tools)


## Database
 - Sử dụng Fluent API để config Entities
 - Migration database ( di chuyen database )
     Cai dat : - Microsoft.Extensions.Configuration.Json - Microsoft.Extensions.Configuration.FileExtensions

   + Package Manager Console: Add-Migration InitialCreate -context shopDbcontext
                              update-database -context shopDbcontext
 - Seeding data
 - add bang identity : + install:  Microsoft.AspNetCore.Identity.EntityFramewo
 - Xây dựng cấu trúc phân tầng Application : folder catalog - products 
  + Tao interface - product
  + Tao phuong thuc phan search va phan trang : 
 - Phuong thuc quan li anh Image #16 AddImages , RemoveImages , UpdateImages , GetListImage
 - Tao API Project : BackendApi #17
 - Tao Swagger cho web Api (Hoc Resful Api) 
     + Install : Swashbuckle.AspNetCore.Swagger 
                 Swashbuckle.AspNetCore.SwaggerUI
                 washbuckle.AspNetCore.SwaggerGen
 - Tao Resful Api cho Product
 - Tao Api quan li Anh
 - Tạo API đăng nhập và đăng kí : login jwt
     + Tao API : usercontroller
 - Them Authorization header cho swagger ( Bao ve API de su dung Token)
 ## Admin App
 - template : https://startbootstrap.com/template/sb-admin
 - Tich hop api 
 - 26: Cookie Authentication va Login Logout
 - 27: Lay danh sach user : add Microsoft.AspNetCore.Session