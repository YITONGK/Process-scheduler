# Process-scheduler
How to use:
./allocate -f <filename> -s (SJF | RR) -m (infinite | best-fit) -q (1 | 2 | 3)
-f filename will specify a valid relative or absolute path to the input file describing the processes.
-s scheduler where scheduler is one of {SJF, RR}.
-m memory-strategy where memory-strategy is one of {infinite, best-fit}.
-q quantum where quantum is one of {1, 2, 3}.
