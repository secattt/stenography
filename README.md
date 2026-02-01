âm thanh: 8; video: 8; ảnh: 5; tấn công: 3, ứng dụng 2:; phát hiện 1, 2

# Hướng dẫn tải và kích hoạt lab

Trong máy ảo Labtainer, mở terminal và:

```
cd ~/labtainer/trunk/scripts/labtainer-student
```

Với mỗi bài lab, gõ lệnh sau để tải về và kích hoạt bài lab:

## Ảnh

gõ 1 trong 2 lệnh sau để tải bài lab về:

```
curl -L https://raw.githubusercontent.com/user/repo/main/filename --output /đường/dẫn/thư/mục/filename

```

hoặc lệnh

```
wget -P /đường/dẫn/thư/mục/ https://raw.githubusercontent.com/user/repo/main/filename
```

sau đó gõ lệnh sau để kích hoạt:

```

```

## Âm thanh

### steg-lsb-basic

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-lsb-basic.tar
```

Kích hoạt:

```
labtainer -r steg-lsb-basic
```

### steg-echo-hiding-1

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-echo-hiding-1.tar
```

Kích hoạt:

```
labtainer -r steg-echo-hiding-1
```

### steg-echo-hiding-2

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-echo-hiding-2.tar
```

Kích hoạt:

```
labtainer -r steg-echo-hiding-2
```

### dsss_cdma

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/dsss_cdma.tar
```

Kích hoạt:

```
labtainer -r dsss_cdma
```

### steg-fhss-extract

```
imodule imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-fhss-extract.tar
```

Kích hoạt:

```
labtainer -r steg-fhss-extract
```

### steg-fhss-embed

```
imodule https://github.com/secattt/stenography/raw/refs/heads/main/audio/steg-fhss-embed.tar
```

Kích hoạt:

```
labtainer -r steg-fhss-embed
```

# Hướng đẫn thực hành

Với mỗi bài lab sau khi tải về và kích hoạt, làm theo hướng dẫn trong docs tương ứng để hoàn thành nhiệm vụ trong từng bài.
