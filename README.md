# Computer Organization Labs — COE328

**Digital logic · VHDL source backups · Quartus design artifacts**

Coursework exploring arithmetic logic units, finite-state machines, decoders, latches and seven-segment display logic. This repository preserves the available Lab 6 report, schematic designs, symbols and waveform files.

[Read the lab report](COE328%20Lab%206%20Report%20GIT.pdf) · [Browse the design files](Lab6_ProjectFiles/)

## Explore the work

- [ALU problem 1](Lab6_ProjectFiles/ALU_Problem1/) and [problem 2](Lab6_ProjectFiles/ALU_Problem2/): source backups, schematic blocks, symbols and waveforms.
- [ALU problem 3](Lab6_ProjectFiles/ALU_Problem3/): schematic, symbol and waveform artifacts.
- [Components](Lab6_ProjectFiles/Components/): decoder, FSM, latch and seven-segment display designs.

Start with the report for the assignment context and recorded results, then compare the corresponding schematic and waveform files.

## File formats

- `.bdf`: Quartus block-diagram/schematic files.
- `.bsf`: block symbols.
- `.vwf`: waveform files.
- `.vhd.bak`: preserved VHDL backup files.
- `output_files/`: historical generated reports and programming artifacts.

The VHDL backups are preserved as supplied. This is an archive of coursework artifacts, not a verified clean-build package.

## Opening and reproducing

The [archived component build report](Lab6_ProjectFiles/Components/Latch/output_files/lab6.flow.rpt) identifies **Quartus II 13.0.1 SP1** and **Cyclone II EP2C35F672C6**, with top-level entity **ssegcode**. This is evidence for a display-component build, not a verified build or board deployment of the complete processor. Use a compatible Intel/Altera Quartus environment and recover the intended project settings before rebuilding.

If reconstructing a project, work in a separate copy: inspect the VHDL backups, restore the required source filenames, configure the device and top-level design, and verify dependencies before compiling. No fresh compilation, simulation or hardware validation is claimed.

## Engineering focus

The artifacts illustrate how combinational components and sequential state logic are assembled into larger digital designs. Review the report alongside the waveform files to understand the intended behavior; historical output files alone do not establish that a reconstructed project is correct.

## Next improvements

Recover the full-system project settings, identify canonical source files, and add a reproducible simulation procedure with explicit expected outputs. Preserve the original coursework artifacts while doing so.
