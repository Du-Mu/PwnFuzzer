# PwnFuzzer

A fuzzer tools write by golang, used for interactive program.

The idea come from [syzkaller](https://github.com/google/syzkaller), which abstract input into a series of system calls.

Similarly, the Pwn-Fuzzer abstract input into a series of interactive program.

## TODO
- [ ] pwn-manager
  - [ ] manage the program instance and generate input 
- [ ] pwn-runner
  - [ ] run the program instance and get the result
