# Cách mở trang tiếng Việt ở máy local

Trang tiếng Việt nằm tại `public/index_vi.html`.

Từ thư mục gốc repository, chạy:

```sh
cd public
python3 -m http.server 8000
```

Sau đó mở:

```text
http://localhost:8000/index_vi.html
```

Trang dùng các asset tương tác trong `public/assets`, vì vậy nên mở qua local server thay vì `file://`.
