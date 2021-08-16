# SuperResolution-Denoising


## Qualitative comparison(Video SR)

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/61686244/129529083-b3ac6038-87ef-4835-998b-678837b732d3.gif)


  
## Qualitative comparison(Denoising + Super Resolution)
### Use a modified [RDSRN](https://github.com/HEEJOWOO/RDSRN)(It will be updated soon.)
* Results of training and testing using the [Visdrone](http://aiskyeye.com/) data set

|Input(350x197)|Ground Truth(1400x788)|Bicubic Upsample(1400x788)|denoising+Super Resolution(1400x788)|
|-----|------------|----------------|----------------|
|![2_input_x4](https://user-images.githubusercontent.com/61686244/129305783-d8a8bf1c-ca43-45f7-8671-ae05aebe0643.png)|![100255](https://user-images.githubusercontent.com/61686244/129203781-a692ffad-b309-4d5f-a597-ebb1b1df626e.png)|![2_bicubic_x4](https://user-images.githubusercontent.com/61686244/129305809-c914f1df-1dd4-4e35-a652-74598fca0380.png)|![2_SR_x4](https://user-images.githubusercontent.com/61686244/129472187-3ce5608a-6d89-4aaa-a5e0-7610509e37a7.png)|
|![image](https://user-images.githubusercontent.com/61686244/129472301-b132bb9c-5bb8-4a63-9f77-aa755d75c00a.png)|![100255_crop](https://user-images.githubusercontent.com/61686244/129472456-2864a78f-a2d6-40cf-99c1-f16ed2cbe24e.png)|![2_bicubic_x4_crop](https://user-images.githubusercontent.com/61686244/129472466-f6522d15-ea89-49f1-bafe-049b5eedf31c.png)|![2_SR_x4_crop](https://user-images.githubusercontent.com/61686244/129472469-b9598d36-c5f5-40fb-86ef-83d712655bd6.png)|


|Input(350x197)|Ground Truth(1400x788)|Bicubic Upsample(1400x788)|denoising+Super Resolution(1400x788)|
|-----|------------|----------------|----------------|
|![1_input_x4](https://user-images.githubusercontent.com/61686244/129306179-0d6a0949-2a9b-4ebe-bbeb-31c4c6e8ac76.png)|![100981](https://user-images.githubusercontent.com/61686244/129206679-cd2e70c3-86a3-4e34-831a-bd953de30ddc.png)|![1_bicubic_x4](https://user-images.githubusercontent.com/61686244/129306230-5f409efc-bfe9-4fbd-a1d7-d291434a41dc.png)|![1_SR_x4](https://user-images.githubusercontent.com/61686244/129472206-69680368-444b-459f-b3ad-df74f3ae8a4e.png)|
|![1_crop](https://user-images.githubusercontent.com/61686244/129472693-9e672707-3a55-4b21-938d-3815c9aa07d4.png)|![100981_crop](https://user-images.githubusercontent.com/61686244/129472694-aa7acdc0-b37d-4e46-808f-473e7ee8ad6e.png)|![1_bicubic_x4_crop](https://user-images.githubusercontent.com/61686244/129472712-9ab4dd18-c624-4b67-bf7d-ff4d3bb3e48e.png)|![1_SR_x4_crop](https://user-images.githubusercontent.com/61686244/129472721-628e0fd4-5ca1-4a38-bbac-bf1b9ce06e34.png)|
