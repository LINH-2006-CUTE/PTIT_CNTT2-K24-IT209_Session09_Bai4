# Docker Volume - Session 09 - Bài 4

## 1. T?o Named Volume

docker volume create easy-volume

## 2. Ki?m tra Volume

docker volume ls

## 3. Ghi d? li?u vào Volume

docker run --rm -v easy-volume:/data alpine sh -c "echo 'Luu tru du lieu Docker' > /data/test.txt"

## 4. Ğ?c d? li?u t? Volume

docker run --rm -v easy-volume:/data alpine cat /data/test.txt

## 5. Ki?m tra d? li?u

docker run --rm -v easy-volume:/data alpine cat /data/test.txt

## K?t qu?

Luu tru du lieu Docker
