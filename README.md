# WEATHER APP with CLOMOSY (Mobile)


This project is an **interactive mobile weather application** developed using the **Clomosy** platform. The app allows users to enter a city name, fetches real-time weather data from **WeatherAPI**, and changes the background image and ambient sounds based on the current weather. It also features motion-sensor interactivity for a more dynamic user experience.

Bu proje, **Clomosy** platformu kullanılarak geliştirilen etkileşimli bir **mobil hava durumu uygulamasıdır**. Uygulama kullanıcıdan şehir ismi alır, **WeatherAPI** üzerinden anlık hava durumu verilerini çeker ve mevcut hava durumuna göre arka plan resmini ve ses efektlerini değiştirir. Ayrıca cihaz eğildiğinde arka plan görseli sağa-sola hareket eder.

---

## 🎮 Features / Özellikler

- 🌐 Real-time weather data by city  
  _Şehre göre anlık hava durumu verisi_

- 🖼️ Background image updates based on weather  
  _Hava durumuna göre değişen arka plan_

- 🔊 Ambient sounds for sunny, rainy, cloudy, and clear weather  
  _Güneşli, yağmurlu, bulutlu ve açık havaya özel ses efektleri_

- 📱 Interactive background that moves with device tilting  
  _Cihaz eğimine duyarlı dinamik arka plan_

---

## 🛠️ Technologies Used / Kullanılan Teknolojiler

| Technology | Description |
|-----------|-------------|
| **Clomosy** | Visual scripting-based mobile/game interface platform |
| **WeatherAPI** | Real-time weather data provider [(weatherapi.com)](https://www.weatherapi.com/) |
| **JSON Parsing** | To extract weather details from the API response |
| **Device Motion Sensor** | Used to animate background image based on phone tilt |

| Teknoloji | Açıklama |
|-----------|----------|
| **Clomosy** | Görsel kodlama tabanlı mobil/oyun arayüz geliştirme platformu |
| **WeatherAPI** | Gerçek zamanlı hava durumu verisi sağlayıcısı [(weatherapi.com)](https://www.weatherapi.com/) |
| **JSON Ayrıştırma (Parsing)** | API'den gelen hava durumu verilerini çıkarmak için |
| **Cihaz Hareket Sensörü** | Cihazın eğilmesine göre arka plan görselini hareket ettirmek için kullanılır |


---

## 🖼️ Screens & Assets / Ekranlar ve Varlıklar

| Weather       | Background Preview | Sound |
|---------------|--------------------|-------|
| **Sunny**     | ![Sunny](<img src="https://github.com/the15developer/WEATHER-MOBILE-APP-CLOMOSY/blob/main/sunny.jpeg" alt="Sunny" width="300"/>) | Sunny ambient |
| **Rainy**     | ![Rainy](https://github.com/the15developer/WEATHER-MOBILE-APP-CLOMOSY/blob/main/rainy.jpeg) | Rain sound |
| **Cloudy**    | ![Cloudy](https://github.com/the15developer/WEATHER-MOBILE-APP-CLOMOSY/blob/main/cloudy.jpeg) | Cloudy |
| **Clear**     | ![Clear](https://github.com/the15developer/WEATHER-MOBILE-APP-CLOMOSY/blob/main/clear.jpeg) | Clear |

---

## 🚀 How It Works / Nasıl Çalışır?

1. User enters a city name in the input field.
2. Presses the `GET` button.
3. The app fetches:
   - City, country, temperature, condition.
4. The UI displays this data and:
   - Updates the background image according to weather.
   - Plays a corresponding ambient sound.
   - Enables motion-based background shifting (left/right).
  
1. Kullanıcı, giriş alanına bir şehir adı yazar.  
2. `GET` butonuna basar.  
3. Uygulama aşağıdaki verileri çeker:  
   - Şehir, ülke, sıcaklık, hava durumu açıklaması.  
4. Arayüz bu verileri gösterir ve:  
   - Hava durumuna uygun arka plan görselini günceller.  
   - Uygun ortam sesini çalar.  
   - Cihazın sağa/sola eğilmesine göre arka planı hareket ettirir.


---

## 📦 Installation / Kurulum

1. Open **Clomosy** on developer account.
2. Import or copy this project’s Clomosy script.
3. Get a free API key from [WeatherAPI](https://www.weatherapi.com/).
4. Paste the key into the `getClick` function's URL string.
5. Deploy the code and open the app on phone (user account). 


1. Geliştirici hesabınızla **Clomosy** platformunu açın.  
2. Bu projeye ait Clomosy betiğini içe aktarın veya kopyalayın.  
3. [WeatherAPI](https://www.weatherapi.com/) sitesinden ücretsiz bir API anahtarı alın.  
4. Aldığınız anahtarı `getClick` fonksiyonundaki URL string’ine yapıştırın.  
5. Kodu yayınlayın ve uygulamayı telefonunuzda (kullanıcı hesabı ile) açın.

---

## 🧠 What I Learned / Öğrendiklerim

- Designing interactive mobile UIs with Clomosy.
- Parsing JSON weather data.
- Using REST APIs in mobile applications.
- Device sensor integration for enhanced user interactivity.
- Combining visuals and audio for immersive weather feedback.

- Clomosy ile etkileşimli mobil kullanıcı arayüzleri tasarlamak.  
- JSON hava durumu verilerini ayrıştırmak.  
- Mobil uygulamalarda REST API’leri kullanmak.  
- Gelişmiş kullanıcı etkileşimi için cihaz sensörlerini entegre etmek.  
- Görsel ve işitsel ögeleri birleştirerek etkileyici bir hava durumu deneyimi sunmak.


---

## 📜 License

This project is developed for personal and educational use only.  
Bu proje yalnızca eğitim ve kişisel kullanım amaçlı geliştirilmiştir.

---

