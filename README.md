# esp32-camera-sccb

Working with camera modules using the SCCB protocol in the ESP32 microcontroller.

This project uses exclusively the ESP-IDF Development Framework.

### Supported Soc

- ESP32
- ESP32-S2
- ESP32-S3

### Supported Sensor

| model    | max resolution | color type | output format                                                                         | Len Size |
| -------- | -------------- | ---------- | ------------------------------------------------------------------------------------- | -------- |
| OV2640   | 1600 x 1200    | color      | YUV(422/420)/YCbCr422<br>RGB565/555<br>8-bit compressed data<br>8/10-bit Raw RGB data | 1/4"     |
| OV3660   | 2048 x 1536    | color      | raw RGB data<br/>RGB565/555/444<br/>CCIR656<br/>YCbCr422<br/>compression              | 1/5"     |
| OV5640   | 2592 x 1944    | color      | RAW RGB<br/>RGB565/555/444<br/>CCIR656<br/>YUV422/420<br/>YCbCr422<br/>compression    | 1/4"     |
| OV7670   | 640 x 480      | color      | Raw Bayer RGB<br/>Processed Bayer RGB<br>YUV/YCbCr422<br>GRB422<br>RGB565/555         | 1/6"     |
| OV7725   | 640 x 480      | color      | Raw RGB<br/>GRB 422<br/>RGB565/555/444<br/>YCbCr 422                                  | 1/4"     |
| NT99141  | 1280 x 720     | color      | YCbCr 422<br/>RGB565/555/444<br/>Raw<br/>CCIR656<br/>JPEG compression                 | 1/4"     |
| GC032A   | 640 x 480      | color      | YUV/YCbCr422<br/>RAW Bayer<br/>RGB565                                                 | 1/10"    |
| GC0308   | 640 x 480      | color      | YUV/YCbCr422<br/>RAW Bayer<br/>RGB565<br/>Grayscale                                   | 1/6.5"   |
| GC2145   | 1600 x 1200    | color      | YUV/YCbCr422<br/>RAW Bayer<br/>RGB565                                                 | 1/5"     |
| BF3005   | 640 x 480      | color      | YUV/YCbCr422<br/>RAW Bayer<br/>RGB565                                                 | 1/4"     |
| BF20A6   | 640 x 480      | color      | YUV/YCbCr422<br/>RAW Bayer<br/>Only Y                                                 | 1/10"    |
| SC101IOT | 1280 x 720     | color      | YUV/YCbCr422<br/>Raw RGB                                                              | 1/4.2"   |
| SC030IOT | 640 x 480      | color      | YUV/YCbCr422<br/>RAW Bayer                                                            | 1/6.5"   |
| SC031GS  | 640 x 480      | monochrome | RAW MONO<br/>Grayscale                                                                | 1/6"     |
