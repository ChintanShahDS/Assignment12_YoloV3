# Assignment12_YoloV3

### Training log
Namespace(epochs=100, batch_size=10, accumulate=4, cfg='cfg/yolov3-custom.cfg', data='data/numberplate/custom.data', multi_scale=False, img_size=[512], rect=False, resume=False, nosave=False, notest=False, evolve=False, bucket='', cache_images=True, weights='weights/yolov3-spp-ultralytics.pt', name='', device='', adam=False, single_cls=False)
Using CUDA device0 _CudaDeviceProperties(name='Tesla T4', total_memory=15102MB)

Image sizes 512 - 512 train, 512 test
Using 2 dataloader workers
Starting training for 100 epochs...

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      0/99     7.74G      8.19      68.4         0      76.6        21       512: 100% 12/12 [00:13<00:00,  1.17s/it]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:02<00:00,  1.05s/it]
                 all        15        35         0         0   0.00033         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      1/99     7.74G      7.21      2.81         0        10        38       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  2.84it/s]
                 all        15        35         0         0  0.000865         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      2/99     9.55G      6.66      1.18         0      7.84        42       512: 100% 12/12 [00:10<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.44it/s]
                 all        15        35         0         0   0.00076         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      3/99     9.55G      5.86      1.23         0       7.1        25       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.23it/s]
                 all        15        35         0         0         0         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      4/99     9.55G      5.75      1.43         0      7.18        25       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.64it/s]
                 all        15        35         0         0         0         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      5/99     9.55G      5.49      1.38         0      6.88        17       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.86it/s]
                 all        15        35         0         0         0         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      6/99     9.55G      5.31      1.33         0      6.63        28       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.02it/s]
                 all        15        35         0         0         0         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      7/99     9.55G      5.27      1.34         0      6.61        24       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.50it/s]
                 all        15        35         0         0         0         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      8/99     9.55G      4.94      1.23         0      6.17        22       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.48it/s]
                 all        15        35         0         0    0.0976         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
      9/99     9.55G      4.94       1.1         0      6.05        36       512: 100% 12/12 [00:10<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.34it/s]
                 all        15        35     0.161     0.143    0.0646     0.151

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     10/99     9.55G      4.77     0.972         0      5.74        25       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.29it/s]
                 all        15        35    0.0817     0.314    0.0476      0.13

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     11/99     9.55G      4.52     0.989         0      5.51        30       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.60it/s]
                 all        15        35     0.123     0.257     0.172     0.167

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     12/99     9.55G      4.42     0.816         0      5.24        25       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.40it/s]
                 all        15        35     0.153     0.314     0.166     0.206

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     13/99     9.55G       4.6     0.729         0      5.33        25       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.59it/s]
                 all        15        35     0.293     0.143     0.107     0.192

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     14/99     9.55G      4.79     0.658         0      5.45        33       512: 100% 12/12 [00:10<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.58it/s]
                 all        15        35     0.217     0.314      0.24     0.256

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     15/99     9.55G       4.5     0.614         0      5.11        24       512: 100% 12/12 [00:09<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.72it/s]
                 all        15        35     0.258     0.257      0.18     0.258

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     16/99     9.55G      4.31     0.668         0      4.97        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.68it/s]
                 all        15        35     0.392     0.371     0.307     0.382

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     17/99     9.55G      3.98     0.544         0      4.52        27       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.58it/s]
                 all        15        35     0.614     0.371     0.351     0.463

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     18/99     9.55G      4.05     0.541         0      4.59        27       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.28it/s]
                 all        15        35     0.645     0.143     0.395     0.234

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     19/99     9.55G      3.85     0.553         0       4.4        32       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.14it/s]
                 all        15        35     0.443     0.364      0.31       0.4

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     20/99     9.55G      3.99     0.531         0      4.52        29       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.35it/s]
                 all        15        35     0.507     0.171     0.288     0.256

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     21/99     9.55G      3.96     0.498         0      4.46        34       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.68it/s]
                 all        15        35     0.483     0.257     0.347     0.336

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     22/99     9.55G      3.96      0.48         0      4.44        20       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.61it/s]
                 all        15        35     0.253     0.343      0.21     0.291

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     23/99     9.55G       3.9     0.512         0      4.42        29       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.58it/s]
                 all        15        35     0.775     0.229     0.424     0.353

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     24/99     9.55G      3.72     0.494         0      4.21        27       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.52it/s]
                 all        15        35      0.68     0.183     0.488     0.288

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     25/99     9.55G      3.86     0.569         0      4.43        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.36it/s]
                 all        15        35         1     0.169     0.608      0.29

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     26/99     9.55G      3.34     0.617         0      3.95        33       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.23it/s]
                 all        15        35     0.749     0.255     0.588     0.381

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     27/99     9.55G      3.66     0.455         0      4.12        22       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.35it/s]
                 all        15        35     0.821     0.262     0.667     0.397

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     28/99     9.55G      3.56     0.491         0      4.05        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.40it/s]
                 all        15        35     0.732     0.314     0.477      0.44

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     29/99     9.55G      3.51     0.442         0      3.95        26       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.43it/s]
                 all        15        35     0.627     0.343     0.449     0.443

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     30/99     9.55G       3.4     0.392         0      3.79        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.39it/s]
                 all        15        35     0.715     0.371     0.498     0.489

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     31/99     9.55G      3.59     0.375         0      3.97        32       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.21it/s]
                 all        15        35     0.861     0.354     0.529     0.502

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     32/99     9.55G      3.18     0.446         0      3.62        27       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.62it/s]
                 all        15        35     0.926     0.358     0.633     0.517

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     33/99     9.55G      3.18     0.514         0      3.69        46       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.70it/s]
                 all        15        35     0.553     0.429     0.496     0.483

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     34/99     9.55G      2.84     0.647         0      3.49        28       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.79it/s]
                 all        15        35     0.751     0.314     0.581     0.443

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     35/99     9.55G      2.83     0.444         0      3.28        29       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.32it/s]
                 all        15        35     0.924     0.349     0.675     0.506

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     36/99     9.55G      3.19     0.361         0      3.55        27       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.26it/s]
                 all        15        35    0.0121     0.286    0.0168    0.0232

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     37/99     9.55G      3.31     0.384         0      3.69        26       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.22it/s]
                 all        15        35   0.00402       0.2   0.00712   0.00788

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     38/99     9.55G      3.17     0.473         0      3.64        28       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.18it/s]
                 all        15        35   0.00177     0.143   0.00317    0.0035

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     39/99     9.55G      3.12     0.444         0      3.56        27       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.08it/s]
                 all        15        35   0.00416     0.257   0.00335   0.00819

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     40/99     9.55G      2.89     0.472         0      3.36        25       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.35it/s]
                 all        15        35    0.0471       0.4     0.045    0.0843

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     41/99     9.55G      2.74     0.476         0      3.21        30       512:  67% 8/12 [00:06<00:03,  1.20it/s]
     
Model Bias Summary:    layer        regression        objectness    classification
                          89      -0.16+/-0.24     -11.03+/-1.95       0.02+/-0.01 
                         101      -0.16+/-0.26      -9.99+/-0.58       0.04+/-0.00 
                         113       0.09+/-0.23      -8.78+/-1.61      -0.00+/-0.01 
                         
     41/99     9.55G       2.7     0.458         0      3.16        34       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.31it/s]
                 all        15        35     0.215     0.438     0.175     0.288

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     42/99     9.55G      2.82      0.44         0      3.26        30       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.15it/s]
                 all        15        35     0.163     0.429     0.146     0.236

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     43/99     9.55G      2.87     0.414         0      3.28        26       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.37it/s]
                 all        15        35     0.198     0.371     0.189     0.258

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     44/99     9.55G      2.46     0.404         0      2.87        39       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.70it/s]
                 all        15        35     0.331     0.429     0.304     0.374

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     45/99     9.55G      2.89     0.364         0      3.25        42       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.58it/s]
                 all        15        35     0.796     0.457     0.596     0.581

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     46/99     9.55G      2.41     0.418         0      2.83        31       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.75it/s]
                 all        15        35     0.944      0.48     0.645     0.637

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     47/99     9.55G      2.35     0.428         0      2.77        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.63it/s]
                 all        15        35     0.958     0.486     0.665     0.645

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     48/99     9.55G       2.5     0.346         0      2.85        18       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.39it/s]
                 all        15        35     0.826     0.407     0.607     0.546

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     49/99     9.55G      2.47     0.342         0      2.81        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.53it/s]
                 all        15        35     0.909       0.4     0.673     0.556

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     50/99     9.55G      2.66     0.329         0      2.98        23       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.31it/s]
                 all        15        35     0.846     0.472     0.683     0.606

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     51/99     9.55G      2.58     0.313         0       2.9        33       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.15it/s]
                 all        15        35      0.95     0.539     0.701     0.688

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     52/99     9.55G      2.48     0.333         0      2.81        25       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.33it/s]
                 all        15        35         1     0.472     0.698     0.641

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     53/99     9.55G      2.43     0.301         0      2.73        29       512: 100% 12/12 [00:10<00:00,  1.14it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.35it/s]
                 all        15        35     0.945     0.492     0.682     0.647

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     54/99     9.55G      2.25      0.31         0      2.56        27       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.45it/s]
                 all        15        35     0.946     0.505     0.691     0.658

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     55/99     9.55G      1.88     0.273         0      2.16        26       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.37it/s]
                 all        15        35     0.943     0.473     0.699      0.63

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     56/99     9.55G       1.9     0.319         0      2.21        29       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.01it/s]
                 all        15        35     0.948     0.524     0.703     0.675

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     57/99     9.55G      2.12     0.321         0      2.44        21       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.31it/s]
                 all        15        35     0.903     0.535     0.694     0.672

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     58/99     9.55G      2.12     0.335         0      2.45        22       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.23it/s]
                 all        15        35     0.902     0.525     0.686     0.664

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     59/99     9.55G      2.11     0.373         0      2.48        33       512: 100% 12/12 [00:10<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.36it/s]
                 all        15        35     0.885     0.438      0.67     0.586

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     60/99     9.55G      1.85     0.319         0      2.17        30       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.10it/s]
                 all        15        35     0.883     0.431     0.671     0.579

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     61/99     9.55G      1.88     0.265         0      2.15        23       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.95it/s]
                 all        15        35     0.846      0.47     0.671     0.604

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     62/99     9.55G      1.74     0.269         0      2.01        28       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.39it/s]
                 all        15        35     0.855     0.508     0.676     0.637

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     63/99     9.55G      1.96     0.235         0       2.2        26       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.62it/s]
                 all        15        35     0.828     0.549     0.681      0.66

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     64/99     9.55G      2.04     0.216         0      2.25        22       512: 100% 12/12 [00:09<00:00,  1.21it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.43it/s]
                 all        15        35     0.869     0.566     0.695     0.686

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     65/99     9.55G      2.27     0.211         0      2.48        27       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.34it/s]
                 all        15        35     0.949     0.536       0.7     0.685

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     66/99     9.55G      1.88     0.264         0      2.15        27       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.31it/s]
                 all        15        35     0.863     0.542     0.689     0.666

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     67/99     9.55G      1.69      0.24         0      1.93        30       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.38it/s]
                 all        15        35     0.878     0.617     0.699     0.725

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     68/99     9.55G      1.83     0.208         0      2.04        26       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.41it/s]
                 all        15        35     0.854     0.629     0.697     0.724

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     69/99     9.55G      1.85     0.232         0      2.08        29       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.25it/s]
                 all        15        35     0.831     0.629     0.689     0.716

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     70/99     9.55G      1.58     0.236         0      1.81        26       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.28it/s]
                 all        15        35     0.803     0.583     0.686     0.676

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     71/99     9.55G      1.56     0.211         0      1.77        27       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.37it/s]
                 all        15        35     0.809     0.604     0.682     0.692

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     72/99     9.55G      1.59     0.221         0      1.81        25       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.68it/s]
                 all        15        35      0.81     0.611     0.679     0.697

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     73/99     9.55G      1.56     0.208         0      1.77        28       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.18it/s]
                 all        15        35     0.786     0.631     0.689       0.7

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     74/99     9.55G      1.47     0.197         0      1.66        34       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.58it/s]
                 all        15        35     0.812     0.615     0.693       0.7

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     75/99     9.55G       1.5      0.19         0      1.69        27       512: 100% 12/12 [00:10<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.34it/s]
                 all        15        35     0.813     0.623     0.694     0.705

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     76/99     9.55G      1.38     0.189         0      1.56        32       512: 100% 12/12 [00:10<00:00,  1.16it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.33it/s]
                 all        15        35     0.792     0.657     0.693     0.718

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     77/99     9.55G      1.48     0.183         0      1.66        33       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.81it/s]
                 all        15        35     0.785     0.657     0.699     0.715

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     78/99     9.55G      1.31     0.161         0      1.47        27       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.42it/s]
                 all        15        35      0.78     0.657       0.7     0.713

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     79/99     9.55G      1.35      0.15         0       1.5        27       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.41it/s]
                 all        15        35     0.757     0.657       0.7     0.703

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     80/99     9.55G      1.39     0.153         0      1.54        16       512: 100% 12/12 [00:09<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.37it/s]
                 all        15        35     0.729     0.657     0.697     0.691

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     81/99     9.55G      1.34     0.178         0      1.52        27       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.26it/s]
                 all        15        35     0.749     0.657     0.701       0.7

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     82/99     9.55G      1.28     0.161         0      1.45        28       512: 100% 12/12 [00:10<00:00,  1.13it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.17it/s]
                 all        15        35     0.751     0.657     0.702     0.701

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     83/99     9.55G      1.28      0.17         0      1.45        30       512: 100% 12/12 [00:10<00:00,  1.13it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.37it/s]
                 all        15        35     0.773      0.68     0.702     0.723

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     84/99     9.55G      4.23     0.245         0      4.48        35       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.38it/s]
                 all        15        35     0.504    0.0571     0.319     0.103

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     85/99     9.55G      2.77     0.697         0      3.47        33       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.39it/s]
                 all        15        35         0         0     0.124         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     86/99     9.55G      2.32     0.643         0      2.97        34       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.79it/s]
                 all        15        35         0         0     0.379         0

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     87/99     9.55G      2.33     0.545         0      2.87        30       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.69it/s]
                 all        15        35         1    0.0868     0.502      0.16

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     88/99     9.55G      2.48     0.514         0         3        25       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.53it/s]
                 all        15        35     0.896     0.246     0.524     0.386

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     89/99     9.55G      2.45     0.504         0      2.96        31       512: 100% 12/12 [00:10<00:00,  1.19it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.18it/s]
                 all        15        35     0.894      0.24     0.537     0.379

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     90/99     9.55G      2.25     0.483         0      2.74        29       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.52it/s]
                 all        15        35     0.713     0.286     0.488     0.408

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     91/99     9.55G      2.51     0.441         0      2.95        28       512: 100% 12/12 [00:10<00:00,  1.13it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.44it/s]
                 all        15        35     0.776     0.198     0.533     0.316

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     92/99     9.55G      2.24     0.463         0       2.7        32       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.27it/s]
                 all        15        35     0.668     0.173     0.523     0.274

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     93/99     9.55G      2.38     0.403         0      2.79        25       512: 100% 12/12 [00:10<00:00,  1.18it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.56it/s]
                 all        15        35     0.875       0.2     0.531     0.326

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     94/99     9.55G       2.6     0.438         0      3.04        30       512: 100% 12/12 [00:09<00:00,  1.20it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  3.83it/s]
                 all        15        35     0.792     0.218     0.502     0.342

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     95/99     9.55G      2.53     0.392         0      2.93        27       512: 100% 12/12 [00:09<00:00,  1.21it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.37it/s]
                 all        15        35     0.839     0.299     0.495     0.441

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     96/99     9.55G      2.62     0.478         0      3.09        37       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.15it/s]
                 all        15        35     0.912     0.298     0.512      0.45

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     97/99     9.55G      2.75     0.426         0      3.18        34       512: 100% 12/12 [00:10<00:00,  1.13it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.27it/s]
                 all        15        35         1       0.3     0.521     0.461

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     98/99     9.55G      2.57     0.442         0      3.02        45       512: 100% 12/12 [00:10<00:00,  1.15it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.33it/s]
                 all        15        35         1     0.345     0.628     0.513

     Epoch   gpu_mem      GIoU       obj       cls     total   targets  img_size
     99/99     9.55G      2.35     0.387         0      2.74        22       512: 100% 12/12 [00:10<00:00,  1.17it/s]
               Class    Images   Targets         P         R   mAP@0.5        F1: 100% 2/2 [00:00<00:00,  4.42it/s]
                 all        15        35         1     0.274     0.649      0.43
100 epochs completed in 0.414 hours.


### Training Batch outputs
![train_batch0](https://github.com/ChintanShahDS/Assignment12_YoloV3/assets/94432132/ec1c8f1f-c498-4144-a717-721a7bfad4f1)

### Testing Batch outputs
![test_batch0](https://github.com/ChintanShahDS/Assignment12_YoloV3/assets/94432132/0fa5529d-68f1-4ceb-a915-adf1970b1d3e)

### Training and Testing graphs
![results](https://github.com/ChintanShahDS/Assignment12_YoloV3/assets/94432132/aa16caa3-b9c5-41e8-953e-32d6da563047)

### LR output
![LR (1)](https://github.com/ChintanShahDS/Assignment12_YoloV3/assets/94432132/6ff44417-8e2a-4aed-9889-bd24acb0f01e)

