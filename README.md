# Optimising Student Project and Second Marker Allocation with Heuristics & Metaheuristics

This project tackles the **student project allocation (SPA)** problem and the linked task of **second marker assignment** under realistic institutional constraints. Developed as part of my **MSc extended research project at The University of Manchester (2025)**.  


## Methods & Findings
- **Staged Hill Climbing** applied as a transparent baseline.  
- **Neighbourhood benchmarking (N1–N5)** showed similar allocation quality, with runtime differences.  
- **Hybrid staged Hill Climbing** combined operators for stable and efficient outcomes.  
- **Simulated Annealing** offered negligible gains over hybrid while taking >3 hours (vs ~15 minutes).  
- **Weighted Hill Climbing** achieved stronger optimisation but relied on subjective weights, reducing transparency.  
- **Second Marker Allocation** implemented as a separate optimisation stage, balancing workloads effectively though consistency across projects remained harder to enforce.  
- **Neighbourhood benchmarking (N1–N5)** identified N1 as the most effective operator, which was subsequently adopted for the final allocation.

**Results:**  
- 87% of students received one of their top three choices, 69% recieved their first choice.  
- Supervisor workloads remained balanced across allocations.  
- Second marker loads were well-distributed, though some inconsistency persisted.  


## Repository Structure
- `code/` – Python scripts and notebooks  
- `data/` – Input datasets  
- `results/` – Allocation outputs and reports    


## Environment

The code was tested with:  
- Python 3.12.4  
- pandas 2.2.2  
- numpy 1.26.4  


