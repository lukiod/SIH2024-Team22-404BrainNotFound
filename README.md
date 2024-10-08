
# Deepfake detection for Sih

## Give a Star⭐ to our Project

</a>

## Latest Update

#### We have dockerised the [Django Application](https://github.com/lukiod/SIH2024-Team22-404BrainNotFound/tree/main/Django%20Application) now you can spin up a container within seconds without worring about dependencies

## 1. Introduction

This projects aims in detection of video deepfakes using deep learning techniques like ResNext and LSTM. We have achived deepfake detection by using transfer learning where the pretrained ResNext CNN is used to obtain a feature vector, further the LSTM layer is trained using the features. For more details follow the Documentation Under ReadMe.md

## 2. Directory Structure

For ease of understanding the project is structured in below format

```
SIH-2024
    |
    |--- Django Application
    |--- Model Creation
    |--- Documentaion
```

1. Django Application
   - This directory consists of the django made application of our work. Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.
2. Model Creation
   - This directory consists of the step by step process of creating and training a deepfake detection model using our approach.
3. Documentation
   - This directory consists of all the documentation done during the project

## 3. System Architecture
![System Architecture](https://github.com/user-attachments/assets/959f6897-a3dc-4b9c-8b60-09138653429f)



## 4. Run Project Locally
Step 1 : Clone this repo 

Step 2 : Go to Django Application directory

Step 3 : Look out for ReadMe.md in Django Application Dir 

Step 4 : Follow the instruction mentioned in the ReadMe


GoodLuck Figuring This Out 

### You can watch the demo vedio

https://drive.google.com/file/d/18YolvlOZjsoPgCFiWkVzV3HjfcU3ecLh/view?usp=sharing

## 5. Our Results

| Model Name                            | No of videos | No of Frames | Accuracy |
| ------------------------------------- | ------------ | ------------ | -------- |
| model_84_acc_10_frames_final_data.pt  | 6000         | 10           | 84.21461 |
| model_87_acc_20_frames_final_data.pt  | 6000         | 20           | 87.79160 |
| model_89_acc_40_frames_final_data.pt  | 6000         | 40           | 89.34681 |
| model_90_acc_60_frames_final_data.pt  | 6000         | 60           | 90.59097 |
| model_91_acc_80_frames_final_data.pt  | 6000         | 80           | 91.49818 |
| model_93_acc_100_frames_final_data.pt | 6000         | 100          | 93.58794 |

## 6. Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- prettier-ignore-start -->

<!-- markdownlint-disable -->

<table>
  <tbody>
    <tr>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->

<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

<!-- prettier-ignore-start -->

<!-- markdownlint-disable -->

<!-- markdownlint-restore -->

<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

#### 6.1 Offline Contributors

1. Mohak Gupta
2. Aryyan Ahlawat
3. Nancy
4. Nishant Luheria
5. Ananya
6. Aastha


### Below are the some changes that can be applied to the project. New Ideas will be appreciated.

- [ ] Deploying the applications in free cloud
- [ ] Creating open source API for detection
- [ ] Batch processing of entire video instead of processing first 'x' frames.
- [X] Optimizing the code for faster execution.

#### Completed

- [X] Dockerizing the app
- [X] Enabling working of project on Non Cuda Computers. i.e on normal or AMD GPUs

