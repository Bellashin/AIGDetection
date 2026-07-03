# AIGDetection

## Project Description

AIGDetection is a deep learning-based project that detects whether a video is AI-generated or real. The goal is to provide real-time inference that helps users identify synthetic videos and reduce misinformation caused by increasingly realistic generative AI.

## Why I decide to make?

매번 인스타그램이나 유튜브를 통해 비디오를 시청할 때, 해당 영상이 AI로 만든 영상인지, 아니면 실제 영상인지 헷갈리는 경우가 많은 걸 직접 경험하게 되었습니다. 현재는 이 높은 퀄리티의 AI 생성 비디오가 나쁜 목표로 생성되고 있지 않지만, 이것이 이제 해당 영상을 이용하는 노년 계층 또는 AI 생성에 대해 모르는 사람들에게 큰 혼란을 야기할 수 있다고 생각했습니다. 

## Main Features

- Detect whether a video is AI-generated or real
- Real-time inference for video streams
- Support for input video from screen directly (planned)

## Tech Stack

* Python
* PyTorch
* OpenCV
* NumPy
* Torchvision

## Project Structure
```
AIGDetection/
├── data/
├── models/
├── inference/
├── training/
├── utils/
├── checkpoints/
├── README.md
└── requirements.txt
```
## Future Plans

* Improve detection accuracy
* Support more AI video generation models
* Build a web demo using Streamlit
* Optimize for real-time inference
* Deploy as a browser extension
* Support longer and higher-resolution videos

## License

This project is under the MIT License.
