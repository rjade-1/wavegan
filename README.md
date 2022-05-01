# Train a WaveGAN

using below command, training a WaveGAN on random clips from a directory containing longer audio can be done

```
export CUDA_VISIBLE_DEVICES="0"
python train_wavegan.py train ./train \
	--data_dir ./data/tatum_audio_file
```

