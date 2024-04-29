# zTSO

zTSO is intended to be an experimental reimplementation of The Sims Online written in Zig that directly accesses NioTSO's C-based libraries.

## Motivation

Although an existing and established reimplementation project already exists, it has excess legacy baggage due to it originally being based on .NET Framework 3.5 and XNA, among other things. This has limited its accessibility. Although NioTSO has been abandoned for quite some time now, the foundation remains solid. The client perfectly simulates a loading screen, plus it can render Sims and objects flawlessly.

The problem is C is, well, C. ¯\\\_(ツ)\_/¯ Accessing NioTSO's code in safer languages like Go or Rust has been historically been difficult. While Zig is still in its infancy, it has proven to be perfectly capable of doing this without jumping through hoops. Making it well worth giving it a try.

Will this succeed? *I have no idea*. I'm not much of a game developer, but that hasn't stopped me from dreaming.

## To do

- [ ] Rewrite header files

- [ ] Write Vitaboy renderer in Zig

## Requirements

- The Sims Online
- [Zig](https://ziglang.org/) 0.11 or newer

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/tonytins/ztso.git
   ```

2. **Navigate to the Repository**:

   ```bash
   cd zsandbox
   ```

3. **Run the Examples**: Execute the code examples using the Zig compiler. For instance:

   ```bash
   zig build run
   ```

4. **Experiment and Learn**: Modify the code, try out different constructs, and see how Zig behaves.

## License

I license this project under the GPL-3.0 license - see [LICENSE](LICENSE) for details.