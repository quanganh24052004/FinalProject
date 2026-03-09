# Final Project - Nguyễn Quang Anh

Đồ án 1: Phương pháp lặp tự thích nghi xấp xỉ nghiệm bài toán chấp nhận tách và áp dụng trong khôi phục ảnh.
- Chuyên ngành: Toán - Tin
- Trường: Đại học Bách Khoa Hà Nội

## Cấu trúc thư mục (Clean Architecture)
Dự án được cấu trúc theo dạng mô-đun:
- `settings/`: Khai báo packages, macros và định dạng trang.
- `frontmatter/`: Trang bìa, nhận xét, lời cảm ơn, tóm tắt,...
- `chapters/`: Các chương của đồ án.
- `backmatter/`: Tài liệu tham khảo và phụ lục.
- `main.tex`: File chính dùng để biên dịch.

## Hướng dẫn biên dịch
Sử dụng `latexmk` hoặc trình biên dịch yêu thích của bạn (như TeXstudio, VSCode + LaTeX Workshop) để biên dịch file `main.tex`.

```bash
latexmk -pdf main.tex
```
