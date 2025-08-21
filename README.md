# algo-cycleheap-sort-
# CycleHeap Sort

A novel stable hybrid sorting algorithm inspired by Cycle Sort, Heap Sort, and MergeSort principles. 
Designed for efficient B2B data pipelines with minimal writes and strong stability guarantees.

## Install

```bash
pip install cycleheap_sort
```

## Usage

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
