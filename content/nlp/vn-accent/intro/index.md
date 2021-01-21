---
title: "Giới thiệu bài toán"
weight: 10
---

Bài toán thêm dấu tiếng Việt giải quyết việc thêm dấu cho các văn bản tiếng Việt không dấu. Trên thực tế, bài toán này đã được ứng dụng rất hiệu quả trong [trình duyệt Cốc Cốc](https://coccoc.com/) nhắm tiết kiệm thời gian nhập văn bản của người dùng và nhận được nhiều hưởng ứng tích cực. Trong dự án này, chúng tôi thiết kế và thử nghiệm một hệ thống thêm dấu tiếng Việt cho báo cáo y tế. Hệ thống được ứng dụng trong phần mềm VN AIDr nhằm giúp bác sĩ tiết kiệm thời gian gõ văn bản y tế, ví dụ như nhận xét tình trạng của bệnh nhân. Chúng tôi hy vọng hệ thống này có thể rút ngắn thời gian nhập liệu và góp phần giảm tải áp lực cho bác sĩ.

<img style="width: 25rem; margin-left: auto; margin-right: auto; margin-top: 2rem; display: block;" alt="Banner - Thêm dấu tiếng Việt" src="banner.png">

Với dữ liệu khổng lồ các bài viết tiếng Việt lấy từ Wikipedia, kết hợp với dữ liệu bài viết từ các trang web về y học, chúng tôi huấn luyện các mô hình ngôn ngữ ngram và các mô hình dựa trên học sâu để dự đoán và thêm dấu cho các văn bản y học. Các bước thiết kế mô hình, chuẩn bị dữ liệu, huấn luyện và kiểm thử được chúng tôi trình bày trong các mục dưới. Chúng tôi cũng triển khai và thử nghiệm thực tế các mô hình huấn luyện được trên phần mềm VN AIDr.