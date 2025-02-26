# VSDSQuadronMini_RISCV_Research_Internship
A practical internship focused on RISC-V development using the VSDSQuadron Mini, covering setup, instruction analysis, simulation, and real-world embedded system applications.

![image](https://github.com/user-attachments/assets/0f0091ae-8a07-4903-ac24-8c1342084913)
<details>
<summary><big><b>TASK-1 : </b></big>The objective of this task is to set up the necessary software environment for the internship. This includes installing Ubuntu on VirtualBox, configuring Visual C++, and writing a simple C program. Additionally, the task involves evaluating the corresponding RISC-V assembly code generated from the sample C code. </summary>
<img width="810" alt="Screenshot 2025-02-26 at 11 37 34 PM" src="https://github.com/user-attachments/assets/7d60cb73-01ef-47b8-affe-5ab86f572497" />
<h3>Step:1 </h3>

<h3>Step:2 Create a sample C code</h3>
<p>Install Leafpad, a lightweight text editor for Ubuntu.</p>
<p><blockquote>$ sudo apt install leafpad</blockquote></p>
<p>Create a new C file and write a basic code for compilation</p>
<p><blockquote>$ leafpad sum1ton.c &</blockquote></p>

<h3>Step:3 Compile the C Code with basic GCC Compiler</h3>
<p>After writing a basic C code, compile the C code</p>
<p><blockquote>$ gcc sum1ton.c</blockquote></p>
<p>Now, Run the compiled C code</p>
<p><blockquote>$ ./a.out</blockquote></p>

<h3>Compile the C Code with RISC-V Compiler</h3>
<p>Compilation of the C code using RISC-V compiler:</p>
<p><blockquote>$ riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c</blockquote></p>

<h3>Step 5: Display The Assembly Code</h3>
<p>To Display the optimized assembly code for the main function:</p>
<p><blockquote>$ riscv64-unknown-elf-objdump -d filename.o | less</blockquote></p>


<p><blockquote></blockquote></p>
</details>
