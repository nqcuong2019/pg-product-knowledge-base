# Cơ sở Tri thức Sản phẩm P&G

Đây là kho lưu trữ dữ liệu sản phẩm của P&G, được sử dụng làm cơ sở tri thức cho các trợ lý AI Gemini (GEMs).

## Cấu trúc dữ liệu

Dữ liệu được chia thành các tệp CSV sau:

### 1. `P&G - SKU.xlsx - SKU.csv`

Tệp này chứa danh sách chi tiết của từng đơn vị lưu kho (SKU - Stock Keeping Unit).

* **Mô tả:** Mỗi dòng tương ứng với một sản phẩm cụ thể.
* **Các cột dữ liệu:**
    * `Mã SKU`: (Kiểu dữ liệu: Text) - Mã định danh duy nhất cho sản phẩm.
    * `Tên sản phẩm`: (Kiểu dữ liệu: Text) - Tên đầy đủ của sản phẩm.
    * `Nhãn hàng`: (Kiểu dữ liệu: Text) - Nhãn hàng của sản phẩm (ví dụ: Downy, Ariel, Pampers).
    * `Danh mục`: (Kiểu dữ liệu: Text) - Danh mục sản phẩm (ví dụ: Nước giặt, Tã em bé).
    * *(Thêm mô tả cho các cột khác nếu có...)*

### 2. `P&G - SKU.xlsx - Tier.csv`

Tệp này định nghĩa các cấp (Tier) hoặc phân khúc của sản phẩm.

* **Mô tả:** Dùng để phân loại sản phẩm vào các nhóm chiến lược hoặc giá cả khác nhau.
* **Các cột dữ liệu:**
    * `Tier Name`: (Kiểu dữ liệu: Text) - Tên của phân khúc (ví dụ: Premium, Mid-tier, Value).
    * `Description`: (Kiểu dữ liệu: Text) - Mô tả chi tiết về đặc điểm của phân khúc này.
    * *(Thêm mô tả cho các cột khác nếu có...)*

---
