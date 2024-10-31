# NhapMonCNTT

# Nội dung học phần  

# Chương 1
- Các thành tố máy tính
-
# Chương 2

# Chương 3
- Chuyển đổi hệ cơ số

### Bảng Hướng Dẫn Chuyển Đổi Hệ Cơ Số

| Hệ Cơ Số  | Ký Hiệu | Giải Thích                      |
|------------|---------|---------------------------------|
| Nhị Phân   | 0, 1    | Sử dụng 2 ký tự (0 và 1).      |
| Thập Phân  | 0-9     | Sử dụng 10 ký tự (0 đến 9).    |
| Bát Phân   | 0-7     | Sử dụng 8 ký tự (0 đến 7).      |
| Thập Lục   | 0-9, A-F| Sử dụng 16 ký tự (0-9, A-F).    |

### Cách Chuyển Đổi

1. **Chuyển Đổi Nhị Phân sang Thập Phân**:
   - Nhân mỗi chữ số với 2 mũ vị trí của nó (tính từ phải sang trái, bắt đầu từ 0).
   - Cộng tất cả các giá trị lại.

   **Ví dụ**: \(1101_2\)
   \[
   = 1 \times 2^3 + 1 \times 2^2 + 0 \times 2^1 + 1 \times 2^0 = 8 + 4 + 0 + 1 = 13_{10}
   \]

2. **Chuyển Đổi Thập Phân sang Nhị Phân**:
   - Chia số cho 2 và ghi lại phần dư.
   - Tiếp tục chia cho 2 cho đến khi thương bằng 0. Đọc các phần dư từ dưới lên.

   **Ví dụ**: \(13_{10}\)
   \[
   13 \div 2 = 6 \quad \text{(dư 1)} \\
   6 \div 2 = 3 \quad \text{(dư 0)} \\
   3 \div 2 = 1 \quad \text{(dư 1)} \\
   1 \div 2 = 0 \quad \text{(dư 1)} \\
   \Rightarrow 1101_2
   \]

3. **Chuyển Đổi Nhị Phân sang Bát Phân**:
   - Nhóm các chữ số nhị phân thành từng nhóm 3, bắt đầu từ bên phải. Thêm số 0 nếu cần thiết.
   - Chuyển đổi mỗi nhóm sang một chữ số bát phân.

   **Ví dụ**: \(110101_2\) → Nhóm thành \(110\) \(101\) → \(6\) \(5\) → \(65_8\)

4. **Chuyển Đổi Bát Phân sang Nhị Phân**:
   - Chuyển đổi từng chữ số bát phân sang nhị phân (3 chữ số cho mỗi chữ số bát phân).

   **Ví dụ**: \(65_8\)
   \[
   6 \to 110, \quad 5 \to 101 \Rightarrow 110101_2
   \]

5. **Chuyển Đổi Thập Phân sang Thập Lục**:
   - Chia số cho 16 và ghi lại phần dư.
   - Chuyển các phần dư từ 10 trở lên thành A-F.

   **Ví dụ**: \(255_{10}\)
   \[
   255 \div 16 = 15 \quad \text{(dư 15)} \\
   15 \div 16 = 0 \quad \text{(dư 15)} \Rightarrow \text{F} \text{ (15 trong hệ thập lục)} \Rightarrow FF_{16}
   \]

6. **Chuyển Đổi Thập Lục sang Thập Phân**:
   - Nhân mỗi chữ số với 16 mũ vị trí của nó.

   **Ví dụ**: \(1A3_{16}\)
   \[
   = 1 \times 16^2 + 10 \times 16^1 + 3 \times 16^0 = 256 + 160 + 3 = 419_{10}
   \]
# Chương 4
- Hệ điều hành Linux
# Chương 5
- Githib
