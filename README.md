# Streaming Frequent Pattern Mining

This project implements streaming data mining algorithms including:
- DGIM (Datar-Gionis-Indyk-Motwani) for counting 1s in a binary stream
- Lossy Counting for approximate item frequencies
- Sliding Window Frequent Itemset Miner for decaying streams

## Files
- `main.py`: Runs all tests and demos
- `dgim.py`: DGIM implementation
- `lossy_counting.py`: Lossy Counting implementation
- `windowed_lossy_counting.py`: Sliding window item frequency miner
- `simulate_data.py`: Simulated clickstream and IoT data generators

## How to Run
```bash
python main.py
