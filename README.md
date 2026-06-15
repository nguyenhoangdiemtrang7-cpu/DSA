# Đồ án DSA

Đồ án môn học Cấu trúc Dữ liệu và Giải Thuật (DSA) - 25CTT4A, gồm hai phần chính: Phát triển thư viện và Phát triển ứng dụng. Ứng dụng thực tế vào trò chơi cơ chế Endless Runner gồm các cấu trúc đã học và thư viện đồ họa SFML để thiết kế giao diện.

## Đội ngũ phát triển
**Thành viên A (Phát triển thư viện):** Huỳnh Thị Ngọc Quyên - MSSV: 25120270.

**Thành viên B (Phát triển ứng dụng):** Nguyễn Hoàng Diễm Trang - MSSV: 25120245.

## Cấu Trúc Thư Mục Dự Án
* `/lib` : Chứa toàn bộ mã nguồn thư viện C++ Templates.
* `/app` : Chứa toàn bộ mã nguồn ứng dụng.
* `/assets` : Chứa các file bổ sung bao gồm font chữ, hình nền, hình ảnh nhân vật.
* `Makefile` : File hỗ trợ biên dịch nhanh ứng dụng.

## Hướng dẫn biên dịch và chạy mã nguồn
**Cách 1: Sử dụng Makefile**
  1. Mở Terminal/Command Prompt tại thư mục gốc dự án.
  2. Gõ lệnh sau để biên dịch: `make` .
  3. Khởi chạy: `./game.exe`.

**Cách 2: Biên dịch thủ công**
  1. Mở Terminal/Command Prompt tại thư mục mã nguồn dự án.
  2. Biên dịch thủ công bằng lệnh sau: `g++ -std=c++17 main.cpp -o game -lsfml-graphics -lsfml-window -lsfml-system`
  3. 3. Khởi chạy: `./game.exe`.
