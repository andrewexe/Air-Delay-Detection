# ✈️ Air Delay Detections

A lightweight data analysis tool for parsing and sorting U.S. airline delay datasets. This project helps identify bottlenecks, frequent delay origins, and performance by carrier, airport, or date.

---

## 📊 Features

- 🚨 Sort flights by **delay length**, **origin**, **destination**, **carrier**
- 📅 Filter delays by **month**, **day of week**, **holiday windows**
- 📈 Generate visualizations for **airline performance**, **peak delay hours**
- 🧹 Efficiently handles large CSV files (millions of records)
- ⚙️ Command-line support for quick sorting and filtering

---

## 🗂️ Example Fields in the Dataset

- `FL_DATE`, `OP_CARRIER`, `ORIGIN`, `DEST`
- `DEP_DELAY`, `ARR_DELAY`, `CANCELLED`, `DIVERTED`
- `CRS_DEP_TIME`, `CRS_ARR_TIME`

---

## 🧪 Usage

### 1. Clone the repo
```bash
git clone https://github.com/your-username/air-delay-detections.git
cd air-delay-detections
