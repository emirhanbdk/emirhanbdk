## Emirhan Budak
**Elektrik-Elektronik Mühendisi** · Gömülü Sistemler · Elektronik Kart Tasarımı · Görüntü İşleme

Uluefe Elektrik'te Gökçepınar RES projesinde elektrik-elektronik mühendisi olarak
şantiye şefliği yapıyorum. Gömülü yazılım (STM32), PCB tasarımı (KiCad) ve kısıtlı
donanımda görüntü işleme üzerine projeler geliştiriyorum.

Donanım ile yazılımın kesiştiği problemlerle ilgileniyorum: bir güç katının ölü zamanını
ayarlamak ile sınırlı bir GPU'da nesne tespit modelini verimli çalıştırmak bana göre aynı
mühendislik disiplinini gerektiriyor.

### Projeler

| Proje | Kapsam | Sonuç |
| :--- | :--- | :--- |
| [PCB-Vision AI](https://github.com/emirhanbdk/pcb-vision-ai) | Yüksek çözünürlüklü PCB görüntülerinde 22 sınıf bileşen tespiti (YOLOv8 + dilimlenmiş çıkarım) | mAP@50 %64,2 (başlangıç modeline göre +14,8 puan) |
| [30 W Senkron Buck](https://github.com/emirhanbdk/senkron-buck-30w) | 21 V → 15 V / 2 A DC-DC çevirici; IR2110, STM32F103 PWM, KiCad çift katman PCB | LTspice'ta tam yükte %93,65 verim; kart el yapımı olarak üretildi |
| [Hibrit Enerji Boyutlandırma](https://github.com/emirhanbdk/hibrit-enerji-gpa) | PV / rüzgâr / batarya sisteminin Gradient Pelican Algoritması ile maliyet optimizasyonu (MATLAB) | LPSP ≤ %5 kısıtı altında en düşük NPC |

Diğer çalışmalar: Jetson üzerinde nesne tanıma (İKA), ROS2/Gazebo ile GNSS'siz otonom
navigasyon, IoT çevresel izleme (TEKNOFEST, takım kaptanı).

### Araçlar

**Gömülü ve donanım:** STM32 (HAL, CubeIDE), C, KiCad, LTspice, Proteus  
**Yapay zekâ ve yazılım:** Python, PyTorch, YOLOv8, OpenCV, FastAPI, ROS2  
**Diğer:** MATLAB/Simulink, Git

### İletişim

[LinkedIn](https://www.linkedin.com/in/emirhanbudak)
