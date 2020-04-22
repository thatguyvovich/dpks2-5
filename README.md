# dpks2-5
Lab5 of RDCS.

## What is this?
This is a module, which allocates memory according to the custom parameter `hello_param`. 

## How to compile?
Use `make`.

## How to run?
Use `insmod hello_param=[number]`.

## What does it do?
It allocates memory for the custom data structure which encapsulates time stamps before `printk` function is called and after. Upon using `rmmod`, module prints out information on how long `printk` took.
