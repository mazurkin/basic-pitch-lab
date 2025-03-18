# Spleeter

bootstrap for https://github.com/spotify/basic-pitch

## installation

```shell
make env-init
make env-create
```

## run

```shell
# example
$ wget https://cdn.pixabay.com/download/audio/2022/02/10/audio_3dd26581cf.mp3?filename=flute-recorder-18816.mp3

# convert
$ bin/basic-pitch --model-serialization tflite --save-midi --sonify-midi output flute-recorder-18816.mp3
```
