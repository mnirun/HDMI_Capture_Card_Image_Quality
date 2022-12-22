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

  - [AVerMedia Live Streamer CAP 4K - BU113](https://www.avermedia.com/en/product-detail/bu113)
  - [ezcap CAM LINK 4K - ezcap331](https://www.ezcap.com/index.php/product/ezcap331camlink4k.html)
  - [HAGiBiS Video Capture Card - THB01](http://www.hagibis.com.cn/video-capture-card-p00193p1.html)
  - [ACASIS 4K HDMI Video Capture Card - HD33](https://www.acasis.com/collections/acasis-capture-card/products/acasis-4k-type-c-to-hdmi-compatible-video-capture-card-1080p-game-capture-card-recorder-box-device-for-live-streaming)
  - [Apogee HDMI Capture USB 3.0 - HV-HCA12](https://www.digital2home.com/apogee-hdmi-capture-usb-3.0-hv-hca12)
  - [Coming soon !] [ACASIS USB 3.0 SDI/HDMI Capture Card - AC-U3SDH](https://www.aliexpress.com/i/1005001929814532.html) / [TYSTVideo 2 Channel SDI+HDMI Video Capture Box - TY-U3SDH](http://www.tystvideo.com/en/product_detail/172/419.html)
  - [Coming soon !] [Rullz MS2130 HDMI Video Capture 4K 30Hz U3](https://www.aliexpress.com/i/1005004883158574.html)

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
    - Exposure
  - Subjective test
    - NVIDIA ICAT

### Temperatute test

  - Operating temperature
  - Infiray T2L test

### Reliability test

interval capture test with ffmpeg

## สรุปการทดสอบ

 - การเลือก HDMI capture card
   - MS2109 budget friendly
   - 4K input/output ?
   - Pixel format ?
   - Color accuracy ?
