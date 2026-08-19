# Kiến trúc hệ thống

## Tổng quan

Hệ thống DevHub được xây dựng theo mô hình Developer Portal.

Backstage đóng vai trò là giao diện trung tâm để quản lý metadata của các thành phần phần mềm.

## Thành phần

### Backstage

Cung cấp giao diện Developer Portal và Software Catalog.

### PostgreSQL

Lưu trữ dữ liệu của Backstage.

### GitHub

Lưu trữ source code và metadata của service.

### Kubernetes

Được sử dụng ở giai đoạn triển khai tiếp theo để quản lý workload.

## Luồng hoạt động

GitHub Repository
→ Software Catalog
→ Backstage
→ Developer Portal

Ở các bước tiếp theo:

Backstage
→ Kubernetes
→ Deployment
→ Pod
→ Service
