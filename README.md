# **Tarif Rehberi Uygulaması**

Tarif Rehberi, kullanıcıların yemek tariflerini saklayabileceği, mevcut malzemelerle hangi yemeklerin yapılabileceğini görebileceği bir masaüstü uygulamasıdır. Uygulama, **C# ve WPF** kullanılarak geliştirilmiş olup dinamik arama, filtreleme, tarif önerme ve maliyet hesaplama gibi işlevleri desteklemektedir.

---

## **Proje Özellikleri**  

**Dinamik Arama ve Filtreleme**  
- Tarif adına veya içerdiği malzemeye göre arama yapabilirsiniz.  
- Tarifleri hazırlama süresi, maliyet ve içerdiği malzeme sayısına göre filtreleyebilirsiniz.

**Tarif Yönetimi**  
- Yeni tarifler ekleyebilir, güncelleyebilir veya silebilirsiniz.  
- Tariflere malzemeleri ve miktarlarını ekleyebilirsiniz.  
- Tarifin tekrar eklenmesini önlemek için duplicate kontrolü yapılır.

**Malzeme Yönetimi**  
- Kullanıcı, tarif eklerken yeni malzemeler oluşturabilir veya kayıtlı malzemeleri seçebilir.  
- Malzemelerin stok miktarı ve birim fiyatı veritabanında saklanır.  

**Tarif Önerisi**  
- Malzemelerinize göre hangi tarifleri yapabileceğinizi öğrenebilirsiniz.  
- Eksik malzemesi olan tarifler kırmızı, tam malzemesi olanlar yeşil renkte gösterilir.  
- Eksik malzemelerin toplam maliyetini hesaplayarak görüntüleyebilirsiniz.  

---

## **Kullanılan Teknolojiler**  

- **Programlama Dili:** C#  
- **Geliştirme Ortamı:** Visual Studio
- **Veritabanı:** Microsoft SQL Server  

---

## **Kurulum ve Çalıştırma**  

### **1. Projeyi Klonlayın**  

Aşağıdaki komutları terminal veya komut istemcisine girerek projeyi klonlayın:  

```sh
git clone https://github.com/Esentrn/RecipeApp.git
cd Recipe-Guide
```

### **2. Uygulamayı Çalıştırın**  

Visual Studio'da `F5` tuşuna basarak veya terminalde aşağıdaki komutu çalıştırarak uygulamayı başlatabilirsiniz:  

```sh
dotnet run
```

---

## **Ekran Görüntüleri**  

![Resim](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp1.png)

![Resim](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp2.png)

![Resim](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp3.png)

![Resim](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp4.png)

![Resim](https://github.com/Esentrn/RecipeApp/blob/d44e9d86c2c8f37f249e878853ca58f73f8847a2/RecipeApp5.png)
