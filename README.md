
# People Counter - People Counting using YOLOv8 Object Detection




## 


![ss](https://github.com/ishita126jain/People-Counter/assets/91709949/81d86a90-5fd0-404b-9e5a-6764a7288b8f)


## Introduction

People Counter is a Python-based project that utilizes YOLOv8, an efficient and powerful object detection model, to count people moving in different direction through a designated area in a video. The project aims to accurately detect and count people while ignoring other objects present in the scene. 
## Prerequisites

- Python 3.6 or higher

- [Virtualenv](https://virtualenv.pypa.io/en/latest/) (optional but recommended)

## Installation

1. Create a virtual environment and activate it:

```bash
virtualenv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```
2. Install required packages:
```bash
pip install -r requirements.txt
```
    
## Usage

1. Prepare your video:

- Place your video file in the project directory.

2. Create a mask:

- Create a mask image named mask.png that defines the area where you want to count vehicles. The rest of the video will be masked out.

3. Run the Car Counter:
```bash
python people_counter.py 
``` 

4. View the results:

- The processed video with people counting will seen.

- The people count and class distribution will be displayed in the console.


## Configuration
- You can customize the confidence threshold for vehicle detection by modifying the conf parameter in people_counter.py. The default value is set to 0.3.
## Acknowledgements

 - [Ultralytics](https://github.com/ultralytics/ultralytics)
 - [CVzone library by CVzone](https://github.com/cvzone/cvzone)
 


## Contribution

Contributions are always welcome!

If you find any issues or have suggestions for improvements, feel free to create a pull request.


## Contact
For any questions or inquiries, please contact us at [ishita126jain@gmail.com](ishita126jain@gmail.com).
