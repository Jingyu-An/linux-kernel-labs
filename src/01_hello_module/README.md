# Lab 01 — Hello Kernel Module

This lab introduces the basics of building and loading a Linux kernel module.

## Features
- Basic module init/exit
- printk log messages
- Module metadata (license, author, description)

## Commands

```bash
make
sudo insmod hello.ko
dmesg | tail

sudo rmmod hello
dmesg | tail