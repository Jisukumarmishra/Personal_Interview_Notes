Super key Any set of columns that uniquely identifies a row
Candidate key A minimal super key

Starvation: A process waits indefinitely because others keep getting priority.
Aging: Gradually increases the priority of waiting processes to reduce starvation.
Turnaround time = Completion time − Arrival time.
Waiting time = Turnaround time − Total CPU burst time.
Response time = First CPU start time − Arrival time.

C. Deadlock — four necessary conditions
A deadlock can occur when all four conditions hold:

1. Mutual exclusion: At least one resource cannot be shared.
2. Hold and wait: A process holds resources while waiting for others.
3. No preemption: Resources cannot be forcibly taken away under the relevant policy.
4. Circular wait: Processes form a circular chain, each waiting for a resource held by the next.

Ways of handling deadlock:

- Prevention: Design the system so at least one necessary condition cannot hold.
- Avoidance: Grant requests only when doing so keeps the system in a safe state.
- Detection and recovery: Detect deadlocks and take corrective action.
- Ignore: Some systems choose not to handle certain deadlocks explicitly.

Deadlock vs starvation: Deadlock involves a circular waiting situation; starvation is indefinite waiting due to unfair allocation or scheduling.

What is Synchronization?

Process Synchronization is a mechanism that coordinates multiple processes or threads accessing shared resources to maintain data consistency and prevent race conditions.

Race Condition
Jab multiple processes ya threads shared data ko concurrently access karte hain aur final result execution order par depend karta hai.

. Critical Section

Program ka woh part jahan shared resources ko access ya modify kiya jata hai

Memory management
Paging: Divides virtual memory into fixed-size pages and physical memory into fixed-size frames.

Segmentation: Divides a program's memory into logical, variable-sized segments, such as code, data, and stack.

Virtual memory: Allows programs to use an address space larger than available physical RAM by keeping parts of memory on secondary storage when needed.

What happens when you enter a URL in a browser?
This is an excellent scenario-based interview question.

1. The browser parses the URL.
2. It determines the destination hostname and resolves it through DNS if necessary.
3. It establishes a connection to the destination, normally using TCP for HTTP/1.1 or HTTP/2, and typically QUIC over UDP for HTTP/3.
4. For HTTPS, TLS security is established through the relevant protocol.
5. The browser sends an HTTP request.
6. The server processes the request and sends an HTTP response.
7. The browser parses HTML, downloads required assets, executes JavaScript, and renders the page.
   Caching, connection reuse, proxies, and other optimizations can change the exact sequence.
