# Deployment

## Môi trường phát triển

Môi trường phát triển sử dụng:

- Ubuntu 26.04 LTS
- VMware
- Node.js
- Yarn
- PostgreSQL
- Backstage

## Môi trường Kubernetes

Kubernetes sẽ được triển khai ở giai đoạn tiếp theo.

Mục tiêu là kết nối Backstage với Kubernetes để hiển thị trạng thái deployment của service.

## Quy trình dự kiến

Source Code
→ GitHub
→ CI/CD
→ Container Image
→ Kubernetes
→ Running Pod

