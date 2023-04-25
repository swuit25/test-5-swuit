# test-5-swuit

{
  "train": {
    "log_interval": 200,
    "eval_interval": 800,
    "seed": 1234,
    "epochs": 10000,
    "learning_rate": 0.0001,
    "betas": [
      0.8,
      0.99
    ],
    "eps": 1e-09,
    "batch_size": 6,
    "fp16_run": false,
    "lr_decay": 0.999875,
    "segment_size": 10240,
    "init_lr_ratio": 1,
    "warmup_epochs": 0,
    "c_mel": 45,
    "c_kl": 1.0,
    "use_sr": true,
    "max_speclen": 512,
    "port": "8001",
    "keep_ckpts": 3,
    "all_in_mem": false
  },
  "data": {
    "training_files": "filelists/train.txt",
    "validation_files": "filelists/val.txt",
    "max_wav_value": 32768.0,
    "sampling_rate": 44100,
    "filter_length": 2048,
    "hop_length": 512,
    "win_length": 2048,
    "n_mel_channels": 80,
    "mel_fmin": 0.0,
