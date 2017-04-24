# MIPS Assembler

This project is the homework of Computer Organization course in ZJU. You could find the source code from
[Github](https://github.com/netaddi/oreAssembler)

## compile

this project is based on **electron**. To run it with source code, first install node.js and npm, cd to the source directory, and run
```bash
npm install
npm start
```

for the precompiled package ( submitted as homework ), simply run ```oreAssembler.exe``` to start it.

## usage

### the two editors

the editor in the left side is for displaying and editing MIPS assembly code, while the one at the right side is for displaying machine instructions.

Note that although it is also editable, but your edit will **not** effect anything. The machine instruction code could only be changed by opening binary file or assembling some code.

### laod a file

in the File menu, you could open asm, coe and bin file. asm file is opened in the left editor while the other two in the right one.

### assemble and deassemble

To assemble or deassemble something, click the button in the main area. The assemble source is the assemble code in the left area, you could type it by yourself or open from a file. The deassemble source is the binary machine instruction opened from *bin* or *coe* file, or generated by assemble function.

### save the generated content

After assembling of deassembling something, you could write them to file by using Save options in the menu.

*Save asm* options saves the content in the left-side editor to file, while the other two options save the assembled contents.
