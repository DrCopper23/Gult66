# Gult66

## RISC-V based SoftCPU core implementation on a ZedBoard
  Quarantine Project currently under progress.
  
### Description
    TODO: Write Description after deciding top level architecture
    Scope- Design a RISC-V based SoftCPU core to be implemented on a ZedBoard with UART as IO
### Guide to navigate the repository
    TODO: Write this during compilation
    
### Tentative Timeline of the Project
    Things Decided
    ISA     -    RV32I (Details specified in the previous mail)
    FPGA -    ZedBoard ( Available in IoT Lab. Can avail from Vinay Chamola with prior notice.)
    IO       -    UART
    

    

    Obviously the following is subject to change. It is a rough timeline I've made for the project.
    Judging from how much time we have and how much time we have wasted, this'll be a successful project only if everyone is      into the project and is willing to dedicate the next month or so for this.

    Timeline
       May 10-12
       - Decide on Application to focus on. 
       - Read up on specifications of ZedBoard to gauge the capacity of cache memory on our chip.

       May 13
       - Finalize the assembler.
       - Backlogs
       May 14-16
       - Decide on the MicroArchitecture based on application 
               -- Decide on pipeline stages.
               -- Decide on various blocks based on chip type- out-of-order/in-order, superscalar, SIMD, VLIW, with/without branch predication unit.
               -- Make draw.io files of potential designs of top level architecture for documentation.
       May 17
       - After Relevant details have been finalized, allocating RTL coding amongst the 3 of us.
       - Divide work into Modules.
       - Establish a coding style. (Will probably use the one specified by PULPino or low-RISC) 
         (or something similar to this https://www.nandland.com/articles/coding-style-recommendations-vhdl-verilog.html)

       May 18-June 7 (Flexible)
       - RTL coding.
         This includes time for making draw.io illustrations of the blocks being coded.
       - Concurrently with RTL descriptions, individually figure out Vivado HLS or tools like Verilator (essentially synthesis tools)

       June 8-12
       - Code Review

       June 13-17
       - Compiling
       - GitHub Repository Design
