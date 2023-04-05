# JobSchedulers.jl

*A Julia-based job scheduler and workload manager inspired by Slurm and PBS.*


| **Documentation**                                                               |
|:-------------------------------------------------------------------------------:|
| [![](https://img.shields.io/badge/docs-stable-blue.svg)](https://cihga39871.github.io/JobSchedulers.jl/stable) [![](https://img.shields.io/badge/docs-dev-blue.svg)](https://cihga39871.github.io/JobSchedulers.jl/dev) |

## Why JobScheduler?

We may find different tasks or programs use different CPU and memory. Some can run simultaneously, but some have to run sequentially. JobScheduler is stable, useful and powerful for task queuing and workload management. 

## Package Features

- Job and task scheduler.
- Local workload manager.
- Support CPU, memory, run time management.
- Support running a job at specific time, or a period after creating (schedule).
- Support deferring a job until specific jobs reach specific states (dependency).
- Support automatic backup and reload.
- Fancy progress meter in terminal.

  ![progress meter](docs/src/assets/progress_meter.png)

## Future development

- Support command-line scheduler by using DaemonMode.jl.

## Installation

JobSchedulers.jl can be installed using the Julia package manager. From the Julia REPL, type ] to enter the Pkg REPL mode and run

```julia
pkg> add JobSchedulers
```

To use the package, type

```julia
using JobSchedulers
```

## Documentation

- [**STABLE**](https://cihga39871.github.io/JobSchedulers.jl/stable) &mdash; **documentation of the most recently tagged version.**
- [**DEVEL**](https://cihga39871.github.io/JobSchedulers.jl/dev) &mdash; *documentation of the in-development version.*
