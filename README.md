# CycleHeap Adaptive Stable Sort

**CycleHeap Sort** is a novel, production-ready hybrid sorting algorithm that merges the optimal behaviors of Cycle Sort, Heap Sort, and MergeSort into one stable, adaptive solution.

🔹 **Stable** – preserves the order of equal elements  
🔹 **Adaptive** – performs faster on partially sorted or structured data  
🔹 **Memory-Efficient** – near in-place sorting  
🔹 **Scalable** – performs competitively up to 1M+ elements  
🔹 **Ideal for B2B & Cloud** – reliable for structured datasets in real-world systems

---

## 🚀 Why CycleHeap?

Modern data pipelines, especially in business-to-business (B2B), analytics, and cloud services, often require:

- **Fast, deterministic performance**
- **Stability for tabular & indexed data**
- **Adaptivity to pre-sorted input**
- **Compatibility with `pandas`, `numpy`, or Dask workloads**

CycleHeap addresses all of this — and more — while keeping the implementation lightweight and understandable.

---

## 📦 Installation

```bash
pip install cycleheap-sort



##  Usage

```python
from cycleheap_sort import cycleheap_adaptive_stable_sort
import pandas as pd

df = pd.DataFrame({
    'company_id': [3, 1, 2],
    'timestamp': [200, 100, 300]
})

sorted_df = cycleheap_adaptive_stable_sort(df, 'company_id', 'timestamp')
print(sorted_df)
```

## Author

Created by Adnan Mohsen (adammohse@yahoo.com) & ChatGPT
