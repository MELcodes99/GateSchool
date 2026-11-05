# Gate School

Learn chip design one NAND gate at a time, then tape out on X Layer.

Gate School is a concept for the X Layer TapeOut Idea Scouts campaign. TapeOut asks people to design circuits from NAND and LATCH transistors and pass Proof of Design sampling to mine $BEM. Most newcomers never get that far because the guides assume chip-design knowledge and mistakes burn real transistors.

Gate School is the onramp: a free sandbox that uses test vectors the same way PoD does, with lessons that build from a single inverter up to a full adder. The final lesson is a real PoD-style problem, and passing it leads into tape-out on X Layer.

## Play

Live at https://melcodes99.github.io/gate-school/

## What is in the prototype

- Guided first lesson that shows exactly where to tap
- Six lessons: NOT, AND, OR, NOR, XOR, half adder
- Final problem: full adder (8 test vectors, par 9 NAND)
- Stars for passing and for matching the gate par
- Simulated tape-out flow (no wallet, nothing sent onchain)

## Roadmap

- LATCH lessons for memory circuits
- Real wallet connection and tape-out on X Layer (chain 196)
- Onchain badges per lesson as a Proof of Design record

## Run locally

It is one HTML file with no build step. Open index.html in a browser.

Built by Mel (0xJedi) & Oma · github.com/MELcodes99
