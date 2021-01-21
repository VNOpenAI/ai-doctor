---
title: "Giới thiệu bài toán"
weight: 10
---

Kỹ thuật chẩn đoán hình ảnh chụp X-quang diễn ra rất phổ biến trong các xét nghiệm y tế tại bệnh viện. Hình ảnh X-quang phổi có giá trị trong việc phát hiện, chẩn đoán bệnh, đánh giá mức độ nặng, đánh giá các biến chứng hô hấp, theo dõi đáp ứng điều trị và chẩn đoán phân biệt. Trong dự náy VN AIDr, chúng tôi xây dựng hệ thống đánh giá khả năng cho 5 bất thường trên ảnh X-quang phổi, với mong muốn hệ thống này có thể trợ giúp bác sĩ trong quá trình chẩn đoán triệu chứng từ ảnh y tế, hạn chế việc bỏ sót triệu chứng. Hệ thống phân loại tổn thương phổi được chúng tôi xây dựng dựa trên bộ dữ liệu lớn [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) của Đại học Stanford, bao gồm **224316** ảnh chụp X-quang ngực của **65240** bệnh nhân. Với bộ dữ liệu này, chúng tôi xây dựng và huấn luyện các thuật toán học máy, học sâu để nhận ra 5 bất thường trên phổi, bao gồm:

- (a) Xẹp phổi (Atelectasis)
- (b) Tim to (Cardiomegaly)
- (c) Đông đặc phổi (Consolidation)
- (d) Phù nề (Edema)
- (e) Tràn dịch màng phổi (Pleural Effusion)

![Website bộ dữ liệu và cuộc thi CheXpert](chexpert.png)
