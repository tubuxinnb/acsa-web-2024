---
title: "NDPage: Efficient Address Translation for Near-Data Processing Architectures via Tailored Page Table"
FirstAuthor:
- Qingcai Jiang
- Buxin Tu
OtherAuthors:
- Hong An
ConfJournal: "28th Design, Automation and Test in Europe Conference"
ConfJournalAbbr: DATE
IsAConference: "yes" # 会议填yes，期刊写 no
CCFLevel: "B" 
Year: 2025
Award: ""
Abstract: "We propose NDPage, an efficient page table design tailored for NDP systems. The key mechanisms of NDPage are (1) an L1 cache bypass mechanism for PTEs that not only accelerates the memory accesses of PTEs but also prevents the pollution of PTEs in the cache system, and (2) a flattened page table design that merges the last two levels of page tables, allowing the page table to enjoy the flexibility of a 4KB page while reducing the number of PTE accesses. We evaluate NDPage using a variety of data-intensive workloads."
KeyWords:
- Deep learning
- Right ventricle reconstruction
- Multi-view echocardiogram
- Dual-aware network

Link: # 官网链接 
PDF: # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Near-Data Processing (NDP) has been a promising architectural paradigm to address the memory wall problem for data-intensive applications. Practical implementation of NDP architectures calls for system support for better programmability, where having virtual memory (VM) is critical. Modern computing systems incorporate a 4-level page table design to support address translation in VM. However, simply adopting an existing 4-level page table in NDP systems causes significant address translation overhead because (1) NDP applications generate a lot of address translations, and (2) the limited L1 cache in NDP systems cannot cover the accesses to page table entries (PTEs). We extensively analyze the 4-level page table design in the NDP scenario and observe that (1) the memory access to page table entries is highly irregular, thus cannot benefit from the L1 cache, and (2) the last two levels of page tables are nearly fully occupied. Based on our observations, we propose NDPage, an efficient page table design tailored for NDP systems. The key mechanisms of NDPage are (1) an L1 cache bypass mechanism for PTEs that not only accelerates the memory accesses of PTEs but also prevents the pollution of PTEs in the cache system, and (2) a flattened page table design that merges the last two levels of page tables, allowing the page table to enjoy the flexibility of a 4KB page while reducing the number of PTE accesses. We evaluate NDPage using a variety of data-intensive workloads. Our evaluation shows that in a single-core NDP system, NDPage improves the end-to-end performance over the state-of-the-art address translation mechanism of 14.3\%; in 4-core and 8-core NDP systems, NDPage enhances the performance of 9.8\% and 30.5\%, respectively.
