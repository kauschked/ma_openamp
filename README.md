# Master thesis: Development and evaluation of asymmetric multiprocessing on a heterogeneous multiprocessor system

This repository is used for hosting my master's thesis.

# Abstract

Heterogeneous multiprocessor systems (MPSoC) have become increasingly popular for industri-
al applications in recent years due to their high performance, lower costs and energy efficiency.
Especially the many different integrated processors running different operating systems, also
known as asymmetric multiprocessing (AMP), pose many challenges. The two biggest chal-
lenges are lifecycle management (LCM) and interprocessor communication (IPC). This thesis
investigates the structure of heterogeneous MPSoCs and the use of different operating systems.
Based on the decisions for the selection of the used AMP architecture, a heterogeneous MPSoC
and the selection of a framework as a solution for the two challenges the development of an
AMP system is done. Subsequently, the implementation of the developed AMP system with the
selected framework OpenAMP on the selected MPSoC i.MX8X from NXP is carried out with
an embedded Linux on the ARM Cortex-A35 and a FreeRTOS on the ARM Cortex-M4. For the
evaluation of the implemented AMP system, process data monitoring and hardware-in-the-loop
latency and data throughput will be measured on the i.MX8X based on the two application
scenarios developed. Among other things, the results show that the maximum latency from
Linux user space to FreeRTOS with the use of the RT patch is 628 µs and the data throughput
is 4.08 MB/s. From the results it can be deduced that the use of the implemented AMP system
is suitable for the presented application scenarios and the IPC for soft real-time.
