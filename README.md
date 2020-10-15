# java-lesson
for java experiment


## 实验目的
用类描述计算机中CPU的速度和硬盘容量

## 实验方法
1.阅读书上例子7-9
2.用eclipse进行编程
3.上传至github并撰写报告

## 实验过程
1.创建project，并在其下创建package，在package下创建CPU、PC、Test、HArdDisk四个class，根据需求分别将四个功能写入。
2.将Test作为主类，在其中进行其他类形参和实参的对应和输出。
3.在main方法中创建一个CPU对象cpu，cpu将自己的speed设置为2200
4.在main方法中创建一个HardDisk对象disk，disk将自己的amount设置为200
5.main方法创建一个PC对象pc
6.pc调用setCPU(CPU c)方法，调用时实参是cpu
7.pc调用setHardDisk(HardDisk h)方法，调用时实参是disk
8.pc调用show()方法

## 核心方法
'''
CPU cpu=new CPU(); 

    cpu.speed=2200; 

    HardDisk disk=new HardDisk();

    disk.amount=200; 

    PC pc=new PC();

    pc.setCPU(cpu);

    pc.setHardDisk(disk);

    pc.show();
'''

## 实验结果
CPU的速度2200
硬盘的容量200

## 实验感想
经过这次实验，我基本熟悉了Java中project package和class之间的关系，明晰了形参和实参的对应关系，以及show方法的用法。 

