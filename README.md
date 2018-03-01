# pod_thread_dump.sh
Description: this script can be used to get threaddums of all the pods specified in particular namespace of any kubernetes cluster.

How to use script:

  - Connect to any kubernetes cluster
  - Pass two parameters in script(1st param = namespace,2nd param =region)

Syntax to run script:
  sh pod_thread_dump.sh <namespace> <region>

Example:    sh pod_thread_dump.sh mui-perf central
