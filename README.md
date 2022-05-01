# Train a WaveGAN

Here is how you would begin (or resume) training a WaveGAN on random clips from a directory containing longer audio, i.e., more than a few seconds per file:

```
export CUDA_VISIBLE_DEVICES="0"
python train_wavegan.py train ./train \
	--data_dir ./data/dir_with_longer_audio_files
```

