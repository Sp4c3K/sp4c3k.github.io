# 🎨 GitHub Portfolio

Portfolio website đẹp mắt và hiện đại được thiết kế để showcase các dự án và kỹ năng của bạn.

## ✨ Tính năng

- 🎯 **Responsive Design** - Hoạt động tốt trên mọi thiết bị
- 🌈 **Gradient Colors** - Màu sắc gradient đẹp mắt
- ⚡ **Smooth Animations** - Hiệu ứng mượt mà
- 📱 **Mobile Menu** - Menu responsive cho mobile
- 🎭 **Modern UI/UX** - Giao diện hiện đại và thân thiện
- 💫 **Interactive Elements** - Các phần tử tương tác sinh động

## 🚀 Cấu trúc dự án

```
github-portfolio/
│
├── index.html          # File HTML chính
├── styles.css          # File CSS cho styling
├── script.js           # File JavaScript cho tương tác
└── README.md          # File này
```

## 📝 Cách sử dụng

1. **Cập nhật thông tin cá nhân:**
   - Mở `index.html`
   - Thay thế "Tên Của Bạn" bằng tên thật của bạn
   - Cập nhật email, số điện thoại, và địa chỉ
   - Thêm link GitHub, LinkedIn, Twitter của bạn

2. **Thêm dự án của bạn:**
   - Tìm section `<section id="projects">`
   - Thêm hoặc sửa các `.project-card`
   - Cập nhật tên dự án, mô tả, và link

3. **Cập nhật kỹ năng:**
   - Tìm section `<section id="skills">`
   - Thêm hoặc xóa các kỹ năng phù hợp với bạn

4. **Thêm ảnh của bạn:**
   - Thay thế `.image-placeholder` bằng thẻ `<img>` với ảnh của bạn
   - Hoặc thêm ảnh vào folder và link đến nó

## 🎨 Tùy chỉnh màu sắc

Trong file `styles.css`, bạn có thể thay đổi màu sắc tại phần `:root`:

```css
:root {
    --primary-color: #6366f1;    /* Màu chính */
    --secondary-color: #8b5cf6;  /* Màu phụ */
    --accent-color: #ec4899;     /* Màu nhấn */
    --bg-color: #0f172a;         /* Màu nền */
}
```

## 🌐 Deploy lên GitHub Pages

1. Tạo repository mới trên GitHub với tên: `username.github.io` (thay `username` bằng username GitHub của bạn)
2. Push code lên repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```
3. Vào Settings > Pages
4. Chọn source là `main` branch
5. Website sẽ được publish tại `https://username.github.io`

## 📱 Sections trong Portfolio

1. **Home** - Phần giới thiệu với gradient text và animation
2. **About** - Thông tin chi tiết về bạn
3. **Projects** - Showcase các dự án của bạn
4. **Skills** - Các kỹ năng và công nghệ bạn sử dụng
5. **Contact** - Form liên hệ và thông tin

## 💡 Tips

- Thêm ảnh thật của các dự án để portfolio trở nên chuyên nghiệp hơn
- Viết mô tả dự án ngắn gọn nhưng đầy đủ thông tin
- Cập nhật thường xuyên với các dự án mới
- Thêm link đến GitHub repos và live demos
- Tối ưu hóa ảnh để website load nhanh hơn

## 🛠️ Công nghệ sử dụng

- HTML5
- CSS3 (với CSS Variables và Flexbox/Grid)
- Vanilla JavaScript
- Font Awesome Icons

## 📄 License

Free to use! Bạn có thể tự do sử dụng và chỉnh sửa theo ý muốn.

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Nếu bạn có ý tưởng cải thiện, hãy tạo pull request.

---

**Chúc bạn thành công với portfolio của mình! 🎉**
