# 📚 DuongVocab

Nền tảng học tiếng Anh thông minh với flashcard, bài kiểm tra và luyện tập từ vựng tương tác.

🌐 **Live site:** [https://duongvocab.github.io](https://duongvocab.github.io)

---

## ✨ Tính năng

- 📖 **Học từ vựng** theo chủ đề với flashcard lật 2 mặt
- 🧠 **Kiểm tra** bằng trắc nghiệm (MCQ), điền từ, sắp xếp câu
- 📄 **Học theo sách** – import bài học từ PDF/nội dung có sẵn
- 🤖 **AI hỗ trợ** – giải thích từ vựng, gợi ý học tập
- 📊 **Theo dõi tiến độ** học tập theo từng bài

## 🚀 Deploy lên GitHub Pages

### Bước 1 – Clone hoặc tạo repo mới

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TEN_BAN/TEN_REPO.git
git push -u origin main
```

### Bước 2 – Bật GitHub Pages

1. Vào **Settings** của repo
2. Chọn **Pages** ở sidebar trái
3. Mục **Source** → chọn **Deploy from a branch**
4. Branch: `main` / Folder: `/ (root)`
5. Bấm **Save**

Sau ~1 phút, website sẽ live tại:  
`https://TEN_BAN.github.io/TEN_REPO`

---

## 📁 Cấu trúc thư mục

```
duongvocab/
├── index.html      # Trang chính (toàn bộ app)
├── 404.html        # Trang lỗi 404
├── favicon.svg     # Icon website
└── README.md       # Tài liệu này
```

## 🛠️ Tech Stack

- **Vanilla HTML / CSS / JS** – không cần framework, không cần build
- **Google Fonts** – DM Sans, Playfair Display
- Tất cả data được nhúng trực tiếp trong `index.html`

---

Made with ❤️ by DuongVocab
