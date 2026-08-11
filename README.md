#这是Ypres的ASC入队考核作业_HPL小题代码仓库。
复现方式：
```bash
git clone git@github.com:Ypreeeeeeeees/HPL_assignment.git
cd HPL_assignment
# 配置 Makefile（Linux + OpenBLAS + OpenMPI）并 make arch=...
mpirun -np 16 ./xhpl   # 读取当前 HPL.dat
```

关键日志与结果位于仓库根目录 output_N/、output_Nbs/、output_PQs/。
