# DeepVisualOdometryKeras
![](MoMotorCity2429constructbar.gif)
![](s'.gif)

# Notes

Feeding data and training this model is computationally heavy. The model was trained using AWS's c5d.9xlarge ec2 instance (36 vCPUs, 77GB memory).

The models weights are quite large in .h5 form @ 508 MB, exceeding the maximum upload size of 100 MB. Message me if you want them in their current state.

The model requires more training. I would like to find some very simple drone movement datasets with accurate groundtruths.  I will be resegmenting and modifying the existing datasets to extend training for now. I am going to start modifying the "FPS" of the images as a general experiment. I will also test transfer learning approaches on some of these models. I would like to use Flownet 2, but I have yet to see it available for Keras, rather, solely on PyTorch, and I would like to develop this completely in Keras. I'll be keeping mny eyes out for other models and looking into a conversion/weights loading.
