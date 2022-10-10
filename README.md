
# Web App Face Mask Detection

This project was created to detect whether someone is wearing a mask or not wearing a mask. on the website we can choose to take a photo or upload a photo and it will generate a prediction to wear a mask or not

## Demo

Url Web: https://share.streamlit.io/app/agungyogasetiawan-face-mask-detection-app-jmdk/

Code Model Building CNN: [Click here for CNN modeling code on Google Colab](https://colab.research.google.com/drive/1YjVIiv5Am5tLOPOokay9dXXTLBRYc9da)

## How to Use

you can clone this repository or download zip
```bash
git clone https://github.com/AgungYogaSetiawan/face-mask-detection.git
```

when finished clone or download the repository. you open cmd and go to the folder where you saved the download, after entering the directory, install requirements.txt by typing this
```bash
pip install -r requirements.txt
```
after install requirements.txt, type this syntax to open streamlit web app
```bash
streamlit run app.py
```
## Conclusion about detection performance

there is some influence in the model can predict from an image, then the model can make mistakes in predicting

- light and distance
![light and distance](https://github.com/AgungYogaSetiawan/assets-image-and-videos-for-readme/blob/main/2022-10-02.png)

- without light and far away
![without light and far away](https://github.com/AgungYogaSetiawan/assets-image-and-videos-for-readme/blob/main/2022-10-02%20(1).png)

- light and close
![light and close](https://github.com/AgungYogaSetiawan/assets-image-and-videos-for-readme/blob/main/2022-10-02%20(2).png)

- without light and close
![without light and close](https://github.com/AgungYogaSetiawan/assets-image-and-videos-for-readme/blob/main/2022-10-02%20(4).png)



## Acknowledgements

- [Awesome Repository](https://github.com/soft-nougat/streamlitwebcam)
- [Streamlit WebRTC](https://github.com/whitphx/streamlit-webrtc)

