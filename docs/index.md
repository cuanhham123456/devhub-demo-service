# DevHub Demo Service

## Tổng quan

`devhub-demo-service` là service mẫu được sử dụng trong đồ án xây dựng Developer Portal bằng Backstage.

Service này đóng vai trò minh họa cho việc quản lý tập trung thông tin của một dự án phần mềm.

## Mục tiêu

Developer Portal cung cấp một giao diện tập trung để thành viên trong nhóm có thể:

- Xem thông tin service.
- Xem owner của service.
- Truy cập repository GitHub.
- Xem tài liệu kỹ thuật.
- Theo dõi trạng thái triển khai.
- Tích hợp thông tin Kubernetes và CI/CD.

## Công nghệ

- Backstage
- Node.js
- PostgreSQL
- GitHub
- Kubernetes
- TechDocs

## Developer Portal

Service được đăng ký vào Backstage Software Catalog thông qua:

`catalog-info.yaml`

Owner của service:

`team-devhub`
