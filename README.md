# Bagpipe Tuner

Live pitch tuner for the Highland bagpipes with drone filtering.

![Svelte](https://img.shields.io/badge/Svelte-222222?style=for-the-badge&logo=svelte)
![TypeScript](https://img.shields.io/badge/TypeScript-222222?style=for-the-badge&logo=typescript)
![Docker](https://img.shields.io/badge/Docker-222222?style=for-the-badge&logo=docker)
![Fly.io](https://img.shields.io/badge/Fly.io-222222?style=for-the-badge&logo=flydotio&logoColor=8B5CF6)

<img src=".github/preview.png" width="640" alt="Bagpipe Tuner">

- YIN algorithm pitch detection through the device microphone
- High-pass drone filtering to isolate the chanter
- Median smoothing and octave-error correction for a steady reading
- Note matching on the bagpipe scale with a displayed sharp or flat reading
