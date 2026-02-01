âm thanh: 8; video: 8; ảnh: 5; tấn công: 3, ứng dụng 2:; phát hiện 1, 2

# Installation
Để bắt đầu chạy Lab, trước tiên cần tải VMware/Virtual Box.

Sau đó cần tải file .ova của Labtainer (Tìm kiếm trên google).

Đây là link Cài đặt labtainer .ova bản cũ: https://nps.box.com/shared/static/2chwo31xgxm2hs4hewp2n4nblroyagwz.ova

Chạy file .ova đó và nó sẽ tự động mở VMware/Virtual Box và tạo máy ảo Labtainer.


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
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-image-code-lsb.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-image-code-lsb
```



### 1b. stego_lsb_image
Tên bài: GIẤU VÀ TÁCH TIN TRONG ẢNH BẰNG THUẬT TOÁN LSB
Độ khó: Mức 2

gõ lệnh sau để tải bài lab về:
```
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/stego_lsb_image.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego_lsb_image
```


### 2. stego_dct_code
Tên bài: GIẤU TIN TRONG ẢNH BẰNG THUẬT TOÁN DCT
Độ khó: Mức 3
gõ lệnh sau để tải bài lab về:
```
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/stego_dct_code.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego_dct_code
```

### 3. destego_dct_code
Tên bài: TÁCH TIN TRONG ẢNH BẰNG THUẬT TOÁN DCT
Độ khó: Mức 3
gõ lệnh sau để tải bài lab về:
```
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/destego_dct_code.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r destego_dct_code
```
### 4. stego-basic-dwt
Tên bài: Giấu tin trong ảnh xám sử dụng thuật toán biến đổi Wavelet rời rạc DWT
Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-basic-dwt.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-basic-dwt
```
### 5. stego-basic-extract-dwt
Tên bài: Tách tin trong ảnh xám được giấu bởi  thuật toán biến đổi Wavelet rời rạc DWT
Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-basic-extract-dwt.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-basic-extract-dwt
```

### 6. stego-basic-dwt-rgb
Tên bài: Giấu tin trong ảnh màu sử dụng thuật toán biến đổi Wavelet rời rạc DWT
Độ khó: Mức 3

gõ lệnh sau để tải bài lab về:
```
curl -L https://github.com/secattt/stenography/raw/refs/heads/main/image/stego-basic-dwt-rgb.tar | tar -xf - -C ~/labtainer/trunk/labs/
```

sau đó gõ lệnh sau để kích hoạt:

```
labtainer -r stego-basic-dwt-rgb
```


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

## Video

### 1. 


# Hướng đẫn thực hành

- Với mỗi bài lab sau khi tải về và kích hoạt tại bước trước đó, sinh viên sẽ được hỏi email, tại đây sinh viên gõ mã sinh viên của mình.
- Để hoàn thành nhiệm vụ trong từng bài, sinh viên làm theo hướng dẫn trong `docs` tương ứng (xem các folder của repo này).
- Cuối cùng gõ lệnh `checkwork` tại terminal ban đầu để kiểm tra kết quả làm bài.
- Sinh viên nộp file `.lab` trên hệ thống để chấm điểm.
- Để kết thúc bài lab, gõ lệnh `stoplab <mã-bài-lab>` tại terminal ban đầu.
