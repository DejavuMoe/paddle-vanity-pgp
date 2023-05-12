## Paddle_Vanity_PGP

Calculating vanity PGP with AI Studio.

**Quick Start**

- register an account of AI Studio
- read **[What's This?](https://www.dejavu.moe/posts/vanity-pgp/#gpu-算号)** | **[How to use?](https://telegra.ph/Baidu-Flying-Pulp-AI-Learning-Center-PGP-Number-Counting-Tutorial-10-18)**
- create an AI Studio Project

- then edit the `run.sh`

  - `algorithm` ed25519/cv25519/rsa4096...
  - `-j` For nVidia Tesla V100 `4096` is a nice choice
  - `-t` Recommendation not to exceed 60,000,000

- change `start command` bash run.sh
- submit script task