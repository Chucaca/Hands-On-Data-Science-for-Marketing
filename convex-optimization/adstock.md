---
description: Cách tính overcarry effect của marketing
---

# Adstock

Advertising Adstock là thuật ngữ dùng để đo hiệu ứng trì hoãn \(decaying effect\) của quảng cáo từ lúc bắt đầu chạy. Ví dụ, team a chạy quảng cáo ở tuần 1, thì hiệu quả của quảng cáo này sẽ duy trì ở tuần 1 và tiếp tục tuần sau đó.

Dự đoán đầu ra \(ví dụ K2, K1\) = a + b\*adstock\(advertising\)

a và b là biến linear regression

adstock function được định nghĩa là 

$$
A_t=X_t+adstock rate*A_{t-1}
$$

Tối ưu hóa sum of square errors for regression formula by changing the adstock rate

Giải thích toàn học:

Objective function: minimize Σ \(Actual – Predicted\)2

Subject to: 0 &lt;= adstock rate &lt; 1

