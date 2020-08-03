<pre>
# MIPS-SIMULATOR
it reads and executes assembly language programs

used - c++

implemented in three phases-


phase 1 -  A simple c++ program which reads an assembly file and execute instruction one-by-one<br />
           and at the end show resisters, there's values and data memory.
           
phase 2 -  Modified version of phase 1 where we use pipeline processing in five steps<br />
           Instruction fetch(IF),instruction decode(ID),instruction execute(EX),Memory access(M),Write back(WB)<br />
           and at the end show resisters, there's values and data memory.
           
phase 3 -  Modified version of phase 2 where we use cache(fully associative)<br />
           this time our simulator will run with two level of cache, L1 and L2<br />
           cache L1 and L2 both size and block size is dynamic which we will set through input file.<br />
           and at the end show IPC(instrction pre cycle), Miss rate, Number of stalls, and Memory of cache L1 and L2.
<pre>
