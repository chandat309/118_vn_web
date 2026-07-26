# 118.vn — Website Giao Đồ Ăn Nhanh

## Tính năng
- ✅ Responsive mobile-first (320px → 1440px+)
- ✅ Đa ngôn ngữ: VI / EN / 中文
- ✅ Chọn địa chỉ giao hàng + GPS
- ✅ Tìm kiếm nhà hàng, lọc danh mục
- ✅ Giỏ hàng + Đặt hàng online
- ✅ Thanh toán: QR Banking, MoMo, Thẻ, Tiền mặt
- ✅ Theo dõi đơn hàng real-time (tracking)
- ✅ Bottom navigation mobile
- ✅ Promo banners, Flash sale
- ✅ 8 nhà hàng mẫu với menu đầy đủ

## Deploy lên Vercel (3 bước)

### Bước 1: Copy folder
```
cp -r /Users/tuanpham/Desktop/Code_web/118_vn_web /path/to/your/project
```

### Bước 2: Cài Vercel CLI
```
npm install -g vercel
```

### Bước 3: Deploy
```
cd /Users/tuanpham/Desktop/Code_web/118_vn_web
vercel --prod
```

## Cấu trúc
```
118_vn_web/
├── index.html      # Toàn bộ website (HTML + CSS + JS)
├── vercel.json     # Config deploy Vercel
└── README.md       # Hướng dẫn
```

## Phát triển tiếp
- Kết nối backend API (Node.js / Supabase)
- Tích hợp VietQR thanh toán thật
- Google Maps địa chỉ
- Push notification đơn hàng
- PWA (Progressive Web App) — offline support
