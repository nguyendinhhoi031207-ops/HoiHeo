# Hồ sơ cá nhân - Nguyễn Đình Hợi

Website tĩnh được xây dựng bằng HTML5 và CSS3 cho bài tập môn Thiết kế web. Mã nguồn quản lý trên GitHub và xuất bản bằng GitHub Pages.

## 1. Chủ đề

Hồ sơ cá nhân (portfolio) của sinh viên ngành Công nghệ thông tin: giới thiệu bản thân, quá trình học tập, các dự án đã làm và thông tin liên hệ.

## 2. Cấu trúc thư mục

```
project/
├── index.html          Trang chủ
├── gioi-thieu.html     Giới thiệu bản thân, dòng thời gian học tập
├── du-an.html          Ba dự án đã thực hiện, nguồn tham khảo
├── lien-he.html        Thông tin liên hệ và biểu mẫu gửi lời nhắn
├── css/
│   └── style.css       Toàn bộ định dạng giao diện
├── images/
│   ├── avatar.svg
│   ├── campus.svg
│   ├── project-1.svg
│   ├── project-2.svg
│   └── project-3.svg
└── README.md
```

## 3. Kỹ thuật sử dụng

- HTML5 với các thẻ ngữ nghĩa: `header`, `nav`, `main`, `section`, `article`, `figure`, `footer`.
- CSS3: biến CSS (custom properties), Flexbox, CSS Grid, `media query` cho màn hình dưới 820px.
- Toàn bộ đường dẫn tới CSS, hình ảnh và liên kết giữa các trang đều là đường dẫn tương đối.
- Bốn trang dùng chung một tệp `css/style.css` nên giao diện thống nhất.
- Không dùng JavaScript, không dùng thư viện CSS ngoài.

## 4. Cách chạy thử trên máy

Tải toàn bộ thư mục về, mở tệp `index.html` bằng trình duyệt. Không cần cài đặt gì thêm.

## 5. Cách đưa lên GitHub Pages

1. Tạo một kho lưu trữ mới trên GitHub, ví dụ `portfolio`, để chế độ Public.
2. Tải toàn bộ tệp trong thư mục này lên kho (nút **Add file → Upload files**, hoặc dùng Git).
3. Vào **Settings → Pages**.
4. Ở mục **Source** chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/ (root)`, bấm **Save**.
5. Chờ khoảng 1-2 phút, địa chỉ website sẽ có dạng `https://<tên-tài-khoản>.github.io/portfolio/`.
6. Mở địa chỉ đó, kiểm tra lại toàn bộ liên kết và hình ảnh.

Dùng Git trên máy:

```bash
git init
git add .
git commit -m "Khoi tao website ho so ca nhan"
git branch -M main
git remote add origin https://github.com/<ten-tai-khoan>/portfolio.git
git push -u origin main
```

## 6. Nguồn tài liệu và hình ảnh

- Tài liệu HTML, CSS: MDN Web Docs - https://developer.mozilla.org/vi/
- Hướng dẫn triển khai: GitHub Pages - https://pages.github.com/
- Phông chữ: Be Vietnam Pro và Bricolage Grotesque từ Google Fonts, giấy phép SIL Open Font License.
- Hình ảnh: toàn bộ tệp trong thư mục `images/` do tác giả tự vẽ ở định dạng SVG.

## 7. Thông tin sinh viên

- Họ và tên: Nguyễn Đình Hợi
- Điện thoại: 0367 087 736
