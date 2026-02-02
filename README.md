
# Stenography Lab Series  <!-- omit from toc -->
![Audio Steganography Banner](https://img.shields.io/badge/Subject-Steganography-C5BAFF)
![License](https://img.shields.io/badge/License-MIT-2496ED)
![Python](https://img.shields.io/badge/Python-3\.x-129990?logo=python)
![Labtainer](https://img.shields.io/badge/Platform-Labtainer-FFE99A?logo=virtualbox)
![Docker](https://img.shields.io/badge/Docker-Used-FAAC68?ogo=docker&logoColor=white)
![OS](https://img.shields.io/badge/OS-Ubuntu-E9433F?logo=ubuntu&logoColor=white)



## TOC <!-- omit from toc -->
- [Installation](#installation)
- [Hướng dẫn tải và kích hoạt các bài lab](#hướng-dẫn-tải-và-kích-hoạt-các-bài-lab)
  - [Ảnh (6 bài)](#ảnh-6-bài)
    - [1a. stego-image-code-lsb (checked)](#1a-stego-image-code-lsb-checked)
    - [1b. stego\_lsb\_image (uploading ----)](#1b-stego_lsb_image-uploading-----)
    - [2. stego\_dct\_code (checked)](#2-stego_dct_code-checked)
    - [3. destego\_dct\_code (checked)](#3-destego_dct_code-checked)
    - [4. stego-basic-dwt (checked)](#4-stego-basic-dwt-checked)
    - [5. stego-basic-extract-dwt (checked)](#5-stego-basic-extract-dwt-checked)
    - [6. stego-basic-dwt-rgb (checed)](#6-stego-basic-dwt-rgb-checed)
  - [Âm thanh (8 bài)](#âm-thanh-8-bài)
    - [1. steg-lsb-basic (checked)](#1-steg-lsb-basic-checked)
    - [2. steg-echo-hiding-1 (checked)](#2-steg-echo-hiding-1-checked)
    - [3. steg-echo-hiding-2 (checked)](#3-steg-echo-hiding-2-checked)
    - [4. steg-phase-coding-embed](#4-steg-phase-coding-embed)
    - [5. steg-phase-coding-extract](#5-steg-phase-coding-extract)
    - [6. dsss\_cdma (checked)](#6-dsss_cdma-checked)
    - [7. steg-fhss-embed (checked)](#7-steg-fhss-embed-checked)
    - [8. steg-fhss-extract (checked)](#8-steg-fhss-extract-checked)
  - [Video (8 bài)](#video-8-bài)
    - [1a. stego-energy-embed (checked)](#1a-stego-energy-embed-checked)
    - [2a. extract-energy-extract (checked)](#2a-extract-energy-extract-checked)
    - [1b. video-stego-dct](#1b-video-stego-dct)
    - [2b. extract-video-dct](#2b-extract-video-dct)
    - [3. dct-video-stego (checked)](#3-dct-video-stego-checked)
    - [4. dct-video-extract (checked)](#4-dct-video-extract-checked)
    - [5. bpcs\_steg](#5-bpcs_steg)
    - [6. bpcs\_extract](#6-bpcs_extract)
    - [7. video\_qp\_stego](#7-video_qp_stego)
    - [8. video\_extract\_qp\_stego](#8-video_extract_qp_stego)
  - [Phát hiện giấu tin (2 bài)](#phát-hiện-giấu-tin-2-bài)
    - [1. stegano-detect-bwfw-echo-hiding](#1-stegano-detect-bwfw-echo-hiding)
    - [2. video\_detect\_qp\_stego](#2-video_detect_qp_stego)
  - [Tấn công (3 bài)](#tấn-công-3-bài)
    - [1. video-stego-attack-lsb-1](#1-video-stego-attack-lsb-1)
    - [2. stegano-attack-bwfw-echo](#2-stegano-attack-bwfw-echo)
    - [3.stego\_code\_bpcs\_attack1](#3stego_code_bpcs_attack1)
  - [Ứng dụng (1 bài)](#ứng-dụng-1-bài)
    - [1. stego-basic-dwt-watermark](#1-stego-basic-dwt-watermark)
- [Hướng đẫn thực hành](#hướng-đẫn-thực-hành)

# Installation
Để chạy Lab, trước tiên cần tải VMware/Virtual Box.

Sau đó cần tải file .ova của Labtainer (Tìm kiếm trên google).

Đây là link Cài đặt labtainer .ova bản cũ: https://nps.box.com/shared/static/2chwo31xgxm2hs4hewp2n4nblroyagwz.ova

Chạy file .ova đó và nó sẽ tự động mở VMware/Virtual Box và tạo máy ảo Labtainer.

> [!NOTE]  
> Sau khi cài đặt máy ảo, sinh viên cần:
> - Cài đặt và kích hoạt các bài lab
> - Thực hành các bài lab thông qua hướng dẫn
> 
> Sinh viên xem outline của file README này để thực hiện.


# Hướng dẫn tải và kích hoạt các bài lab

Trong máy ảo Labtainer, mở terminal và:

```
cd ~/labtainer/trunk/scripts/labtainer-student
```

Với mỗi bài lab, gõ lệnh sau để tải về và kích hoạt bài lab tương ứng (sinh viên tìm theo mã bài lab tương ứng):

---

## Ảnh (6 bài)

### 1a. stego-image-code-lsb (checked)

Tên bài: GIẤU VÀ TÁCH TIN TRONG ẢNH BẰNG THUẬT TOÁN LSB

Độ khó: Mức 2

gõ lệnh sau để tải bài lab về:

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-image-code-lsb.tar
```

imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-image-code-lsb.tar

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-image-code-lsb
```

Sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](image/docs/stego-image-code-lsb.docx)


> Bài 1a và 1b có nội dung thực hành tương tự, nếu không tải được bài 1a, có thể tải bài 1b


### 1b. stego_lsb_image (uploading ----)
Tên bài: GIẤU VÀ TÁCH TIN TRONG ẢNH BẰNG THUẬT TOÁN LSB

Độ khó: Mức 2

gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego_lsb_image.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego_lsb_image
```


### 2. stego_dct_code (checked)
Tên bài: GIẤU TIN TRONG ẢNH BẰNG THUẬT TOÁN DCT

Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego_dct_code.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego_dct_code
```

Sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](image/docs/stego_dct_code.docx)


### 3. destego_dct_code (checked)
Tên bài: TÁCH TIN TRONG ẢNH BẰNG THUẬT TOÁN DCT

Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/destego_dct_code.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r destego_dct_code
```

Sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](image/docs/destego_dct_code.docx)


### 4. stego-basic-dwt (checked)
Tên bài: Giấu tin trong ảnh xám sử dụng thuật toán biến đổi Wavelet rời rạc DWT

Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-basic-dwt.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-basic-dwt
```

Sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](image/docs/stego-basic-dwt.docx)


### 5. stego-basic-extract-dwt (checked)
Tên bài: Tách tin trong ảnh xám được giấu bởi  thuật toán biến đổi Wavelet rời rạc DWT

Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-basic-extract-dwt.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-basic-extract-dwt
```

Sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](image/docs/stego-basic-extract-dwt.docx)



### 6. stego-basic-dwt-rgb (checed)
Tên bài: Giấu tin trong ảnh màu sử dụng thuật toán biến đổi Wavelet rời rạc DWT

Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-basic-dwt-rgb.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-basic-dwt-rgb
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](image/docs/stego-basic-dwt-rgb.docx)


---

## Âm thanh (8 bài)
### 1. steg-lsb-basic (checked)
Tên bài: GIẤU VÀ TÁCH TIN TRONG ÂM THANH SỬ DỤNG PHƯƠNG PHÁP LSB THUẦN
Độ khó: Mức 1

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-lsb-basic.tar
```

Kích hoạt:

```
labtainer -r steg-lsb-basic
```
Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-lsb-basic.docx)


### 2. steg-echo-hiding-1 (checked)
Tên bài: GIẤU TIN TRONG ÂM THANH SỬ DỤNG PHƯƠNG PHÁP ECHO HIDING

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-echo-hiding-1.tar
```

Kích hoạt:

```
labtainer -r steg-echo-hiding-1
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-echo-hiding-1.docx)


### 3. steg-echo-hiding-2 (checked)
Tên bài: TÁCH TIN TRONG ÂM THANH SỬ DỤNG PHƯƠNG PHÁP ECHO HIDING

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-echo-hiding-2.tar
```

Kích hoạt:

```
labtainer -r steg-echo-hiding-2
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-echo-hiding-2.docx)



### 4. steg-phase-coding-embed
Tên bài: GIẤU TIN TRONG ÂM THANH SỬ DỤNG PHƯƠNG PHÁP MÃ HÓA PHA

Độ khó: Mức 2

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-phase-coding-embed.tar
```

Kích hoạt:

```
labtainer -r steg-phase-coding-embed
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-phase-coding-embed.docx)



### 5. steg-phase-coding-extract
Tên bài: TÁCH TIN TRONG ÂM THANH SỬ DỤNG PHƯƠNG PHÁP MÃ HÓA PHA

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-phase-coding-extract.tar
```

Kích hoạt:

```
labtainer -r steg-phase-coding-extract
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-phase-coding-extract.docx)



### 6. dsss_cdma (checked)
Tên bài: Mô phỏng triển khai hệ thống truyền thông Direct Sequence Spread Spectrum Code Division Multiple Access (DSSS-CDMA) - Thuật toán trải phổ dãy trực tiếp
Độ khó: Mức 4

Gõ lệnh sau để tải bài lab về:

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/dsss_cdma.tar
```

Kích hoạt:

```
labtainer -r dsss_cdma
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/dsss_cdma.docx)


### 7. steg-fhss-embed (checked)
Tên bài: GIẤU TIN TRONG ÂM THANH SỬ DỤNG KỸ THUẬT TRẢI PHỔ NHẢY TẦN (FHSS)
Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-fhss-embed.tar
```

Kích hoạt:

```
labtainer -r steg-fhss-embed
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-fhss-embed.docx)



### 8. steg-fhss-extract (checked)

Tên bài: TÁCH TIN TRONG ÂM THANH SỬ DỤNG KỸ THUẬT TRẢI PHỔ NHẢY TẦN (FHSS)
Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:

```
imodule imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-fhss-extract.tar
```

Kích hoạt:

```
labtainer -r steg-fhss-extract
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](audio/docs/steg-fhss-extract.docx)



---


## Video (8 bài)

### 1a. stego-energy-embed (checked)
Tên bài: Giấu tin trong video dựa trên sự khác biệt năng lượng (DEW) và hệ số  DCT

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/stego-energy-embed.tar
```
sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-energy-embed
```
Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](video/docs/stego-energy-embed.docx)


> Bài 1a và 1b có nội dung thực hành tương tự, nếu không tải được bài 1a, có thể tải bài 1b


### 2a. extract-energy-extract (checked)
Tên bài: Tách tin trong video dựa trên sự khác biệt năng lượng (DEW) và hệ số  DCT

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/extract-energy-extract.tar
```
sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r extract-energy-extract
```
Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](video/docs/extract-energy-extract.docx)

> Bài 2a và 2b có nội dung thực hành tương tự, nếu không tải được bài 2a, có thể tải bài 2b

### 1b. video-stego-dct
Tên bài: Giấu tin trong video dựa trên sự khác biệt năng lượng  (DEW - Difference Energy Watermarking) trong cùng một khung hình sử dụng DCT

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/video-stego-dct.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r video-stego-dct
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](video/docs/video-stego-dct.docx)


### 2b. extract-video-dct
Tên bài: Tách tin trong video dựa trên sự khác biệt năng lượng  trong cùng một khung hình sử dụng DCT 

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/extract-video-dct.tar
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r extract-video-dct
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](video/docs/extract-video-dct.docx)

### 3. dct-video-stego (checked)
Tên bài: Giấu tin vào hệ số DC-AC (DCT) của video sử dụng hệ số cân bằng độ lệch

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/dct-video-stego.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r dct-video-stego    
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](video/docs/dct-video-stego.docx)


### 4. dct-video-extract (checked)
Tên bài: Tách tin trong hệ số DC-AC (DCT) của video sử dụng hệ số cân bằng độ lệch

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/dct-video-extract.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r dct-video-extract
```

Sau đó sinh viên hoàn thành các nhiệm vụ theo hướng dẫn tại: [Tại đây](video/docs/dct-video-extract.docx)

### 5. bpcs_steg
Tên bài: GIẤU VÀ TÁCH TIN TRÊN VIDEO SỬ DỤNG PHƯƠNG PHÁP MẶT PHẲNG BIT

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/bpcs_steg.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r bpcs_steg
```
### 6. bpcs_extract
Tên bài: TÁCH TIN TRÊN VIDEO SỬ DỤNG PHƯƠNG PHÁP MẶT PHẲNG BIT

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/bpcs_extract.tar
```

sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r bpcs_extract
```

### 7. video_qp_stego
Tên bài: Giấu tin trong video H.264 dựa vào Quantization Parameter

Dộ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/video_qp_stego.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r video_qp_stego

```

### 8. video_extract_qp_stego
Tên bài: Tách tin trong video H.264 dựa vào Quantization Parameter

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/video_extract_qp_stego.tar
```
sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r video_extract_qp_stego
```




## Phát hiện giấu tin (2 bài)

### 1. stegano-detect-bwfw-echo-hiding
Tên bài: PHÁT HIỆN FILE ÂM THANH BỊ GIẤU TIN BỞI THUẬT TOÁN BACKWARD-FORWARD ECHO HIDING

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/stegano-detect-bwfw-echo-hiding.tar
```
sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stegano-detect-bwfw-echo-hiding  
```


### 2. video_detect_qp_stego
Tên bài: Phát hiện giấu tin sử dụng Quantization Parameter trong video H.264

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/video/video_detect_qp_stego.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r video_detect_qp_stego
```


## Tấn công (3 bài)
### 1. video-stego-attack-lsb-1
Tên bài: TẤN CÔNG LÊN TIN ĐƯỢC GIẤU BỞI PHƯƠNG PHÁP LSB TRONG VIDEO

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/attack/video-stego-attack-lsb-1.tar
```
sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r video-stego-attack-lsb-1
```



### 2. stegano-attack-bwfw-echo
Tên bài: TẤN CÔNG NHÚNG MỘT SCRIPT ĐỘC HẠI TRONG ÂM THANH SỬ DỤNG THUẬT TOÁN BACKWARD-FORWARD ECHO HIDING

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/attack/stegano-attack-bwfw-echo.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r stegano-attack-bwfw-echo
```
### 3.stego_code_bpcs_attack1
Tên bài: TẤN CÔNG LÊN TIN ĐƯỢC GIẤU BỞI PHƯƠNG PHÁP MẶT PHẲNG BIT

Độ khó: Mức 3

Gõ lệnh sau để tải bài lab về: 

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/attack/stego_code_bpcs_attack1.tar
```
sau đó 

```
labtainer -r stego_code_bpcs_attack1
```


## Ứng dụng (1 bài)
### 1. stego-basic-dwt-watermark
Tên bài: NHÚNG WATERMARK  VÀO ẢNH BẰNG THUẬT TOÁN DWT

Độ khó: Mức 2

Gõ lệnh sau để tải bài lab về:
```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/apps/stego-basic-dwt-watermark.tar
```
sau đó gõ lệnh sau để kích hoạt:
```
labtainer -r stego-basic-dwt-watermark
```



# Hướng đẫn thực hành
- Với mỗi bài lab sau khi tải về và kích hoạt tại bước trước đó, sinh viên sẽ được hỏi email, tại đây sinh viên gõ mã sinh viên của mình.
- Để hoàn thành nhiệm vụ trong từng bài, sinh viên làm theo hướng dẫn trong `docs` tương ứng (xem các folder của repo này).
- Cuối cùng gõ lệnh `checkwork` tại terminal ban đầu để kiểm tra kết quả làm bài.
- Sinh viên nộp file `.lab` trên hệ thống để chấm điểm.
- Để kết thúc bài lab, gõ lệnh `stoplab <mã-bài-lab>` tại terminal ban đầu.

---
