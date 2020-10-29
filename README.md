# # The Next Car
(Introduction)

Membuat Aplikasi dimana  sebuah program yang menerapkan konsep pola arsitektur yang memisahkan aplikasi dalam tiga komponen utama Logis: Model, View dan Controller.
## Scope of functionalities
-   User bisa menekan tombol  `STARTED/STOPPED`,  `OPENED/CLOSED`,  `LOCKED/UNCLOCKED`, dan  `ON/OFF`
-   User hanya bisa menekan `STARTED` ketika kondisi  "Close The Door, pintu sudah terkunci dan Aki sudah menyala"
## How does it works?
-   Terdapat folder Model yang berisikan class  `Door.cs`  dan  `AccuBattery.cs`
-   Terdapat`MainWindow.xaml`untuk menampilkan program
-   Terdapat folder Controller yang berisi class  `AccuBatteryController.cs`  `DoorController.cs`  dan  `Car.cs`
-   Terdapat class `MainWindow.xaml.cs` untuk function