+----------------------+
| Market Data Source   |
| (Simulated prices)   |
+----------+-----------+
           |
           v
+----------------------+
| Queue                |
| (Incoming prices)    |
+----------+-----------+
           |
           v
+----------------------+
| Priority Queue       |
| (Select best trade)  |
+----------+-----------+
           |
           v
+----------------------+
| Sorting Module       |
| (Volume-based sort)  |
+----------+-----------+
           |
           v
+----------------------+
| Trade Decision       |
+----------------------+
