# Learning Outline 

## Content

The workshop is divided into the following three sections:

### The Unix Shell

The aim of this section is to teach learners basic unix commands in 
order to help them interact with a HPC infrastructure. This may entail:

- filesystem navigation and manipulation
- different command line and bash scripts
- remote sessions with `ssh`


### Clusters and Distributed Computing Infrastructure

This section is meant to convey a simplistic mental model of the cluster,
and how tasks get submitted, assigned and executed on the cluster.

Towards the end of the section, learners will submit a (number of) "Hello World" 
style batch job(s) that are aligned to the Unix Shell section above.

The session concludes by introducing and practising `environment modules` based 
on the observation that software on HPC and for HPC systems is very diverse a
nd subject to change. 

### Paradigms of Parallel Computing

This section will guide learners through the process of
performing a large HPC simulation (code available),
and a high-throughput analysis (code available) of related data. The end 
goal will be to compare the simulation to the data (i.e. to relate their actions on a HPC installation to the scientific method).

For this, they will develop the workflow for a specific research scenario,
for example:

> Lola was hired by a research lab to help prepare the purchase of a multi-million dollar experiment.
The experiment is known to fail at temperatures that are too low or too high.
She knows that the temperature changes follow a daily pattern,
and she's written some code to simulate these temperature changes.
After running this code and generating the temperature predictions,
she determines how closely her predictions match the actual temperature readings
she has for every day in the last year.
The simuation would take too long to run
and generate too much data for her lab workstation,
so she will use the local University's HPC facility for this work.

### Timing

1.  Introduction to the Unix Shell [90 min]

	a.  Navigating the file system (`ls`, `cd`, `pwd`, `cp`, `rm`, `mv`) [30 min] 

    b.  commands and scripts [30 min]

	c.  taking the space shuttle `ssh` to another planet [15 min]

	d.  transferring files to/from a remote host (`scp`, `rsync`) [15 min]


2.  Clusters and Distributed Computing Infrastructure [45-60 min]

	a. the scheduling problem and our first "Hello World" [20 min]

	b. distributed file systems [15 min]

	c. revisiting "Hello World" using input/output [15 min]


3.  Paradigms of Parallel Computing [90 min] 

	a. calculating with many distributed systems (MPI, shared-memory parallelisation) [30 min]

	b. data-parallel computations (`map-reduce`) [30 min]

	c. what this is all for? [30 min]



> All timings above should be considered lower bounds and shall be subject to change once more workshop instances of this material are performed.
