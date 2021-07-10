# Notes

## command to generate asm file -> *.s

```bash
cargo rustc --release -- --emit asm
cargo rustc -- --emit asm
```

## command to generate mir file -> *.mir

```bash
cargo rustc --release -- --emit mir
cargo rustc -- --emit mir
```

## command to generate llvm-ir file -> .ir

```bash
cargo rustc --release -- --emit 
cargo rustc -- --emit llvm-ir
```

## command to generate llvm-bc file -> *.?

```bash
cargo rustc --release -- --emit llvm-bc
cargo rustc -- --emit llvm-bc
```

