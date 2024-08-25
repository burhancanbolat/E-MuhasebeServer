# Clean Architecture

ASP.NET Core için Clean Architecture başlangıç projesi. [Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html) loosely-coupled, dependency-inverted architecture mimarisine yönelik bir dizi mimarinin sonuncusu. [Hexagonal](http://alistair.cockburn.us/Hexagonal+architecture), [ports-and-adapters](http://www.dossier-andreas.net/software_architecture/ports_and_adapters.html), or [onion architecture](http://jeffreypalermo.com/blog/the-onion-architecture-part-1/) diye de adlandırıldığını duyabilirsiniz.

## Table Of Contents

- [Clean Architecture](#clean-architecture)  
  - [Table of contents](#table-of-contents)
  - [Give a start! :star:](#give-a-star-star)
  - [Versions](#versions)
  - [Getting Started](#getting-started)



## Versions

Proje şu anda .NET 8 versiyonunu kullanıyor. Eski versiyonlarda desteği yok.




## Projede kullanılan kütüphaneler
- **EntityFrameworkCore**
- **EntityFrameworkCore.Identity**
- **MediatR**
- **AutoMapper**
- **FluentValidation**
- **TS.Result**
- **TS.EntityFrameworkCore.GenericRepository**

Proje başlangıçta PostgreSql ile ayarlandı. PostgreSql ile devam etmek istiyorsanız `appsetting.json` dosyasında ConnectionStrings kısmını kendinize göre düzenleyin



Eğer Database değiştirmek istiyorsanız kurulu NuGet package'ini Infrastructure katmanında değiştirip connection bilgisini değiştirmelisiniz.

Login metodu ve User classı projede mevcut.
Proje çalıştığında otomatik bir admin kullanıcısı oluşturur





