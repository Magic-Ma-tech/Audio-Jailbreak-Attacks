# Audio-Jailbreak-Attacks
This is the official implementation of Audio Jailbreak Attacks: Exposing Vulnerabilities in SpeechGPT within a White-Box Framework.

Please install the dependencies using the following method.

```
pip install -r requirements.txt
```

The jailbreak samples are `output.wav` and `output_noise.wav`.

You can use the `Attack_GPT-audio-GOODVOICE` script to generate the adversarial token and use `reverse_noise` to convert the token back to audio.

The SpeechGPT code is available at https://github.com/0nutation/SpeechGPT.


