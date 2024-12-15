# <center>LẬP TRÌNH KHOA HỌC DỮ LIỆU</center>

---
# ĐỒ ÁN CUỐI KÌ
# PHÂN TÍCH TÌNH HÌNH BỆNH LÍ <br> XÂY DỰNG MÔ HÌNH DỰ ĐOÁN


## Thông tin nhóm
<center>

| HỌ TÊN                | MSSV      |
|:------------------    |:--------: |
| Nguyễn Văn Hiến    | 22120101  |
| Đặng Minh Hoàng       | 22120110  |
| Nguyễn Ngọc Hoàng     | 22120112  |

</center>


### Giảng viên hướng dẫn: 
#### **Thầy Phạm Trọng Nghĩa**
#### **Thầy Vũ Công Thành**

---

## Nội dung
1. [Giới thiệu](#introdution)  
    1.1. [Thông tin bộ dữ liệu](#information)  
    1.2. [Thông tin thuộc tính](#attribute)  
    1.3. [Lí do lựa chọn](#reason)  
2. [Khám phá dữ liệu](#data-exploration)  
    2.1. [Khai báo thư viện](#import-lib)  
    2.2. [Tải bộ dữ liệu](#downloading-data)   
    2.3. [Kích thước bộ dữ liệu](#how-many-rows-and-columns)  
    2.4. [Ý nghĩa các hàng](#rows-exploration)  
    2.5. [Ý nghĩa các cột](#columns-exploration)  
    2.6. [Trực quan hoá phân bố](#data-visualization)
3. [Đặt vấn đề - Tiền xử lí - Phân tích giải quyết vấn đề](#ask-preprocessing-analysis)      
    3.1. [Câu hỏi 1](#question-1)  
    3.2. [Câu hỏi 2](#question-2)  
    3.3. [Câu hỏi 3](#question-3)  
    3.4. [Câu hỏi 4](#question-4) <br>
    3.5. [Câu hỏi 5](#question-5)  
    3.6. [Câu hỏi 6](#question-6)   
4. [Tự đánh giá](#reflection)  
5. [Tham khảo](#references)  

---
## Phân công
#### Link: [**Phân công công việc**](https://docs.google.com/spreadsheets/d/1LFgHiE4LrsdKKONrlz3Dx75mgC28t3EZAGVVMmRnEes/edit?fbclid=IwY2xjawHLI99leHRuA2FlbQIxMAABHdmqChAUwiNuHKush4gsy9TejRrbWguKtTCfDWnIyajlrORcCFAkcnXngQ_aem_GujmZPLFKWAIWjjX9vS1pw&gid=0#gid=0)

---
## Nguồn
#### Dữ liệu
##### Nguồn: [**Indicators of Heart Disease (2022 UPDATE)**](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data)
#### Tham khảo

[1] [**Những di chứng nguy hiểm do hậu COVID-19 ít ai ngờ tới**](https://medlatec.vn/tin-tuc/nhung-di-chung-nguy-hiem-do-hau-covid19-it-ai-ngo-toi-s194-n27545#:~:text=Theo%20c%C3%A1c%20chuy%C3%AAn%20gia%20y,%2C%20%C4%91%C3%B4ng%20m%C3%A1u%2C...)

[2] [**Những người dễ bị đột quỵ thường mắc 9 thói quen xấu này**](https://baosoctrang.org.vn/suc-khoe-va-doi-song/202411/nhung-nguoi-de-bi-dot-quy-thuong-mac-9-thoi-quen-xau-nay-5e00fab/)

[4] [**Học về cây quyết định (Decision tree)**](https://www.youtube.com/watch?v=_L39rN6gz7Y)

[5] [**Học về rừng ngẫu nhiên (Random Forest)**](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ)

[6]  [**Các cách xử lí mất cân bằng dữ liệu**](https://www.youtube.com/watch?v=yLM0FXgQmxw)

[7] [**Chỉ số BMI và cách tính toán theo chuẩn khu vực**](https://tinhbmi.vn/bang-bmi-chuan-chau-a/)

[8] [**Đột quỵ: Nguyên nhân, dấu hiệu nhận biết và cách phòng tránh**](https://www.vinmec.com/vie/bai-viet/dot-quy-nguyen-nhan-dau-hieu-nhan-biet-cach-phong-tranh-vi)

[9] [**Bệnh mãn tính: Các loại bệnh phổ biến và cách phòng ngừa**](https://www.docosan.com/blog/kien-thuc-y-te/benh-man-tinh/)
