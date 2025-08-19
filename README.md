# ESPHome `micro_wake_word` Model collection for Pepper

This repository serves to host `micro_wake_word` model files (`.tflite`) for ease of use with the `micro_wake_word` ESPHome component.

## Usage

These files can be used by referencing them by the filename without `.tflite`.

```yaml
micro_wake_word:
  ...
  models:
    - model: hay_pepper
```

## Model Training

See [https://github.com/kahrendt/microWakeWord](https://github.com/MasterPhooey/MicroWakeWord-Trainer-Docker) for details and instructions on training your own wake words.
