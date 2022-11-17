command to run :
		./qemu-system-riscv64 -M sifive_x280_rtl_rev1  -bios fw_jump.elf  -kernel uImage--5.17.x+git0+70a10e90d4-r0-qemuriscv64-20221116134927.bin 
  -initrd gyt-image-minimal-qemuriscv64-20221116134927.rootfs.cpio.gz -nographic -smp cpus=2 -m 512
