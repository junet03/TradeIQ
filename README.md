# TradeIQ  
Dự án TradeIQ - theo dõi và phân tích giao dịch.  

## **Chức năng chính:**  
- Thu thập dữ liệu giá và khối lượng từ API.  
- Tính toán lưới giao dịch và phân tích dữ liệu.  
- Theo dõi và quản lý các bot giao dịch tự động.  

## **Cách sử dụng:**  
1. Cấu hình API trong thư mục **configs**.  
2. Chạy mã trong thư mục **scripts** để kết nối dữ liệu.  
3. Theo dõi lịch sử hoạt động trong thư mục **logs**.  

## **Yêu cầu hệ thống:**  
- Python 3.8 trở lên.  
- Các thư viện cần thiết: `requests`, `pandas`, `yaml`.  

## **Hướng dẫn cài đặt:**  
```bash
pip install -r requirements.txt
python scripts/data_fetcher.py
