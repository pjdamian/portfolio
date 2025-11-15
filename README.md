# portfolio
Hi, I'm Peter, I enjoy all things coding and data. This portfolio showcases how I think and approach problems.

---

## Projects

### Circuit Simulator (Modified Nodal Analysis)

**Repo:** https://github.com/pjdamian/circuit-simulator  
**Tech:** Python, NumPy, NetworkX  
**Skills Demonstrated:** Numerical methods, circuit theory, OOP design, algorithm implementation, testing  

**Summary:**  
A DC network solver built using Modified Nodal Analysis (MNA). Supports resistors, voltage sources (with internal resistance), and ideal switches. Includes node voltage and branch current reporting, isolated node pruning, ground selection, and physics verification through series and parallel test circuits. Fully unit-tested and structured for extensibility.

**Highlights:**
- Full MNA assembly (`A x = b`) with voltage-source current unknowns  
- Component-oriented architecture (Resistor, VoltageSource, Switch)  
- Automatic graph-based topology handling via NetworkX  
- Node and branch reporting with clear sign conventions  
- Physics-checked examples (Ohm’s law verification, KCL validation)  
- Test suite using `pytest` 
