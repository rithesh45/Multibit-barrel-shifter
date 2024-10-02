# Multibit-barrel-shifter
Multi-bit barrel Shifter is a combinational circuit which is used to shift bits. it is like shift registers but as combinational and faster becuz barrel shifter can shift many bits in 1 clock cycle whereas shift registers take multiple clock cycles to shift.
left shift only w << shift_amount is enough

for right shift w >> shift_amt is enough

for right rotation w>> shift_amt | w << (4-shift_amt)
