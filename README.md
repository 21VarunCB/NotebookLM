# Operating Systems (Unit-3: Memory Management) AI Companion

An interactive knowledge base and study companion built on NotebookLM, grounded in comprehensive Operating Systems course lectures (UE24CS242B / UE25CS242A).

## Repository Contents
- `/docs/`: Source documents and lecture summaries (Modules 3.1 to 3.8).
- `/evaluations/`: Test query sets and verified answer traces.
- `README.md`: System overview and architecture details.

## Topics Covered
- **Hardware & Addressing**: Logical vs. physical address space, MMU, memory protection.
- **Allocation & Fragmentation**: Contiguous allocation, first-fit/best-fit/worst-fit, compaction.
- **Paging & Segmentation**: Page tables, TLB hits/misses, address translation, segmentation tables.
- **Virtual Memory & Thrashing**: Demand paging, page fault handling, LRU/FIFO/Optimal page replacement, Working-Set Model.

## Usage & Prompts
To query the knowledge base, use structured prompts such as:
- `Compare paging and segmentation with respect to programmer view and hardware support.`
- `Calculate the Effective Access Time (EAT) given a 20ns TLB search and 100ns memory access time at an 80% hit ratio.`
- `Trace LRU page replacement for reference string: 7, 0, 1, 2, 0, 3, 0, 4, 2, 3 with 3 frames.`
