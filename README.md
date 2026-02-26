# 🧰 Larenea Toolkit

## 🇹🇷 TÜRKÇE

**Larenea Toolkit**, Blender için geliştirilmiş, üretim sürecini
hızlandırmaya yönelik küçük ama etkili araçlardan oluşan bir add-on
paketidir.

Add-on, Blender'ın N Paneli üzerinden erişilebilir ve özellikle karakter
üretimi, retopoloji, sahne yönetimi ve grid tabanlı sistemler üzerinde
çalışırken zaman kazandırmayı amaçlar.

------------------------------------------------------------------------

## 🔹 İçerik

### 🧩 Mesh Data Transfer

Seçilen kaynak objenin fiziksel mesh verisini hedef objeye belirli
metodlarla transfer etmeye olanak sağlar.

Kullanım amaçları: - High poly (özellikle Marvelous Designer çıktısı,
UV'si açılmış meshler) modellerin UV bilgilerini kopyalayarak low poly
versiyon üretmek - Retopoloji sürecini hızlandırmak - Organik olmayan
modeller ve animasyon varlıklarında veri transferi yapmak

Ek Özellik: - Seçili vertexlerin UV layout'unu 3D space içerisinde yeni
bir mesh olarak oluşturan bir buton içerir. - UV layout 3D uzayda
fiziksel olarak düzenlenebilir hale gelir. - Retopo ve UV düzeltme
işlemleri daha kolay yapılabilir.

------------------------------------------------------------------------

### 🎭 Blendshape Randomizer

Seçili mesh üzerindeki blendshape (Shape Key) değerlerini rastgele
üretmeye yarayan bir araçtır.

Özellikler: - Prefix (ön ek) bazlı shapekey filtreleme - Minimum ve
maksimum değer aralığı belirleme - Belirtilen prefix ile başlayan tüm
shapekey'leri random üretme

Bu sistem, karakter creation sürecinde demo üretmek için
geliştirilmiştir. Özellikle facial yapıların rastgele üretilmesi ve
farklı etnik karakter varyasyonlarının hızlı test edilmesi amacıyla
kullanılmıştır.

------------------------------------------------------------------------

### 🧱 Grid Generator

Seçili obje referans alınarak: - Belirlenen row (satır) ve column
(sütun) sayısında - Tanımlanan scale değerinde

otomatik grid üretir.

Grid tabanlı map sistemleri için geliştirilmiştir. Oluşturulan objeler
otomatik ve sistemli şekilde isimlendirilir.

------------------------------------------------------------------------

### 🏷 Mesh Name Sync

Blender'da mesh isimlerini obje isimleriyle senkronize eder.

Bir objenin adı değiştirildiğinde: - O objeye ait mesh data adı da
otomatik olarak güncellenir.

Bu araç özellikle düzenli proje yapısı oluşturmak için geliştirilmiştir.

------------------------------------------------------------------------

### 🎥 Main Camera Switcher

Sahnedeki tüm kameraları listeleyen ve aralarında hızlı geçiş yapmayı
sağlayan bir araçtır.

Özellikler: - Kamera listesi üzerinden doğrudan geçiş - Ctrl + Shift +
Sağ Ok / Sol Ok ile sıralı geçiş - Seçilen kamerayı aktif kamera yapma

Özellikle araç çekim animasyonları ve çok kameralı sahne çalışmalarında
kullanılmıştır.

------------------------------------------------------------------------

### 🧷 Vertex Group Batch Rename

Vertex gruplarını toplu olarak yeniden adlandırmaya yarar.

Özellikler: - Sadece eşleşen kısmı değiştirme - Tüm ismi değiştirme -
Pattern bazlı yeniden adlandırma

Özellikle Mixamo karakterleriyle gelen "mixamo" prefix'li vertex
gruplarını hızlıca düzenlemek ve kendi rig sistemine uyarlamak için
geliştirilmiştir.

------------------------------------------------------------------------

## 🇺🇸 EN

**Larenea Toolkit** is a Blender add-on package consisting of small but
powerful tools designed to speed up production workflows.

The add-on is accessible from Blender's N Panel and focuses on character
creation, retopology, scene management, and grid-based systems.

------------------------------------------------------------------------

### 🧩 Mesh Data Transfer

Allows transferring mesh data from a selected source object to a target
object using specific methods.

Primary use cases: - Copying UV data from high-poly meshes (especially
Marvelous Designer outputs) to create low-poly versions - Speeding up
retopology workflows - Transferring data for non-organic models and
animation assets

Additional Feature: - Generates selected vertex UV layout as a new mesh
in 3D space. - Enables physical editing of UV layouts directly in 3D. -
Makes retopology and UV correction more intuitive.

------------------------------------------------------------------------

### 🎭 Blendshape Randomizer

Randomizes blendshape (Shape Key) values of the selected mesh.

Features: - Prefix-based shapekey filtering - Minimum and maximum value
range definition - Random generation for all shapekeys matching the
given prefix

Developed for character creation demos, particularly for generating
random facial structures and testing ethnic variations.

------------------------------------------------------------------------

### 🧱 Grid Generator

Generates a grid based on the selected object:

-   Custom row and column count
-   Defined scale value

Created for grid-based map systems. Objects are automatically and
systematically named.

------------------------------------------------------------------------

### 🏷 Mesh Name Sync

Synchronizes mesh data names with object names.

When an object name changes: - The corresponding mesh data name updates
automatically.

Designed to maintain clean and organized project structures.

------------------------------------------------------------------------

### 🎥 Main Camera Switcher

Lists all cameras in the scene and allows quick switching between them.

Features: - Direct selection from list - Ctrl + Shift + Right / Left
arrow navigation - Automatically sets selected camera as active

Used especially for vehicle cinematics and multi-camera animation
setups.

------------------------------------------------------------------------

### 🧷 Vertex Group Batch Rename

Allows batch renaming of vertex groups.

Features: - Replace only matching segments - Replace entire names -
Pattern-based renaming

Particularly useful for quickly modifying Mixamo-generated vertex groups
and adapting them to custom rig systems.

------------------------------------------------------------------------

Larenea Toolkit is a production-oriented Blender utility collection
built to eliminate repetitive tasks and accelerate workflow efficiency.
