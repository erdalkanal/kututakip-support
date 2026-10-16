# Privacy Policy for Stock & Box Tracker (Stok Takip: Kutu & Envanter)

**Effective Date:** October 3, 2026  
**Last Updated:** October 16, 2026  
**Application Name:** Stock & Box Tracker / Stok Takip: Kutu & Envanter  
**iOS Bundle ID:** `com.kututakip.app`  
**Android Package Name:** `com.kututakip.market`  
**Developer:** Erdal Kanal  

---

## 1. Overview & Core Philosophy

**Stock & Box Tracker** ("the App", "we", "our", or "us") is developed with a strict **Privacy-First** and **Offline-First** architecture for both **iOS (Apple App Store)** and **Android (Google Play Store)**. We believe that your workshop, home, and warehouse inventory data belongs solely to you.

- We do **NOT** require any user account, registration, login, or email address.
- We do **NOT** operate any central cloud database that collects, stores, or analyzes your personal inventory items, photos, or records.
- All inventory data, box names, parts, QR codes, and settings remain stored **exclusively on your local device**.

---

## 2. Information We Collect (or Do Not Collect)

### 2.1 Personal Data
The App does **not** collect, store, sell, or transmit any personally identifiable information (PII) such as your name, email address, phone number, physical address, or financial details.

### 2.2 Inventory and Box Data
Any text, numbers, categories, prices, or descriptions you enter regarding your boxes, shelves, components, and tools are stored strictly within the local application sandbox database (`AsyncStorage`) on your mobile device.

### 2.3 Camera and Photo Library
- **Camera (`NSCameraUsageDescription` / `CAMERA`):** The App requests access to your device camera solely to allow you to capture optional photos of your boxes and components or scan QR codes. Images are processed and stored locally on your device and are never uploaded to any external server.
- **Photo Library (`NSPhotoLibraryUsageDescription` / `READ_EXTERNAL_STORAGE`):** If you choose to attach existing photos from your gallery to your boxes or components, those images are compressed and saved locally on your device's internal storage and are never uploaded to any remote server.

---

## 3. Device Permissions and Why We Need Them

The App requests only the minimum permissions necessary to deliver its core features on iOS and Android:

| Permission | iOS Key / Android Name | Purpose |
| :--- | :--- | :--- |
| **Camera** | `NSCameraUsageDescription` / `android.permission.CAMERA` | Used exclusively for capturing optional item/box pictures locally and scanning box QR codes. |
| **Photo Library / Storage** | `NSPhotoLibraryUsageDescription` / `READ_EXTERNAL_STORAGE` | Used strictly when you attach an image from your gallery or export/import a local `.json` inventory backup file. |
| **App Tracking Transparency (iOS)** | `NSUserTrackingUsageDescription` | Used on iOS to ask your permission before Google AdMob delivers personalized ads. If declined, only non-personalized contextual ads are shown. |
| **Notifications** | `expo-notifications` / `POST_NOTIFICATIONS` | Used optionally for local reminders or low-stock alerts. |

You can review or revoke these permissions at any time through your device's iOS or Android system settings.

---

## 4. Third-Party Services, Advertising & In-App Purchases

To support the free version and maintain the application, the App integrates **Google AdMob SDK** for advertising and **Apple StoreKit / Google Play Billing** for optional PRO subscriptions:

- **Google AdMob:** [https://support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)
- **Google Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Apple Privacy Policy:** [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
- **Apple Standard EULA (Terms of Use):** [https://www.apple.com/legal/internet-services/itunes/dev/stdeula/](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)

These SDKs handle advertising and subscription transactions independently. On iOS, Google AdMob respects your **App Tracking Transparency (ATT)** choice. Upgrading to **PRO** completely disables all advertisements in the App. The App never shares your internal inventory data or box contents with Google, Apple, or advertising partners.

---

## 5. Auto-Renewable Subscriptions (PRO Version)

- **Subscription Name:** Stock Tracker PRO (Annual Subscription - `kututakip_pro_yearly`)
- **Billing & Renewal:** Payment is charged to your Apple ID or Google Play account at confirmation of purchase. The subscription automatically renews annually unless auto-renew is turned off at least 24 hours before the end of the current period.
- **Managing Subscriptions:** You can manage or cancel your subscription at any time in your **App Store Account Settings** (iOS) or **Google Play Subscriptions** (Android).

---

## 6. Data Security, Retention, and User Control

- **Complete Data Control:** You own 100% of your data. You can back up your inventory at any time using the built-in JSON export feature, or wipe everything immediately using the **"Reset & Delete All Local Data"** function in the App Settings.
- **Data Deletion:** Uninstalling the application or resetting data via the App's Settings immediately and permanently deletes all your local inventory records and settings.

---

## 7. Contact Us

If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us:

- **Support Center:** [https://github.com/erdalkanal/kututakip-support](https://github.com/erdalkanal/kututakip-support)
- **Support Tickets:** [https://github.com/erdalkanal/kututakip-support/issues](https://github.com/erdalkanal/kututakip-support/issues)
- **Email:** `erdalkanal@users.noreply.github.com`

---
---

# Gizlilik Politikası (Stok Takip: Kutu & Envanter)

**Yürürlük Tarihi:** 3 Ekim 2026  
**Son Güncelleme:** 16 Ekim 2026  
**Uygulama Adı:** Stok Takip: Kutu & Envanter / Stock & Box Tracker  
**iOS Bundle ID:** `com.kututakip.app`  
**Android Paket Adı:** `com.kututakip.market`  
**Geliştirici:** Erdal Kanal  

---

## 1. Genel Bakış ve Temel Gizlilik İlkesi

**Stok Takip: Kutu & Envanter** uygulaması, hem **iOS (Apple App Store)** hem de **Android (Google Play Store)** platformlarında kullanıcı gizliliğini en üst düzeyde korumak amacıyla **%100 Çevrimdışı (Offline-First)** ve **Gizlilik Odaklı** bir mimari ile geliştirilmiştir. Atölyeniz, deponuz ve çekmecelerinizdeki envanter verilerinin yalnızca size ait olduğuna inanıyoruz.

- Uygulama herhangi bir **üyelik, kayıt, e-posta veya kullanıcı girişi gerektirmez**.
- Kullanıcıların kutu ve envanter verilerini toplayan veya saklayan **merkezi bir bulut veritabanımız bulunmamaktadır**.
- Girdiğiniz tüm kutu bilgileri, komponentler, adetler, fotoğraflar, fiyatlar ve ayarlar **yalnızca kendi cihazınızda** yerel olarak saklanır.

---

## 2. Uygulama İzinleri ve Kullanım Amaçları

| İzin | iOS / Android Tanımı | Amaç |
| :--- | :--- | :--- |
| **Kamera** | `NSCameraUsageDescription` / `CAMERA` | Yalnızca kutu ve ürün fotoğrafı çekmek ve QR kodlarını okutmak için kullanılır. |
| **Fotoğraf Arşivi / Depolama** | `NSPhotoLibraryUsageDescription` / `READ_EXTERNAL_STORAGE` | Yalnızca galeriden ürün fotoğrafı seçmek veya envanterinizi `.json` dosyası olarak yedeklemek/geri yüklemek için kullanılır. |
| **Uygulama Takip Şeffaflığı (ATT)** | `NSUserTrackingUsageDescription` | iOS cihazlarda Google AdMob üzerinden ilgi alanınıza uygun reklam sunulabilmesi için izninizi ister. İzin verilmezse yalnızca genel reklamlar gösterilir. |
| **Bildirimler** | `POST_NOTIFICATIONS` | Yalnızca yerel kritik stok veya hatırlatıcı bildirimleri için kullanılır. |

---

## 3. Üçüncü Taraf Servisler, Reklamlar ve Abonelikler

Uygulamanın ücretsiz sürümünü desteklemek adına **Google AdMob** SDK'sı ve isteğe bağlı PRO abonelik işlemleri için **Apple StoreKit / Google Play Billing** altyapısı kullanılmaktadır:

- **Google AdMob:** [https://support.google.com/admob/answer/6128543](https://support.google.com/admob/answer/6128543)
- **Apple Standart Kullanım Koşulları (EULA):** [https://www.apple.com/legal/internet-services/itunes/dev/stdeula/](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)

PRO sürüme geçildiğinde uygulama içerisindeki tüm reklamlar tamamen kaldırılır. Envanter verileriniz hiçbir reklam ağıyla paylaşılmaz.

---

## 4. Veri Güvenliği ve Silme

- **Tam Veri Hakimiyeti:** Verilerinizin tek sahibi sizsiniz. Dilediğiniz an JSON formatında yedek alabilir veya Ayarlar menüsündeki **"Tüm Yerel Verileri Sıfırla ve Sil"** butonuyla tüm yerel veritabanını anında temizleyebilirsiniz.
- **Verilerin Silinmesi:** Uygulamayı cihazınızdan sildiğinizde veya uygulama içi sıfırlama yaptığınızda tüm yerel envanter verileriniz kalıcı olarak silinir.
