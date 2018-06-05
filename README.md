# sensitive-image-recognition
    catalog:
      1.bottleneck --->Fc layer output
      2.image_multiclass --->Data set(five classes--->blood explosion fight gun porn)
      3.imagener --->mobilenet_v1(width/resolution) or Inception v3
      4.retrain_logs --->train/validation (events--->for tensorflow visualization(tensorboard)
      5.saved_models
    usage:
      1.cmd.txt or command.txt
      2.tensorboard --log_dir=retrain_logs
      3.python 2.7
      4.cuda9.0 cudnn7.0.7 gpu
      5.tensorflow
      6.ubuntu16.04
