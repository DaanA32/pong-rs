# Pong!

Made by following the [Amethyst Pong Tutorial](https://book.amethyst.rs/master/pong-tutorial.html).

## Known Issues
-   No Audio: Rodio panics on my system
    ```
    ALSA lib pcm_dmix.c:1089:(snd_pcm_dmix_open) unable to open slave
    thread '<unnamed>' panicked at 'The device doesn't support any format!?: DeviceNotAvailable', /home/daan/.cargo/registry/src/github.com-1ecc6299db9ec823/rodio-0.11.0/src/engine.rs:149:14
    ```