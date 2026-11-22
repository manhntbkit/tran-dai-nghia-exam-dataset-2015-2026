# Bộ Dữ Liệu Thống Kê Đề Khảo Sát, Tỷ Lệ Chọi & Điểm Chuẩn Lớp 6 Trần Đại Nghĩa (2015–2026)
# Tran Dai Nghia Grade 6 Entrance Survey Dataset (2015–2026): Cutoffs, Competition Ratios & 370-Question Linguistic/Difficulty Analysis

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Coverage](https://img.shields.io/badge/Coverage-2015--2026_(11_Exam_Cycles)-blue.svg)](https://onthitdn.com/blog/thong-ke-de-thi-tran-dai-nghia-2015-2026)
[![Digitized Questions](https://img.shields.io/badge/Digitized_Questions-370-success.svg)](https://onthitdn.com/blog/de-thi-tran-dai-nghia)

- **Repository / Dataset Slug**: `tran-dai-nghia-exam-dataset-2015-2026`
- **Primary Research Report**: [https://onthitdn.com/blog/thong-ke-de-thi-tran-dai-nghia-2015-2026](https://onthitdn.com/blog/thong-ke-de-thi-tran-dai-nghia-2015-2026)
- **Full Exam Archive (PDF & Solutions)**: [https://onthitdn.com/blog/de-thi-tran-dai-nghia](https://onthitdn.com/blog/de-thi-tran-dai-nghia)
- **Cutoff & Score Calculator Hub**: [https://onthitdn.com/blog/diem-thi-tran-dai-nghia](https://onthitdn.com/blog/diem-thi-tran-dai-nghia)
- **Raw CSV**: [`https://onthitdn.com/tai-lieu/thong-ke-de-thi-tran-dai-nghia-2015-2026.csv`](https://onthitdn.com/tai-lieu/thong-ke-de-thi-tran-dai-nghia-2015-2026.csv)
- **Raw JSON**: [`https://onthitdn.com/tai-lieu/thong-ke-de-thi-tran-dai-nghia-2015-2026.json`](https://onthitdn.com/tai-lieu/thong-ke-de-thi-tran-dai-nghia-2015-2026.json)
- **Maintainer**: Ban Chuyên Môn OnThiTDN ([https://onthitdn.com](https://onthitdn.com))
- **License**: Creative Commons Attribution 4.0 International (`CC-BY-4.0`)

---

## 1. Tổng quan bộ dữ liệu (Vietnamese Overview)

Bộ dữ liệu mở này tổng hợp số liệu tuyển sinh, điểm chuẩn, tỷ lệ chọi và phân tích định lượng `370` câu hỏi đã số hóa từ `11` kỳ khảo sát năng lực vào lớp 6 **Trường THCS và THPT Trần Đại Nghĩa** (TP. Hồ Chí Minh) giai đoạn `2015–2026` (năm học `2016–2017` đến `2026–2027`; riêng năm `2021–2022` TP.HCM hủy khảo sát và chuyển sang xét tuyển hồ sơ do dịch Covid-19).

### Các tệp trong bộ dữ liệu (Included Files)
1. `thong-ke-de-thi-tran-dai-nghia-2015-2026.csv`: Bảng dữ liệu phẳng (12 dòng tương ứng 12 năm học từ 2015 đến 2026, 20 cột thuộc tính) mã hóa UTF-8, sẵn sàng nhập vào Pandas, R, Excel hoặc Google Sheets.
2. `thong-ke-de-thi-tran-dai-nghia-2015-2026.json`: Cấu trúc JSON phân cấp bao gồm metadata phương pháp luận (`methodology`), thống kê tổng hợp 11 năm (`summary`), và mảng chi tiết từng năm (`years`).

### 5 phát hiện thực nghiệm nổi bật (Key Empirical Findings, 2015–2026)

1. **Điểm chuẩn và tỷ lệ chọi sau mốc tách trường (2024–2026)**:
   - Tháng 5/2024, Trường THPT Chuyên Trần Đại Nghĩa tách thành 2 trường: **THCS và THPT Trần Đại Nghĩa** (53 Nguyễn Du, Quận 1) và **THPT Chuyên Trần Đại Nghĩa** (An Khánh, TP. Thủ Đức). Chỉ tiêu tuyển sinh lớp 6 điều chỉnh từ `525` chỉ tiêu (`2022–2023`) xuống `350` chỉ tiêu (`2024–2026`).
   - Điểm chuẩn tăng liên tiếp qua 5 mùa khảo sát: `63,50/100` (`2022–2023`, chọi `1/6,80`) → `64,75/100` (`2023–2024`, chọi `1/9,14`) → `67,50/100` (`2024–2025`, `4.301` hồ sơ / `350` chỉ tiêu, chọi `1/12,29`) → `73,25/100` (`2025–2026`, `4.851` hồ sơ / `350` chỉ tiêu, chọi `1/13,86`) → **`75,25/100`** (`2026–2027`, khảo sát ngày `01/07/2026`, `~4.225` hồ sơ / `350` chỉ tiêu, chọi `1/12,07`).
2. **Kỳ khảo sát chung ngày `01/07/2026` tại 5 trường THCS TP.HCM**:
   - Năm học `2026–2027`, kỳ khảo sát năng lực lớp 6 diễn ra chung vào sáng `01/07/2026` tại 5 trường trên địa bàn TP.HCM: `THCS và THPT Trần Đại Nghĩa`, `THCS Trần Quốc Toản 1`, `THCS Hoa Lư`, `THCS Bình Thọ`, và `THCS Nguyễn An Ninh`. Trong 5 trường, chỉ duy nhất bài khảo sát của Trần Đại Nghĩa có phần **Nghe tiếng Anh (English Listening)**.
3. **Độ dài đề bài (stem length) tăng gần gấp đôi**:
   - Số từ trung bình trên mỗi câu hỏi tăng từ vùng `33,3–47,9` từ/câu giai đoạn `2018–2020` lên vùng `69,4–79,4` từ/câu giai đoạn `2022–2026` (năm 2024: `79,4` từ/câu; năm 2025: `69,5` từ/câu; năm 2026: `79,3` từ/câu). Đề chuyển rõ rệt từ câu hỏi trực diện sang bài toán tình huống thực tế đòi hỏi năng lực đọc hiểu và lọc nhiễu thông tin.
4. **22,2% câu hỏi sử dụng hình vẽ, sơ đồ hoặc biểu đồ trực quan**:
   - Trong `370` câu hỏi đã số hóa (`244` câu trắc nghiệm + `126` câu tự luận), có `82` câu (`22,2%`) chứa hình minh họa. Riêng ở phần Trắc nghiệm bằng tiếng Anh, tỷ lệ câu có hình ảnh chiếm tới `26,6%` (`65/244` câu).
5. **60,3% câu hỏi kiểm tra kiến thức nền tảng và vận dụng chuẩn lớp 5**:
   - Phân bổ độ khó trên toàn bộ `370` câu hỏi gồm: **Dễ** `94` câu (`25,4%`), **Trung bình** `129` câu (`34,9%`), **Khá** `103` câu (`27,8%`), và **Thử thách** `44` câu (`11,9%`). Như vậy, nhóm câu nền tảng (`Dễ + Trung bình`) chiếm `60,3%` (`223/370` câu), trong khi nhóm phân hóa (`Khá + Thử thách`) chiếm `39,7%` (`147/370` câu).
   - Về thang điểm năm `2026`: Tổng điểm `100` chia thành `40` điểm Trắc nghiệm tiếng Anh (`20` câu trong `30` phút) và `60` điểm Tự luận (`60` phút), trong đó phần Tự luận chuyển từ cơ cấu `15/15/30` (năm 2025) sang cơ cấu cân bằng `20/20/20` (Toán & Tư duy logic `20` điểm; Đọc hiểu & Làm văn tiếng Việt `20` điểm; Tiếng Anh Nghe + Đọc/Viết `20` điểm).

---

## 2. Dataset Overview (English Summary for International Researchers & Kaggle Users)

This open educational dataset provides longitudinal admission metrics and item-level aggregate statistics across **11 official Grade 6 entrance survey cycles (`2015–2026`)** at **Tran Dai Nghia High School for the Gifted / Tran Dai Nghia Secondary & High School** in Ho Chi Minh City, Vietnam (`370` digitized questions total; the `2021–2022` survey was cancelled due to COVID-19 restrictions).

### Key Takeaways
- **Cutoff & Selectivity Trajectory**: Following the May 2024 institutional restructuring into Tran Dai Nghia Secondary & High School (`350` Grade 6 seats at 53 Nguyen Du, District 1), competition ratios reached `1/12.29` in 2024 (`4,301` applicants, cutoff `67.50/100`), `1/13.86` in 2025 (`4,851` applicants, cutoff `73.25/100`), and `1/12.07` on `01/07/2026` (`~4,225` applicants, cutoff `75.25/100`).
- **Reading Load Expansion**: Average stem length nearly doubled from `33–48` words per item (`2018–2020`) to `69–79` words per item (`2024–2026`), reflecting a shift toward multi-sentence real-world problem scenarios.
- **Visual Reasoning & Cognitive Distribution**: `22.2%` of all digitized items (`82/370`, and `26.6%` of English MCQs) require interpreting figures, diagrams, or spatial grids. Across the 11-year corpus, `60.3%` of items assess foundational and standard Grade 5 application (`Easy: 25.4%`, `Medium: 34.9%`), while `39.7%` serve as differentiating items (`Hard: 27.8%`, `Challenge: 11.9%`).
- **2026 Rubric Rebalancing**: The 90-minute assessment (`100` points total) comprises a 30-minute English MCQ section (`20` questions = `40` points) and a 60-minute written section (`60` points) rebalanced in 2026 to an equal `20/20/20` split across Math & Logical Reasoning (`20` pts), Vietnamese Reading & Essay (`20` pts), and English Listening + Reading/Writing (`20` pts, adjusted from 2025's `15/15/30` allocation).

---

## 3. Từ điển dữ liệu / Column Dictionary (`CSV` & `JSON`)

Bảng dưới đây mô tả chi tiết 20 trường dữ liệu trong tệp `thong-ke-de-thi-tran-dai-nghia-2015-2026.csv` và khóa tương ứng trong `thong-ke-de-thi-tran-dai-nghia-2015-2026.json`:

| Cột CSV (`CSV Column`) | Khóa JSON (`JSON Key`) | Kiểu dữ liệu (`Type`) | Mô tả tiếng Việt / English Description |
| --- | --- | --- | --- |
| `nam_thi` | `examYear` | `integer` | Năm tổ chức kỳ khảo sát (`2015` đến `2026`). / Calendar year of the entrance survey. |
| `nam_hoc` | `schoolYear` | `string` | Năm học tuyển sinh tương ứng (ví dụ: `2026-2027`). / Target academic school year. |
| `ngay_khao_sat` | `examDate` | `string (ISO 8601)` | Ngày tổ chức khảo sát chính thức (`YYYY-MM-DD`, ví dụ `2026-07-01`). Để trống nếu nguồn lưu trữ không ghi rõ ngày. / Official survey date. |
| `trang_thai` | `status` | `string` | Trạng thái kỳ thi: `khao_sat` (tổ chức thi khảo sát) hoặc `khong_khao_sat_covid19` (năm 2021 xét tuyển hồ sơ do dịch Covid-19). / Exam execution status. |
| `diem_chuan` | `cutoffScore` | `float` | Điểm chuẩn trúng tuyển đợt 1 trên thang điểm `100` (ví dụ: `75.25` năm 2026; `73.25` năm 2025; `67.50` năm 2024). Chỉ điền cho các năm đã đối chiếu từ ≥2 nguồn chính thức. / Official cutoff score out of 100. |
| `chi_tieu` | `quota` | `integer` | Chỉ tiêu tuyển sinh lớp 6 được Sở GD&ĐT TP.HCM giao (`350` giai đoạn 2024–2026; `525` giai đoạn 2022–2023). / Approved Grade 6 enrollment quota. |
| `applicants` | `applicants` | `integer` | Số lượng thí sinh đăng ký dự khảo sát (ví dụ: `4225` năm 2026; `4851` năm 2025; `4301` năm 2024). / Total registered applicants. |
| `competitionRatio` | `competitionRatio` | `string` | Tỷ lệ chọi thực tế theo định dạng `1/X` (ví dụ: `1/12.07` năm 2026; `1/13.86` năm 2025; `1/12.29` năm 2024). / Admission competition ratio (`quota / applicants`). |
| `ghi_chu_chi_tieu` | `quotaNote` | `string` | Ghi chú về quy mô chỉ tiêu của năm tương ứng. / Quota verification note. |
| `nguon_diem_chuan` | `cutoffSource` | `string` | Nguồn xác minh điểm chuẩn và hồ sơ (Thông báo Trường THCS & THPT Trần Đại Nghĩa, Sở GD&ĐT TP.HCM, báo chí chính thống). / Authoritative verification source. |
| `so_cau_so_hoa` | `digitizedQuestions` | `integer` | Tổng số câu hỏi của năm đó đã được số hóa trong kho dữ liệu OnThiTDN (tổng cộng `370` câu qua 11 kỳ thi). / Number of digitized items for the given year. |
| `trac_nghiem` | `multipleChoiceQuestions` | `integer` | Số câu hỏi thuộc phần Trắc nghiệm bằng tiếng Anh (chuẩn hiện hành: `20` câu / `30` phút). / Count of English multiple-choice questions. |
| `tu_luan` | `essayQuestions` | `integer` | Số câu hỏi/ý hỏi thuộc phần Tự luận đã số hóa (Toán tư duy, Tiếng Việt, Tiếng Anh tự luận & nghe). / Count of digitized written/constructed-response questions. |
| `so_cau_co_hinh` | `visualQuestions` | `integer` | Số câu hỏi có sử dụng hình vẽ, biểu đồ, bảng biểu hoặc lưới hình học trực quan. / Count of items containing figures, charts, or geometric diagrams. |
| `ti_le_co_hinh_pct` | `visualPercent` | `float` | Tỷ lệ phần trăm câu hỏi có hình minh họa (`%`, trung bình toàn bộ dữ liệu: `22.2%`). / Percentage of items with visual figures (`0–100`). |
| `do_dai_tb_tu_moi_cau` | `avgWordsPerQuestion` | `float` | Độ dài trung bình của phần đề bài (stem) tính theo số từ trên mỗi câu hỏi đã số hóa (tăng từ `33.3–47.9` lên `69.4–79.4` từ/câu). / Mean word count per question stem. |
| `muc_de` | `difficulty.de` | `integer` | Số câu hỏi ở mức độ **Dễ** (nhận biết, đọc hiểu trực tiếp — tổng `94` câu = `25.4%`). / Count of Easy items. |
| `muc_trung_binh` | `difficulty.trungBinh` | `integer` | Số câu hỏi ở mức độ **Trung bình** (vận dụng chuẩn kiến thức lớp 5 — tổng `129` câu = `34.9%`). / Count of Medium items. |
| `muc_kha` | `difficulty.kha` | `integer` | Số câu hỏi ở mức độ **Khá** (vận dụng tổng hợp, suy luận 2–3 bước — tổng `103` câu = `27.8%`). / Count of Hard/Differentiating items. |
| `muc_thu_thach` | `difficulty.thuThach` | `integer` | Số câu hỏi ở mức độ **Thử thách** (phân hóa cao, tư duy phi khuôn mẫu — tổng `44` câu = `11.9%`). / Count of Challenge items. |

*(Lưu ý: Trong tệp JSON còn có trường bổ sung `avgWordsMcOnly` phản ánh độ dài trung bình tính riêng cho 20 câu Trắc nghiệm tiếng Anh để thuận tiện so sánh đồng nhất với các năm chỉ số hóa phần trắc nghiệm.)*

---

## 4. Bảng tóm tắt dữ liệu 2015–2026 (Quick Preview Table)

| `nam_thi` | `nam_hoc` | `ngay_khao_sat` | `diem_chuan` | `chi_tieu` | `applicants` | `competitionRatio` | `so_cau_so_hoa` | `ti_le_co_hinh_pct` | `do_dai_tb_tu_moi_cau` | `Dễ + TB` | `Khá + Thử thách` |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **2026** | 2026–2027 | `2026-07-01` | **75.25** | 350 | 4225 | `1/12.07` | 38 | 21.1% | 79.3 | 20 | 18 |
| **2025** | 2025–2026 | `2025-06-16` | **73.25** | 350 | 4851 | `1/13.86` | 38 | 21.1% | 69.5 | 21 | 17 |
| **2024** | 2024–2025 | `2024-07-04` | **67.50** | 350 | 4301 | `1/12.29` | 36 | 22.2% | 79.4 | 19 | 17 |
| **2023** | 2023–2024 | — | **64.75** | 525 | 4800 | `1/9.14` | 36 | 11.1% | 69.4 | 18 | 18 |
| **2022** | 2022–2023 | — | **63.50** | 525 | 3570 | `1/6.80` | 37 | 16.2% | 73.9 | 20 | 17 |
| **2021** | 2021–2022 | *(Hủy do Covid-19)* | — | — | — | — | — | — | — | — | — |
| **2020** | 2020–2021 | — | — | — | — | — | 26 | 38.5% | 33.3 | 14 | 12 |
| **2019** | 2019–2020 | — | — | — | — | — | 20 | 45.0% | 40.8 | 12 | 8 |
| **2018** | 2018–2019 | — | — | — | — | — | 20 | 20.0% | 47.9 | 12 | 8 |
| **2017** | 2017–2018 | — | — | — | — | — | 36 | 13.9% | 59.8 | 25 | 11 |
| **2016** | 2016–2017 | — | — | — | — | — | 42 | 19.0% | 75.0 | 31 | 11 |
| **2015** | 2015–2016 | — | — | — | — | — | 41 | 29.3% | 62.5 | 31 | 10 |

---

## 5. Hướng dẫn sử dụng nhanh bằng Python (Quick Start in Python / Pandas)

```python
import pandas as pd

url = "https://onthitdn.com/tai-lieu/thong-ke-de-thi-tran-dai-nghia-2015-2026.csv"
df = pd.read_csv(url)

# Lọc các năm có khảo sát thực tế (loại trừ năm 2021 hủy thi do Covid-19)
conducted = df[df["trang_thai"] == "khao_sat"].copy()

print("Tổng số câu hỏi đã số hóa:", int(conducted["so_cau_so_hoa"].sum()))
print(
    conducted[
        [
            "nam_thi",
            "diem_chuan",
            "chi_tieu",
            "applicants",
            "competitionRatio",
            "do_dai_tb_tu_moi_cau",
        ]
    ].head(5)
)
```

---

## 6. Giấy phép & Cách trích dẫn nguồn (License & Citation)

Bộ dữ liệu này được phát hành theo giấy phép **Creative Commons Attribution 4.0 International ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/))**. Bạn được tự do chia sẻ, trích xuất, vẽ biểu đồ và sử dụng cho mục đích báo chí dữ liệu, nghiên cứu giáo dục hoặc ứng dụng học tập, với điều kiện ghi nhận nguồn gốc như bên dưới.

### Trích dẫn dạng Markdown / HTML (For Articles, Blogs & Press)

```markdown
Nguồn dữ liệu: [Báo cáo thống kê 11 năm đề khảo sát, tỷ lệ chọi và điểm chuẩn lớp 6 Trần Đại Nghĩa (2015–2026) — OnThiTDN](https://onthitdn.com/blog/thong-ke-de-thi-tran-dai-nghia-2015-2026) (Giấy phép CC-BY-4.0).
```

### Trích dẫn học thuật BibTeX (For Academic & Data Journalism Citations)

```bibtex
@dataset{onthitdn_tdn_grade6_dataset_2026,
  author       = {{Ban Chuyên Môn OnThiTDN}},
  title        = {{Thống kê đề thi, tỷ lệ chọi và điểm chuẩn khảo sát lớp 6 Trường THCS và THPT Trần Đại Nghĩa (2015–2026)}},
  year         = {2026},
  month        = {11},
  publisher    = {OnThiTDN},
  version      = {2026.11},
  license      = {CC-BY-4.0},
  url          = {https://onthitdn.com/blog/thong-ke-de-thi-tran-dai-nghia-2015-2026},
  note         = {Open CSV and JSON dataset analyzing 370 digitized exam questions across 11 survey cycles in Ho Chi Minh City}
}
```
