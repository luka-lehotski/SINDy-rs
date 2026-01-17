# SINDy-rs

SINDy - Sparse Identification of Nonlinear Dynamics (Brunton, Kutz, Proctor 2016), is a method for discovering ODE describing desired dynamical system. It aims to find the sparse solution (least possible equation). We can use Sparce matrix algorithms and parallelization to speed up computation.

<img width="850" height="338" alt="image" src="https://github.com/user-attachments/assets/76e9b9e9-6f4b-42ae-9ec7-205dd74be1fc" />

What i specifically like about this method is that is interpretable, compared to PINNs (which aims to solve some of the same problems). 

This method is widely applicable, and powerful tool for identification and prediction in systems. My goal in this project is to build up a library adjectent to original PySINDy in RUST, since it enables memory safety, speed, and verification, which is important when dealing with matrix multiplications.
