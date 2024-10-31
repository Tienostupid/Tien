# NhapMonCNTT

# Nội dung học phần  

# Chương 1
## Giới thiệu về máy tính
### 1.Máy tính là gì?
- Thiết bị điện tử có khả năng thao tác thông tin và dữ liệu; lưu trữ, truy xuất và xử lý dữ liệu.
**Ứng dụng của máy tính:**
- Giáo dục, kinh doanh, sản xuất...
**Các thành phần máy tính**
- Phần cứng (Hardware): Các thành phần vật lý, bao gồm:
- Bộ vi xử lý (CPU)
- Bộ nhớ (RAM)
- Hệ thống lưu trữ (HDD/SSD)
- Bo mạch chủ (Motherboard)
- Card đồ họa (GPU)
- Thiết bị ngoại vi (bàn phím, chuột, màn hình...)
**Phần mềm (Software): Các chương trình và ứng dụng, chia thành:**
- Hệ điều hành (Windows, macOS, Linux)
- Phần mềm ứng dụng (Microsoft Office, Adobe Photoshop...)
***Các loại máy tính***
- Máy tính cá nhân (PC): Desktop, Laptop
- Máy tính bảng (Tablet)
- Máy trạm (Workstation)
- Máy tính nhúng (Embedded Computer)
- Máy chủ (Server)
- Siêu máy tính (Supercomputer)
- Máy tính lượng tử (Quantum Computer)
## 2.Lịch sử phát triển của máy tính
- ***Jacques de Vaucanson***: Tiên phong trong tự động hóa.
- ***Joseph Marie Jacquard***: Máy dệt tự động.
- ***Charles Babbage***: "Cha đẻ của máy tính", phát minh máy tính Difference Engine và Analytical Engine.
- ***Konrad Zuse***: Tạo ra máy tính Z3 và phát triển ngôn ngữ lập trình Plankalkül.
- ***ENIAC (1945)***: Máy tính đầu tiên lập trình được, rất lớn và phức tạp.
- ***UNIVAC (1951)***: Máy tính thương mại đầu tiên.
- ***IBM 7030 Stretch (1961)***: Máy tính với khả năng tính toán cao.
## 3.Các thế hệ máy tính
- Thế hệ đầu tiên (1940-1955): Ống chân không, kích thước lớn.
- Thế hệ thứ hai (1956-1963): Transistor, kích thước nhỏ hơn.
- Thế hệ thứ ba (1964-1971): Mạch tích hợp (IC), hiệu suất cao.
- Thế hệ thứ tư (1971-nay): Vi xử lý, máy tính cá nhân.
- Thế hệ thứ năm (hiện tại và tương lai): Trí tuệ nhân tạo (AI) và máy tính lượng tử.
## 4.Phần cứng máy tính
**Các thành phần chính:**
- Bo mạch chủ (Motherboard)
- Bộ xử lý trung tâm (CPU)
- Bộ nhớ RAM
- Ổ cứng (HDD/SSD)
- Card đồ họa (GPU)
- Nguồn cấp điện (PSU)
- Thiết bị ngoại vi
**Chức năng của CPU:** Điều khiển hoạt động máy tính và xử lý dữ liệu.

**Bộ nhớ:** Chức năng lưu trữ dữ liệu và chương trình, bao gồm bộ nhớ trong (RAM, ROM) và bộ nhớ ngoài (HDD, SSD).

**Hệ thống vào ra:** Kết nối thông tin giữa máy tính và thế giới bên ngoài; bao gồm các mô-đun điều khiển vào ra và thiết bị ngoại vi.


# Chương 2
 ## 1.Biểu diễn thông tin trong máy tính:

**Bit và Byte:**
- Thông tin trong máy tính được biểu diễn bằng các bit, với mỗi bit có thể là 0 hoặc 1.
- Một byte gồm 8 bit, có thể biểu diễn 256 giá trị khác nhau (từ 0 đến 255).
**Dữ liệu và kiểu dữ liệu:**
- Các loại dữ liệu cơ bản trong máy tính bao gồm số nguyên, số thực, ký tự, chuỗi, và mảng.
- Dữ liệu được lưu trữ và xử lý trong bộ nhớ, có thể được tổ chức dưới dạng cấu trúc dữ liệu phức tạp hơn.
## 2.Hệ thống số:

**Các hệ thống số chính:**
- ***Hệ nhị phân (cơ số 2)***: Chỉ sử dụng hai ký tự 0 và 1. Ví dụ: 100110
- ***Hệ thập phân (cơ số 10)***: Sử dụng mười ký tự từ 0 đến 9. Ví dụ:19,20,...
- ***Hệ bát phân (cơ số 8)***: Sử dụng tám ký tự từ 0 đến 7. Ví dụ:167,... 
- ***Hệ thập lục phân (cơ số 16)***: Sử dụng mười sáu ký tự (0-9 và A-F). Ví dụ: 1,A,16,1A,...
  
**Ý nghĩa và ứng dụng:**
- Mỗi hệ thống có ứng dụng riêng, ví dụ hệ nhị phân là nền tảng của lập trình máy tính, trong khi hệ thập lục phân thường dùng để biểu diễn địa chỉ bộ nhớ.
## 3.Chuyển đổi cơ số:

| **Chuyển Đổi**                     | **Cách Thực Hiện**                                                                                                            | **Ví Dụ**                                           |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| **Thập Phân sang Nhị Phân**       | - Chia số thập phân cho 2. <br> - Ghi lại phần dư. <br> - Lặp lại cho đến khi thương số bằng 0. <br> - Đọc các phần dư từ dưới lên. | 13<sub>10</sub> → 1101<sub>2</sub>                               |
| **Nhị Phân sang Thập Phân**       | - Nhân từng bit của số nhị phân với \(2^{n}\) (n là chỉ số bit, bắt đầu từ 0 từ phải sang trái). <br> - Cộng các giá trị.  | 1101<sub>2</sub> → 1 × 2<sup>3</sup> + 1 × 2<sup>2</sup> + 0 × 2<sup>1</sup> + 1 × 2<sup>0</sup> = 13<sub>10</sub> |
| **Thập Phân sang Bát Phân**       | - Chia số thập phân cho 8. <br> - Ghi lại phần dư. <br> - Lặp lại cho đến khi thương số bằng 0. <br> - Đọc các phần dư từ dưới lên. | 65<sub>10</sub> → 101<sub>8</sub>                               |
| **Bát Phân sang Thập Phân**       | - Nhân từng bit của số bát phân với \(8^{n}\) (n là chỉ số bit). <br> - Cộng các giá trị.                                 | 101<sub>8</sub> → 1 × 8<sup>2</sup> + 0 × 8<sup>1</sup> + 1 × 8<sup>0</sup> = 65<sub>10</sub> |
| **Thập Phân sang Thập Lục Phân**  | - Chia số thập phân cho 16. <br> - Ghi lại phần dư (0-9 và A-F). <br> - Lặp lại cho đến khi thương số bằng 0. <br> - Đọc các phần dư từ dưới lên. | 255<sub>10</sub> → FF<sub>16</sub>                             |
| **Thập Lục Phân sang Thập Phân**  | - Nhân từng ký tự với \(16^{n}\) (n là chỉ số ký tự). <br> - Cộng các giá trị (0-9 là giá trị bình thường, A=10, B=11,..., F=15). | FF<sub>16</sub> → 15 × 16<sup>1</sup> + 15 × 16<sup>0</sup> = 255<sub>10</sub>   |



### Lưu Ý:
- Để chuyển đổi giữa các hệ thống số, bạn có thể kết hợp các bước trong bảng.
- Khi thực hiện các phép toán, hãy chú ý đến dấu hiệu số và kích thước bộ nhớ để tránh tràn số.

## 4.Số nguyên có dấu:

| **Chuyển Đổi**                         | **Cách Thực Hiện**                                                                                              | **Ví Dụ**                                               |
|----------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|
| **Thập Phân sang Nhị Phân (bù 2)**     | - Đối với số dương: Chuyển đổi giống như số thập phân thông thường. <br> - Đối với số âm: <br> 1. Chuyển đổi sang nhị phân. <br> 2. Lấy bù 2 bằng cách đảo bit và cộng 1. | - 5<sub>10</sub> → 0101<sub>2</sub> <br> - (-5)<sub>10</sub>: <br> 1. 5 → 0101<sub>2</sub> <br> 2. Đảo bit: 1010 <br> 3. Cộng 1: 1011<sub>2</sub> |
| **Nhị Phân sang Thập Phân (bù 2)**     | - Nếu bit cao nhất là 0, tính giá trị bình thường. <br> - Nếu bit cao nhất là 1, lấy bù 2: <br> 1. Đảo bit. <br> 2. Cộng 1. <br> 3. Lấy giá trị âm của kết quả. | 1101<sub>2</sub>: <br> 1. Bit cao nhất là 1 → đảo bit: 0010 <br> 2. Cộng 1: 0011 <br> 3. Giá trị = -3<sub>10</sub> |
| **Thập Phân sang Bát Phân (bù 2)**     | - Chuyển đổi sang nhị phân trước, sau đó chuyển sang bát phân. <br> - Đối với số âm, chuyển sang bù 2 trước. | 65<sub>10</sub> → 101<sub>8</sub> <br> - (-65)<sub>10</sub> → <br> 1. 65 → 101<sub>2</sub> → Đảo bit: 010 <br> 2. Cộng 1: 011 → 77<sub>8</sub> |
| **Bát Phân sang Thập Phân (bù 2)**     | - Chuyển đổi sang nhị phân trước. <br> - Nếu bit cao nhất là 7, dùng bù 2.                                     | 101<sub>8</sub> → 65<sub>10</sub> <br> - 777<sub>8</sub>: <br> 1. Chuyển đổi → 111111111<sub>2</sub> → Đảo bit: 000000000 <br> 2. Cộng 1: 000000001 = -65<sub>10</sub> |
| **Thập Phân sang Thập Lục Phân (bù 2)**| - Chuyển đổi sang nhị phân, sau đó sang thập lục phân. <br> - Đối với số âm, tìm bù 2.                         | 255<sub>10</sub> → FF<sub>16</sub> <br> - (-255)<sub>10</sub>: <br> 1. 255 → 11111111<sub>2</sub> → Đảo bit: 00000000 <br> 2. Cộng 1: 00000001 → 01<sub>16</sub> |
| **Thập Lục Phân sang Thập Phân (bù 2)**| - Chuyển đổi sang nhị phân trước. <br> - Nếu bit cao nhất là F, lấy bù 2.                                     | FF<sub>16</sub> → 255<sub>10</sub> <br> - 80<sub>16</sub>: <br> 1. 80 → 10000000<sub>2</sub> → Đảo bit: 01111111 <br> 2. Cộng 1: 10000000 → -128<sub>10</sub> |

## 5.Phép cộng - trừ trên số nguyên:

| **Phép Toán**            | **Cách Thực Hiện**                                                                                               | **Ví Dụ**                                           |
|--------------------------|----------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| **Cộng số dương**       | - Cộng hai số nhị phân bằng cách thực hiện phép cộng từng cặp bit. <br> - Nếu có tổng lớn hơn 1, ghi 0 và mang 1 sang bit tiếp theo. | 3<sub>10</sub> + 5<sub>10</sub>: <br> 0011<sub>2</sub> + 0101<sub>2</sub> = 1000<sub>2</sub> (8<sub>10</sub>) |
| **Cộng số âm**          | - Chuyển số âm sang bù 2. <br> - Cộng như số dương. <br> - Nếu kết quả có bit tràn (carry), bỏ qua bit này. | -5<sub>10</sub> + 3<sub>10</sub>: <br> 1011<sub>2</sub> + 0011<sub>2</sub> = 1000<sub>2</sub> (-2<sub>10</sub>) |
| **Cộng số trái dấu**    | - Nếu một số dương và một số âm, chuyển số âm sang bù 2 và thực hiện phép cộng. <br> - Kết quả có thể dương hoặc âm. | 5<sub>10</sub> + (-3)<sub>10</sub>: <br> 0101<sub>2</sub> + 1101<sub>2</sub> = 0010<sub>2</sub> (2<sub>10</sub>) |
| **Trừ số dương**        | - Chuyển số bị trừ thành số âm và thực hiện phép cộng. <br> - Nếu không có bit tràn, kết quả dương. | 8<sub>10</sub> - 3<sub>10</sub>: <br> 1000<sub>2</sub> + 1101<sub>2</sub> = 0101<sub>2</sub> (5<sub>10</sub>) |
| **Trừ số âm**           | - Chuyển số âm thành số dương và thực hiện phép cộng. <br> - Kết quả có thể là dương hoặc âm. | -5<sub>10</sub> - 3<sub>10</sub>: <br> 1011<sub>2</sub> + 0011<sub>2</sub> = 1000<sub>2</sub> (-8<sub>10</sub>) |
| **Trừ số trái dấu**     | - Nếu một số dương và một số âm, cộng với bù 2 của số âm. <br> - Kết quả có thể dương hoặc âm. | 5<sub>10</sub> - (-3)<sub>10</sub>: <br> 0101<sub>2</sub> + 0011<sub>2</sub> = 1000<sub>2</sub> (8<sub>10</sub>) |

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

2. **Chuyển Đổi Thập Phân sang Nhị Phân**:
   - Chia số cho 2 và ghi lại phần dư.
   - Tiếp tục chia cho 2 cho đến khi thương bằng 0. Đọc các phần dư từ dưới lên.


3. **Chuyển Đổi Nhị Phân sang Bát Phân**:
   - Nhóm các chữ số nhị phân thành từng nhóm 3, bắt đầu từ bên phải. Thêm số 0 nếu cần thiết.
   - Chuyển đổi mỗi nhóm sang một chữ số bát phân.


4. **Chuyển Đổi Bát Phân sang Nhị Phân**:
   - Chuyển đổi từng chữ số bát phân sang nhị phân (3 chữ số cho mỗi chữ số bát phân).


5. **Chuyển Đổi Thập Phân sang Thập Lục**:
   - Chia số cho 16 và ghi lại phần dư.
   - Chuyển các phần dư từ 10 trở lên thành A-F.

6. **Chuyển Đổi Thập Lục sang Thập Phân**:
   - Nhân mỗi chữ số với 16 mũ vị trí của nó.

# Chương 4
- Hệ điều hành Linux
# Chương 5
- Githib
