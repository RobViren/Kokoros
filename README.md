# Kokoro Rust

[Kokoro](https://huggingface.co/hexgrad/Kokoro-82M) is a trending top 2 TTS model on huggingface. 
This repo provides **insanely fast Kokoro infer in Rust**, you can now have your built TTS engine powered by Kokoro and infer fast by only a command of `koko`.

`kokoros` is a `rust` crate that provides easy to use TTS ability.
One can directly call `koko` in terminal to synthesize audio.

`kokoros` uses a relative small model 87M params, while results in extremly good quality voices results.

Languge support:

- [x] English;
- [x] Chinese (partly);
- [x] Japanese (partly);
- [x] German (partly);


## Updates

- ***`2025.01.12`***: Released `Kokoros`;


## Build

Run:

```shell
cargo build --release

# test
cargo run
```


## Roadmap

Due to Kokoro actually not finalizing it's ability, this repo will keep tracking the status of Kokoro, and helpfully we can have language support incuding: English, Mandarian, Japanese, German, French etc.


## Copyright

Copyright reserved by Lucas Jin under Apache License.