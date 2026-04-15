# Experiment Report: Data Quality Impact on AI Agent

**Student ID:** AI20K-0379
**Name:** Lê Minh Tuấn
**Date:** 15/04/2026

---

## 1. Ket qua thi nghiem

Chay `agent_simulation.py` voi 2 bo du lieu va ghi lai ket qua:

| Scenario | Agent Response | Accuracy (1-10) | Notes |
|----------|----------------|-----------------|-------|
| Clean Data (`processed_data.csv`) | Based on my data, the best choice is Laptop at $1200 | 9.6| |
| Garbage Data (`garbage_data.csv`) | Based on my data, the best choice is Nuclear Reactor at $999999. | 2| |

---

## 2. Phan tich & nhan xet

### Tai sao Agent tra loi sai khi dung Garbage Data?

(Viet nhan xet cua ban o day — it nhat 50 tu)

Khi Agent phải xử lý tập dữ liệu chứa "Garbage Data" (dữ liệu rác), khả năng đưa ra quyết định chính xác của nó bị phá vỡ hoàn toàn, bởi vì hệ thống AI luôn tuân theo nguyên tắc "Garbage in, Garbage out" (Đầu vào là rác thì đầu ra cũng là rác).

---

## 3. Ket luan

**Quality Data > Quality Prompt?** toi dong tinh

(Viet ket luan cua ban o day)
