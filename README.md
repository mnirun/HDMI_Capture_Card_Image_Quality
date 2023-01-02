# HDMI Capture Card Image Quality
HDMI Capture Card Image Quality

- ความเป็นมาและวัตถุประสงค์
- ความรู้เบื้องต้น
  - Image quality
  - Colorspace
  - Chroma subsampling
  - Pixel format
  - Scaler
  - Splitter
  - Extractor
  - USB 3.0 / 3.1 / 3.2 ?
  - Uncompressed video data rates
- อุปกรณ์และโปรแกรมที่ใช้ทดสอบ
  - อุปกรณ์
  - โปรแกรม
- การทดสอบ
  - Latency test
  - Framerate test
    - Data rate checking
  - Image test
  - Temperatute test
  - Reliability test
- สรุปการทดสอบ
  - การเลือกใช้งาน
- ข้อมูลอ้างอิง

## ความเป็นมาและวัตถุประสงค์

## ความรู้เบื้องต้น

### Image quality

#### Subjective method

Double stimulus

##### NVIDIA ICAT

#### Objective method

 - SSIM
 - HCL: Luminance
 - HCL: Chroma

##### ImageMagick

### Colorspace

 - RGB (Red, Green, Blue)
 - HCL (Hue, Chroma, Luminance)

### Chroma subsampling

 - 4:4:4
 - 4:2:2
 - 4:2:0

### Pixel format

 - MJPEG (4:2:0)
 - NV12 (4:2:0)
 - YUYV422 (4:2:2)

### Scaler

### Splitter

HDMI video splitter

### Extractor

HDMI audio extractor

### USB 3.0 / 3.1 / 3.2 ?

|ชื่อปัจจุบัน|ชื่อก่อนหน้า (ชื่อแรกสุด)|เลนคู่|ความเร็ว (Gbps)|การเชื่อมต่อ|
|---|---|---|---|---|
|USB 3.2 Gen 1x1|USB 3.1 Gen 1 (USB 3.0)|:x:|5|USB-A, B, micro B, USB-C|
|USB 3.2 Gen 2x1|USB 3.1 Gen 2 (USB 3.1)|:x:|10|USB-A, B, micro B, USB-C|
|USB 3.2 Gen 1x2|(USB 3.2)|:heavy_check_mark:|10|USB-C|
|USB 3.2 Gen 2x2|(USB 3.2)|:heavy_check_mark:|20|USB-C|


### Uncompressed video data rates


 - Data rates = [resolution](https://en.wikipedia.org/wiki/Display_resolution) × [color depth](https://en.wikipedia.org/wiki/Color_depth) × [frames per second](https://en.wikipedia.org/wiki/Frame_rate)
   - [Resolution](https://en.wikipedia.org/wiki/Display_resolution) = width × height
   - [Color depth](https://en.wikipedia.org/wiki/Color_depth) = bits per channel × [color channels](https://en.wikipedia.org/wiki/Channel_(digital_image)) × chroma ratio
     - Chroma ratio = (chroma subsampling Y + chroma subsampling Cb + chroma subsampling Cr) / 12
 - Integer Overflow/Wraparound

## อุปกรณ์และโปรแกรมที่ใช้ทดสอบ

### HDMI capture card

  - [ACASIS 4K HDMI Video Capture Card - HD33](https://www.acasis.com/collections/acasis-capture-card/products/acasis-4k-type-c-to-hdmi-compatible-video-capture-card-1080p-game-capture-card-recorder-box-device-for-live-streaming)
  - [ACASIS USB 3.0 SDI/HDMI Capture Card - AC-U3SDH](https://www.aliexpress.com/i/1005001929814532.html)
  - [Apogee HDMI Capture USB 3.0 - HV-HCA12](https://www.digital2home.com/apogee-hdmi-capture-usb-3.0-hv-hca12)
  - [AVerMedia Live Streamer CAP 4K - BU113](https://www.avermedia.com/en/product-detail/bu113)
  - [ezcap CAM LINK 4K - ezcap331](https://www.ezcap.com/index.php/product/ezcap331camlink4k.html)
  - [HAGiBiS Video Capture Card - THB01](http://www.hagibis.com.cn/video-capture-card-p00193p1.html)
  - [Rullz MS2130 HDMI Video Capture 4K 30Hz U3](https://www.aliexpress.com/i/1005004883158574.html)

#### ACASIS 4K HDMI Video Capture Card - HD33

![ACASIS_HD33](images/device/ACASIS_HD33.png)

 - USB 2.0
 - [MacroSilicon MS2109](http://en.macrosilicon.com/info.asp?base_id=2&third_id=50)
 - HDMI passthrough
 - Line-in

#### ACASIS USB 3.0 SDI/HDMI Capture Card - AC-U3SDH

![ACASIS_U3SDH](images/device/ACASIS_U3SDH.png)

  - USB 3.2 Gen 1x1
  - UVA & UVC
  - Lattice Sil9293CNUC MHL/HDMI Receiver
  - [Lattice ECP3-17 FPGA](https://www.latticesemi.com/en/Products/FPGAandCPLD/LatticeECP3)
  - [FTDI FT602Q-B FIFO to UVC Class SuperSpeed USB3.0](https://ftdichip.com/products/ft602q-b/)
  - [Genesys Logic GL3523 USB 3.1 Gen 1 Controller](https://www.genesyslogic.com.tw/en/product_view.php?show=67)
  - [Solid State System SSS1600 USB Line-in Controller](http://www.3system.com.tw/en-global/product/productDetail/65)
  - [TYSTVideo 2 Channel SDI+HDMI Video Capture Box - TY-U3SDH](http://www.tystvideo.com/en/product_detail/172/419.html)

#### Apogee HDMI Capture USB 3.0 - HV-HCA12

![Apogee_HV](images/device/Apogee_HV-HCA12.png)

 - USB 3.2 Gen 1x1
 - MStar Semiconductor MST097B
 - [EtronTech EJ511](https://www.eevertech.com/product_d.php?lang=en&tb=1&id=1045)
 - HDMI passthrough
 - Line-out
 - [CreHiVi HV-HCA12](http://www.hi-video.com.cn/Crehivi/pro/Video_Capture/2018/0910/119.html)
 - [USB-Capture-Card-Reversing](https://github.com/ArsenioDev/USB-Capture-Card-Reversing)
 - [Razer Ripsaw HD Review](https://www.weistang.com/thread-115925-1-1.html)

#### AVerMedia Live Streamer CAP 4K - BU113

![AVerMedia_BU113](images/device/AVerMedia_BU113.png)

  - USB 3.2 Gen 1x1
  - SDR 3840x2160@30fps
  - SDR 1920x1080@60fps
  - HDR 1920x1080@60fps
  - [AVerMedia Live Streamer CAP 4K Review (BU113) – So Much More Than a Cam Link!](https://streamguides.gg/2021/10/avermedia-live-streamer-cap-4k-review-bu113-so-much-more-than-a-cam-link/)

#### ezcap CAM LINK 4K - ezcap331

![ezcap_ezcap331](images/device/ezcap_ezcap331.png)

  - USB 3.2 Gen 1x1
  - NV12 3840x2160@30fps
  - NV12 1920x1080@120fps
  - [GERA SOLO](https://gera.ltd/gera-solo-pocket-4k-hdmi-to-usb3-1-capture-card/)
  - [Pyle PLINK2](https://www.pyleaudio.com/sku/PLINK2/Camera-Link-4K-USB31-GEN-HDMI-Video-Capture-Device---Live-Streaming-Record-Capture,-USB-31-GEN1-Video-Recording)

#### HAGiBiS Video Capture Card - THB01

![HAGiBiS_THB01](images/device/HAGiBiS_THB01.png)

  - USB 2.0
  - [MacroSilicon MS2109](http://en.macrosilicon.com/info.asp?base_id=2&third_id=50)
  - HDMI passthrough
  - Line-out

#### Rullz MS2130 HDMI Video Capture 4K 30Hz U3
 
 ![Rullz_MS2130](images/device/Rullz_MS2130.png)
 
  - USB 3.2 Gen 1x1
  - [MacroSilicon MS2130](http://www.ultrasemi.com/index.php/td-3-48-72-446)
  - YUY2 1920x1080@60fps
  - MJPEG 1290x1080@60fps

### อุปกรณ์อื่น ๆ

  - [UGREEN HDMI splitter 1x2](https://www.amazon.com/dp/B0B129NNV1 )
  - [Infiray T2L USB-C thermal camera](https://www.infiray.com/products/t2s-t2l-thermal-camera-for-smartphone.html)

### แผ่น Blu-ray

  - [Super HiVi CAST](https://web.archive.org/web/20200215085853/http://www.hivicast.jp/detail/shvc_00_en.html)
  - [FPD Benchmark Software](https://www.phileweb.com/editor/av-review/157/special.html)
  - [Hi-Definition Reference Software](https://www.qtec.ne.jp/technology/hdrs/)
  - [Blade Runner 2049](https://www.amazon.com//dp/B07VFN6WLH/)
  - [TENET](https://www.amazon.com/dp/B08MHRRKW7/)
  - [The Meg](https://www.amazon.com/dp/B07D512BDG/)
  - [Oblivion](https://www.amazon.com/dp/B07KLCVVV9/)
  - [E235系山手線 4K撮影作品【ブルーレイ】](http://vicom.jp/shopdetail/000000001360)
  - [Train Night View 夜の山手線 4K撮影作品【ブルーレイ】](http://vicom.jp/shopdetail/000000001361)
  - [世界自然遺産 小笠原 ～ボニンブルーの海～【ブルーレイ】](http://vicom.jp/shopdetail/000000001359/)
  - [さくら 春を彩る華やかな桜のある風景 4K撮影作品【ブルーレイ】](http://vicom.jp/shopdetail/000000001342/)
  - [Hello World](https://www.amazon.com/dp/B083WCFCHV/)
  - [In This Corner of The World](https://www.amazon.com/dp/B072ZDZYKM/)
  - [Kimagure Orange Road](https://www.discotekmedia.com/Kimagure-Orange-Road-Complete-Blu-ray.htm)

### โปรแกรม

  - [mpv](https://mpv.io/) + [mpv-settings](https://github.com/Tsubajashi/mpv-settings)
  - [FFmpeg](https://ffmpeg.org/)
  - [HyperHDR](https://github.com/awawa-dev/HyperHDR)
  - [PotPlayer](https://potplayer.daum.net/)
  - [trdrop](https://github.com/cirquit/trdrop)
  - [ImageMagick](https://www.imagemagick.org/)
  - [NVIDIA Image Comparison & Analysis Tool (ICAT)](https://www.nvidia.com/en-us/geforce/technologies/icat/)
  - [mono-to-stereo](https://github.com/ToadKing/mono-to-stereo), [mono-to-stereo-gui](https://github.com/ndekopon/mono-to-stereo-gui)

## การทดสอบ

### Latency test

#### Video latency test

HyperHDR

#### Audio latency test

TBD

### Framerate test

  - PotPlayer
  - trdrop

#### Data rate checking

### Image test

  - Objective test
    - Similarity

      |SSIM|MOS|คุณภาพ (Quality)|
      |---|---|---|
      |≥0.99|5|ยอดเยี่ยม (Excellent)|
      |≥0.95 & <0.99|4|ดี (Good)|
      |≥0.88 & <0.95|3|พอใช้ (Fair)|
      |≥0.50 & <0.88|2|ไม่ดี (Poor)|
      |<0.50|1|แย่ (Bad)|

      MOS = [Mean opinion score](https://en.wikipedia.org/wiki/Mean_opinion_score)

    - Exposure
  - Subjective test
    - NVIDIA ICAT

### Temperatute test

  - Operating temperature
  - Infiray T2L test

### Reliability test

interval capture test with ffmpeg

## สรุปการทดสอบ

![HDMI_01_Video_Latency](images/result/HDMI_01_Video_Latency.png)

![HDMI_02_Video_Quality](images/result/HDMI_02_Video_Quality.png)

![HDMI_03_Contact_Sheet](images/result/HDMI_03_Contact_Sheet.jpg)

 - การเลือก HDMI capture card
   - MS2109 budget friendly
   - 4K input/output ?
   - Pixel format ?
   - Color accuracy ?

## ข้อมูลอ้างอิง
 - [USB 3.0](https://en.wikipedia.org/wiki/USB_3.0)
 - [A Novel Methodology for Mapping Objective Video Quality Metrics to the Subjective MOS Scale](https://ieeexplore.ieee.org/abstract/document/6873572/)
 - [NON-EXPERTS OR EXPERTS? STATISTICAL ANALYSES OF MOS USING DSIS METHOD](https://repositori.upf.edu/bitstream/handle/10230/45507/sugito_icassp_nonex.pdf?sequence=1&isAllowed=y)
