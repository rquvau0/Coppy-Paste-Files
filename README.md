# sort-files
code make with claude AI if have a mistake report for me
run with python
**files**
file_bot_web/
├── file_bot_web.py     # Backend Python: server + xử lý file
└── index.html          # Giao diện (HTML + CSS + JavaScript nhúng chung)
**structure**
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
**works**
1.  python file_bot_web.py
        │
        ▼
2. Broswer auto open interface (index.html)
        │
        ▼
3. Paste Source start + finish  →  bấm "Tải danh sách"
        │
        ▼
4. Tab paste: choose file necessary coppy
        │
        ▼
5. Tab preview: drag to arrange
        │
        ▼
6. Click "Sao chép"
        │
        ▼
7. Python coppy files finished to first
   (trùng tên thì hỏi bạn, đổi tên (1), (2)... chứ không ghi đè)
        │
        ▼
8. Annoumance result [OK] / [LỖI] cho từng file
