# 1. getSize( originalDisk )
https://unix.stackexchange.com/questions/52215/determine-the-size-of-a-block-device

example:
`blockdev --getsize64 /dev/nvme0n1`

# 1. createQcow2( originalDisk.Size )
https://www.ibm.com/docs/en/linux-on-systems?topic=commands-qemu-image-command

example:
`qemu-img create -f qcow2 Laptop1.img 512110190592`
