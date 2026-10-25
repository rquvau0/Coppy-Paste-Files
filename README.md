# Coppy/Paste-Files

⚠Code made with Claude AI, if you have any mistakes please report to me.

 Run with Python.

## **Files**

```text
file_bot_web/
├── file_bot_web.py     # Backend Python: server + xử lý file
└── index.html          # Giao diện (HTML + CSS + JavaScript nhúng chung)
```
## **Structure**

```text
file_bot_web/
├── file_bot_web.py          # Backend Python
│   ├── Tiện ích             # liệt kê file, so trùng tên, đặt tên (1), (2)...
│   ├── API                  # list · dest · copy · delete · backup · browse
│   └── Server               # mở web tại 127.0.0.1:8765, tự bật trình duyệt
│
└── index.html               # Giao diện (HTML + CSS + JavaScript)
    ├── Nguồn / Đích         # dán đường dẫn hoặc bấm Chọn…
    ├── Tab Sao chép         # tích chọn, tìm, sắp xếp A→Z / Z→A
    ├── Tab Tạo backup       # backup file ở đích hoặc file đã chọn
    ├── Tab Xóa file ở đích
    ├── Tab Xem trước vị trí # kéo thả sắp thứ tự chép
    └── Khung Kết quả
```
## **Works**

```text
1. python file_bot_web.py
        │
        ▼
2. Browser auto open interface (index.html)
        │
        ▼
3. Paste Source start + finish  →  bấm "Tải danh sách"
        │
        ▼
4. Tab paste: choose file necessary copy
        │
        ▼
5. Tab preview: drag to arrange
        │
        ▼
6. Click "Sao chép"
        │
        ▼
7. Python copy files finished to first
   (trùng tên thì hỏi bạn, đổi tên (1), (2)... chứ không ghi đè)
        │
        ▼
8. Announce result [OK] / [LỖI] cho từng file
```
## **How to use**

```text
Download file bot.zip
Extract bot.zip
Run file_bot_web.py
Turn off = close cmd or press key Ctrl + C in cmd
```
