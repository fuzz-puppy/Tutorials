# FFGO Tutorial

Use this quick reference to capture the key steps from [the companion YouTube tutorial](FILL IN).

## Creating the Image Board

Create an image board in the correct format using [Image Board Creator](https://www.fuzzpuppy.com/image-board-creator).

## Creating the Text Prompt

### Sample Prompts

Download example prompts from [here](https://github.com/zli12321/FFGO-Video-Customization/blob/a5dbf153d2a66d71c1980534c01c64ebf6a33d0d/Data/combined_first_frames/0-data.csv) 2.

### Prompt Creator Prompt

You are a prompting expert using the FFGO LoRa - https://firstframego.github.io/

1. 0-data.csv attached are sample prompts showing the correct format. Review them carefully.
2. [YOUR-FILENAME].png is the reference combined image we are going to use.
3. we want [DESCRIBE YOUR VIDEO BRIEFLY].
4. please provide the best possible prompt based on the examples. Make sure:

- The prompt starts with these words exactly: "ad23r2 the camera view suddenly changes."
- Never mention a “reference image”
- Describes what is happening as if it already exists
- Provide natural cinematic narration

## Negative Prompt

Example negative prompt can be found [here](https://github.com/zli12321/FFGO-Video-Customization/blob/a5dbf153d2a66d71c1980534c01c64ebf6a33d0d/VideoX-Fun/examples/wan2.2/predict_i2v.py#L137).

## Links to FFGO LoRas

- High Noise: https://huggingface.co/Kijai/WanVideo_comfy/resolve/main/LoRAs/Wan22_FFGO/Wan22_FFGO-LoRA-HIGH_bf16.safetensors
- Low Noise: https://huggingface.co/Kijai/WanVideo_comfy/resolve/main/LoRAs/Wan22_FFGO/Wan22_FFGO-LoRA-LOW_bf16.safetensors

## Settings

See [Example](./example-settings.json).

- Upload your image board.
- Change the prompt to your prompt.
