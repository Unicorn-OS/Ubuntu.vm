# Solution: works
https://unix.stackexchange.com/questions/687485/ubuntu-ext4-partition-is-not-being-extended-or-resized-as-expected-with-growpart

https://discuss.linuxcontainers.org/t/root-partition-size-in-profile-not-applied-to-vm/7529/5

```
growpart /dev/vda 1
resize2fs /dev/vda1
```
