

# PoseEstimation-CoreML

iOS + Machine Learning DEMO Projects are in [this repository(iOS Projects with ML Models)](https://github.com/motlabs/iOS-Proejcts-with-ML-Models)<br>This project is Pose Estimation on iOS with Core ML<br>

![180705-poseestimation-demo.gif](https://github.com/tucan9389/PoseEstimation-CoreML/blob/master/resource/180705-poseestimation-demo.gif?raw=true)

## Requirements

- Xcode 9.2+
- iOS 11.0+
- Swift 4.1

## Download model

Pose Estimation model for Core ML(`model_cpm.mlmodel`)<br>
☞ Download Core ML model [model_cpm.mlmodel](https://github.com/edvardHua/PoseEstimationForMobile/tree/master/release/cpm_model) or [hourglass.mlmodel](https://github.com/edvardHua/PoseEstimationForMobile/blob/master/release/hourglass_model/hourglass.mlmodel).

> input_name_shape_dict = {"image:0":[1,224,224,3]} image_input_names=["image:0"] <br>output_feature_names = ['Convolutional_Pose_Machine/stage_5_out:0']
>
> －in [https://github.com/edvardHua/PoseEstimationForMobile](https://github.com/edvardHua/PoseEstimationForMobile)

## Preparing build

### Import the model

![모델 불러오기.png](https://github.com/tucan9389/MobileNetApp-CoreML/blob/master/resource/%EB%AA%A8%EB%8D%B8%20%EB%B6%88%EB%9F%AC%EC%98%A4%EA%B8%B0.png?raw=true)

Once you import the model, compiler generate model helper class on build path automatically. When you use model, you can access through model helper class by creating a instance not through build path.

## Code

(Ready to publish)
