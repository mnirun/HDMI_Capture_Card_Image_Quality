# HDMI Capture Card Image Quality
HDMI Capture Card Image Quality

- ความเป็นมาและวัตถุประสงค์
- ความรู้เบื้องต้น
  - Image quality
  - Chroma subsampling
  - Pixel format
  - Scaler
  - Splitter
  - Extractor
- อุปกรณ์และโปรแกรมที่ใช้ทดสอบ
  - อุปกรณ์
  - โปรแกรม
- การทดสอบ
  - Latency test
  - Framerate test
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

## อุปกรณ์และโปรแกรมที่ใช้ทดสอบ

### HDMI capture card

  - AVerMedia Live Streamer CAP 4K - BU113
  - ezcap CAM LINK 4K - ezcap331
  - HAGiBiS Video Capture Card - THB01
  - ACASIS 4K HDMI Video Capture Card - HD33
  - Apogee HDMI Capture USB 3.0 - HV-HCA12
  - [Coming soon !] ACASIS USB 3.0 SDI/HDMI Capture Card - U3SDH

### อุปกรณ์อื่น ๆ

  - [UGREEN HDMI splitter 1x2](https://www.amazon.com/dp/B0B129NNV1 )
  - [Infiray T2L Thermal Camera](https://www.infiray.com/products/t2s-t2l-thermal-camera-for-smartphone.html)

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

  - [FFmpeg](https://ffmpeg.org/)
  - [ImageMagick](https://www.imagemagick.org/)
  - [NVIDIA Image Comparison & Analysis Tool (ICAT)](https://www.nvidia.com/en-us/geforce/technologies/icat/)

## การทดสอบ

### Latency test

#### Video latency test

HyperHDR

#### Audio latency test

TBD

### Framerate test

  - PotPlayer
  - trdrop

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
