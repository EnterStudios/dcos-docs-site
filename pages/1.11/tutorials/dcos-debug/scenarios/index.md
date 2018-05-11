<!-- IV. Hands On Examples Section -->

<a name=hands-on></a>

# Hands On: Debugging Application Deployment on DC/OS

In this section, there are three basic debugging scenarios for practice. We encourage you to try to debug these scenarios without the solution before skipping to the solution.

## Prerequisites

- running [DC/OS cluster](/1.11/installing/oss/)
    - 4 private agent nodes
    - 1 public agent node
- configured [DC/OS CLI](https://docs.mesosphere.com/1.11/cli/install/)

Note that these exercises require a running [DC/OS cluster](/1.11/installing/oss/) and a configured [DC/OS CLI](https://docs.mesosphere.com/1.11/cli/install/). We are also using a cluster with 4 private agents and 1 public agent *that has not been running any workloads prior*. Of course then, your results may vary if using an alternative cluster setup.