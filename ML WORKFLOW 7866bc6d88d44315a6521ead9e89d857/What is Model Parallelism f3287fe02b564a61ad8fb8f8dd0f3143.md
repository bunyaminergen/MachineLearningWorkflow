# What is Model Parallelism

Model parallelism is a technique used in parallel computing to split a large machine learning model across multiple
processors or machines, with each processor or machine handling a specific part of the model. The goal of model
parallelism is to speed up t he training and inference of large models by dividing the work across multiple processors
or machines.
In model parallelism, the model is split into smaller sub
models, each one of which can fit into the memory of a
single machine or processor. The sub models are then distributed across multiple machines or processors, with
each one handling a specific part of the model. The results from each machine or processor are then combined to
produce the final result. This is often used in cases where the model is too large to fit into the memory of a single
machine, and therefore it needs to be split across multiple machines.
Model parallelism can be used in various applications such as deep learning, where large models are used for
training and inference. In deep learning, model parallelism is often used to train models on multiple GPUs or
distributed systems. This allows the model to be trained on larger datasets and achieve better performance.
It's worth noting that model parallelism can be used in conjunction
with data parallelism, where the data is split
across multiple machines or processors, and the model is split across multiple machines or processors as well. This
way both the model and data can be processed in parallel, which can lead to a significant spe edup in the training
and inference process.