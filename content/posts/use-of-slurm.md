+++
title = '关于Slurm任务调度系统的笔记'
date = 2023-09-27T15:50:44+08:00
draft = true
+++

- 同时提交多个节点的任务, 但是不同的节点运行的任务不同;

```bash
sbatch -N3 -n3 -c (task_name) ./run.sh
```