# Trust Region Bayesian Optimization of Annealing Schedules on a Quantum Annealer

**Seon-Geun Jeong<sup>1</sup>, Mai Dinh Cong<sup>1</sup>, Minh-Duong Nguyen<sup>2</sup>, Xuan Tung Nguyen<sup>3</sup>, Quoc-Viet Pham<sup>4</sup> and Won-Joo Hwang<sup>1,5,*</sup>**

<sup>1</sup> Department of Information Convergence Engineering, Pusan National University, Busan, Republic of Korea  
<sup>2</sup> Department of Intelligent Computing and Data Science, VinUniversity, Hanoi, Vietnam  
<sup>3</sup> Faculty of Interdisciplinary Digital Technology, Phenikaa University, Yen Nghia, Vietnam  
<sup>4</sup> School of Computer Science and Statistics, Trinity College Dublin, Dublin, Ireland  
<sup>5</sup> School of Computer Science and Engineering, Pusan National University, Busan, Republic of Korea  

**Keywords:** Annealing schedule, Bayesian optimization, Fourier-parameterized annealing schedule, quantum annealing

---

## 📝 Abstract
> Quantum annealing (QA) is a practical model of adiabatic quantum computation, already realized on hardware and considered promising for combinatorial optimization. However, its performance is critically dependent on the annealing schedule due to hardware decoherence and noise. Designing schedules that account for such limitations remains a significant challenge. We propose a trust region Bayesian optimization (TuRBO) framework that jointly tunes annealing time and Fourier-parameterized schedules. Given a fixed embedding on a quantum processing unit (QPU), the framework employs Gaussian process surrogates with expected improvement to balance exploration and exploitation, while trust region updates refine the search around promising candidates. The framework further incorporates mechanisms to manage QPU runtime and enforce feasibility under hardware constraints efficiently. Simulation studies demonstrate that TuRBO consistently identifies schedules that outperform random and greedy search in terms of energy, feasible solution probability, and chain break fraction. These results highlight TuRBO as a resource-efficient and scalable strategy for annealing schedule design, offering improved QA performance in noisy intermediate-scale quantum regimes and extensibility to industrial optimization tasks.
