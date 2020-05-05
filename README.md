# nolox
Attempt to create a toy OS kernel without locks

# Main design ideas

* Supports only x86_64 for now
* Supports only VIRTIO devices - console, block and input devices
* Monolithic kernel
* Syscall interface is batch-oriented
* Non-preemptive scheduling inside kernel, fully preemptive outside kernel
