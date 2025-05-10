# TaskFlow - Ứng dụng Quản lý Công việc Nhóm theo Kanban

<p align="center">
  <img src="public/taskflow-logo.png" alt="TaskFlow Logo" width="200"/>
</p>

<p align="center">
  <a href="#tính-năng">Tính năng</a> •
  <a href="#công-nghệ">Công nghệ</a> •
  <a href="#cài-đặt">Cài đặt</a> •
  <a href="#cấu-trúc-dự-án">Cấu trúc dự án</a> •
  <a href="#môi-trường">Môi trường</a> •
  <a href="#testing">Testing</a> •
  <a href="#đóng-góp">Đóng góp</a> •
  <a href="#giấy-phép">Giấy phép</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version 1.0.0"/>
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License MIT"/>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"/>
</p>

## 📋 Giới thiệu

TaskFlow là ứng dụng quản lý công việc nhóm theo mô hình Kanban, giúp tổ chức và theo dõi công việc một cách trực quan. Ứng dụng cho phép người dùng tạo bảng, danh sách và thẻ công việc với giao diện kéo thả trực quan, hỗ trợ làm việc nhóm hiệu quả.

![TaskFlow Demo](public/taskflow-demo.png)

## ✨ Tính năng

- **Xác thực người dùng**: Đăng ký, đăng nhập và quản lý tài khoản
- **Quản lý bảng Kanban**: Tạo, chỉnh sửa và xóa bảng
- **Quản lý danh sách**: Thêm, sửa, xóa và sắp xếp danh sách trong bảng
- **Quản lý thẻ công việc**: Tạo, chỉnh sửa, xóa và di chuyển thẻ giữa các danh sách
- **Giao diện kéo thả**: Sắp xếp danh sách và thẻ bằng thao tác kéo thả trực quan
- **Chia sẻ bảng**: Mời người dùng khác tham gia bảng làm việc
- **Chế độ Dark/Light**: Tùy chỉnh giao diện theo sở thích
- **Responsive**: Tương thích với nhiều kích thước màn hình
- **Xử lý lỗi**: Hiển thị lỗi đẹp mắt với Error Boundary

## 🛠️ Công nghệ

- **Frontend**:
  - [Next.js 14](https://nextjs.org/) (App Router)
  - [React 18](https://reactjs.org/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [Tailwind CSS](https://tailwindcss.com/)
  - [Shadcn UI](https://ui.shadcn.com/)
  - [React Beautiful DnD](https://github.com/atlassian/react-beautiful-dnd)

- **State Management**:
  - Context API
  - useReducer
  - Custom Hooks

- **Testing**:
  - [Jest](https://jestjs.io/)
  - [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

- **CI/CD**:
  - [GitHub Actions](https://github.com/features/actions)
  - [Vercel](https://vercel.com/)

## 🚀 Cài đặt

### Yêu cầu

- Node.js 18.x trở lên
- npm hoặc yarn

### Các bước cài đặt

1. Clone repository:
```bash
git clone https://github.com/your-username/taskflow.git
cd taskflow
