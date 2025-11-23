# Computer Organization & Architecture Key Terms

## Foundational Terms
- **Computer system**: A complete setup that processes inputs into outputs.
- **Hardware**: Physical computer components.
- **Software**: Programs/instructions that direct hardware.
- **Computer Architecture**: Logical design (instruction set, data formats).
- **Computer Organization**: Physical implementation (how components work together).
- **System bus**: Communication path for CPU, memory, I/O.
- **Performance**: Speed of task execution.
- **Instruction**: Binary command for CPU.
- **Clock cycle**: One tick of CPU clock.
- **Machine cycle**: Time to fetch and execute an instruction step.
- **Stored program concept**: Data + instructions stored in same memory.

## CPU & Execution
- **CPU**: Core processor that runs instructions.
- **ALU**: Performs arithmetic/logic operations.
- **Control Unit**: Directs operations.
- **Registers**: Small fast storage units.
- **PC**: Holds address of next instruction.
- **IR**: Holds current instruction.
- **AC**: Holds intermediate results.
- **MAR**: Holds memory address.
- **MBR**: Holds data for transfer.

## Memory Architecture
- **Memory hierarchy**: Registers → cache → RAM → storage.
- **Cache**: Fast memory for frequently used data.
- **Cache hit/miss**: Data found/not found in cache.
- **Locality of reference**: Reuse of same or nearby data.
- **Main memory**: RAM storing active programs/data.
- **Addressing**: Identifying memory locations.
- **Word size**: Bits processed at once.
- **Byte addressing**: Each address maps to one byte.
- **Memory cycle time**: Time for one read/write.

## Buses & Data Transfer
- **Data bus**: Transfers data.
- **Address bus**: Transfers memory addresses.
- **Control bus**: Transfers commands.
- **Bus width**: Number of bits transferred at once.
- **I/O-mapped I/O**: Separate address space for I/O.
- **Memory-mapped I/O**: Shared address space with memory.

## ISA
- **ISA**: Instruction set a CPU understands.
- **Opcode**: Operation part of instruction.
- **Operand**: Data/address used by instruction.
- **Instruction format**: Instruction layout.
- **RISC**: Simple, fast instructions.
- **CISC**: Complex instructions.
- **Micro-operations**: Low-level execution steps.

## Addressing Modes
- **Immediate**: Operand inside instruction.
- **Direct**: Instruction contains operand address.
- **Indirect**: Address contains another address.
- **Register**: Operand stored in register.
- **Register indirect**: Register contains operand address.
- **Indexed**: Base + index register.
- **Base addressing**: Base register + offset.

## MARIE Architecture
- **AC, PC, IR, MAR, MBR**: CPU registers.
- **InReg/OutReg**: Input/output registers.
- **Instructions**: LOAD, STORE, ADD, JUMP, SKIPCOND, HALT.
- **Microinstruction**: One control step.
- **Control signals**: Activate CPU components.

## Interrupts
- **Interrupt**: Signal to pause current execution.
- **Interrupt cycle**: Save state + handle interrupt.
- **ISR**: Code handling interrupt.
- **Maskable**: Can be disabled.
- **Non-maskable**: Cannot be ignored.
- **Polling**: CPU checks devices repeatedly.
- **Vectored**: Interrupt contains ISR address.
- **Priority interrupt**: Higher priority interrupts handled first.

## Control Unit
- **Hardwired**: Fast, circuit-based control.
- **Microprogrammed**: Flexible, memory-based control.
- **Control signals**: Coordinate device operations.
- **Sequencer**: Orders microinstructions.
- **Control memory**: Stores microprograms.
