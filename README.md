[![Website](https://img.shields.io/badge/Live_Demo-Click_Here-blue?style=for-the-badge&logo=google-chrome)](https://ngockhanhvd2812.github.io/dba_interview/)

# 🚀 Sự Cố Datafile trên Oracle RAC

> **Phân tích trực quan “kinh điển” khi đặt datafile sai chỗ trên Oracle RAC**  
> Khám phá **phát hiện**, **khắc phục** & **phòng ngừa** sự cố Datafile cục bộ vs ASM qua minh hoạ động và mô phỏng thực tế.

---

### 🌐 Kiến Trúc RAC Tương Tác
- **SVG động** với 2 instance, shared ASM, datafile cục bộ  
- **Kéo–thả** datafile sang ASM để “fix”  
- **Glow** & **confetti** khi xử lý thành công  

### ⚠️ Phân Tích Hệ Quả
- 4 card mở rộng chi tiết (click để xem)  
- **Pie Chart** minh hoạ tỉ lệ ORA‑01157, treo session, mất recover, outage  

### 🔍 Phát Hiện Lỗi
1. **SQL Simulation**: filter `gv$datafile`  
2. **Alert Log**: slide‑in log với ORA errors  
3. **OS Check**: “ls” trên FS giả lập file không tồn tại  

### 📊 Biểu Đồ So Sánh
- **Bar Chart** downtime (phút) cho Online (12c+) vs Offline (≤11g)  
- Tương tác hover để xem chi tiết  

