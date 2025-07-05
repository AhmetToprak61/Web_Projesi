# Büyük Projem

Bu proje çok büyük olduğu için Google Drive üzerinden indirilebilir:

📥 [Projeyi İndir (Google Drive)](https://drive.google.com/drive/folders/172n2ob75sFsFR0TbtLoGQ4NZwhhJddFt?usp=sharing)
Bu dosya Google Drive linki içerir.


# Traversal Core Projesi

Bu proje, Murat Yücedağ'ın Traversal serisine dayalı olarak geliştirilmiş, .NET 6 ile yazılmış katmanlı mimariye sahip bir ASP.NET Core web projesidir. Projede SignalR, WebAPI, DTO yapıları ve çeşitli admin/user panelleri yer almaktadır.

## 🔧 Kullanılan Teknolojiler

- ASP.NET Core 6
- Entity Framework Core
- SignalR
- MSSQL Server
- Katmanlı Mimari (EntityLayer, DataAccessLayer, BusinessLayer, DTOLayer)
- API Tüketimi ve Üretimi

## 🚀 Projeyi Çalıştırma Adımları

1. **Projeyi Klonlayın:**

```bash
git clone https://github.com/kullaniciadi/traversalcoreproje.git


2.Visual Studio ile açın:
  TraversalCoreProje.sln dosyasını açın.

3.Veritabanı bağlantısını ayarlayın:
  TraversalCoreProje/appsettings.json dosyasındaki connection string'i kendi SQL Server bağlantınıza göre düzenleyin:
************
"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=TraversalDb;Trusted_Connection=True;"
}
************
4.Migration ve Veritabanı Oluşturma (Opsiyonel):

  Eğer EF Core Migrations varsa, Package Manager Console'da:
************
Update-Database
************
Örnek Giriş Bilgileri:
Email: admin@example.com
Şifre: 1234