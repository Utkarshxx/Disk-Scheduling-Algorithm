# Disk Scheduling Algorithms

## Algorithms Implemented
1. First-Come, First-Served (FCFS)
2. Shortest Seek Time First (SSTF)
3. SCAN (Elevator Algorithm)
4. C-SCAN (Circular SCAN)
5. LOOK
6. C-LOOK

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/disk-scheduling-algorithms.git
   cd disk-scheduling-algorithms
   ```

2. Compile and run:
   ```bash
   g++ disk_scheduling.cpp -o disk_scheduling
   ./disk_scheduling
   ```

3. Enter:
   - Initial head position
   - List of disk requests
   - Algorithm to use

## Input Format
- Initial head position (e.g., 50)
- List of requests (e.g., 82, 170, 43, 140, 24, 16, 190)
- Direction (for SCAN, C-SCAN, LOOK, C-LOOK)

## Output
- Order of requests serviced
- Total head movements
- Average seek time

## Example Output
```
FCFS Algorithm:
Request sequence: 50 → 82 → 170 → 43 → 140 → 24 → 16 → 190
Total head movements: 642 cylinders
Average seek time: 91.71
```

## Dependencies
- C++ compiler
- Python 3.x

## License
MIT License
