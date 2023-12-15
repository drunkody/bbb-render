# Awesome Video Scene Cut Detection and Analysis Tool

Awesome Video Scene Cut Detection and Analysis Tool is a powerful software designed to automatically detect and analyze scene changes in video files. With cutting-edge algorithms and a user-friendly interface, this tool is perfect for video editors, filmmakers, and content creators who want to streamline their editing process.

## Features

## Links
https://github.com/topics/scene-detection
Как мы научились делить видео на сцены с помощью 
https://habr.com/ru/companies/ivi/articles/497428/

https://github.com/topics/scene-detection


Существующие решения:
- ffprobe, 
- ffmpeg.org/ffprobe.htmlShotdetect, 
- johmathe.name/shotdetect.htmlPySceneDetect, pyscenedetect.readthedocs.io


http://github.com/albanie/shot-detection-benchmarks

https://cyberleninka.ru/article/n/adaptivnyy-detektor-momentov-mgnovennoy-smeny-stsen-v-videopotoke-i-metod-ego-obucheniya-na-osnove-priznakov-soderzhimogo-videopotoka

Извлечение ключевых кадров
Подходы в исследованиях

По типу решаемой задачи:
– В общем случае
    · G.Ciocca et al., An Innovative Algorithm For Key FrameExtraction In Video Summarization
– В частном случае
    · A.Ekin et al., Automatic Soccer Video Analysis andSummarization
    · S.X.Ju et al., Summarization of Videotaped Presentations:Automatic Analysis of Motion and Gesture
    
    По способу решения задачи:
– Видео 
– это множество кадров 
– кластеризация
    · P.Mundur et al., Keyframe-based video summarization using
    Delaunay clustering
– Видео – это последовательность кадров 
– сравнение соседних кадров
    · K.Khurana et al., Key Frame Extraction Methodology ForVideo Annotation
    · H.Zhang et al., Video Parsing and Browsing UsingCompressed Data

# Video Scene Cut Detection and Analysis Tool Comparison

## Features

| Feature | Shotcut | Adobe Premiere Pro | Final Cut Pro X | AVISynth+ | FFmpeg |
|---|---|---|---|---|---|
| Price | Free | $20.99/month | $299.99 | Free | Free |
| Scene cut detection | Yes | Yes | Yes | Yes | Yes |
| Content analysis | No | Yes | Yes | No | No |
| Custom scripting | No | Yes | Yes | Yes | Yes |

## Recommendations

* **Best free option:** Shotcut
* **Best professional option:** Adobe Premiere Pro or Final Cut Pro X
* **Best option for custom scripting:** AVISynth+ or FFmpeg

## Conclusion

The best video scene cut detection and analysis tool for you depends on your specific needs and budget. If you are looking for a free and open-source option, Shotcut is a good choice. If you are looking for a professional video editing software with a powerful scene cut detection tool, Adobe Premiere Pro or Final Cut Pro X are good options. If you are looking for a command-line tool that can be used for custom scripting, AVISynth+ or FFmpeg are good options.

Sure, here are some new scripts from GitHub for video scene cut detection:

PySceneDetect: A Python library for scene detection in videos. It uses a variety of techniques, including color histogram analysis, edge detection, and motion analysis.
SceneDetect: A Python library for scene detection in videos. It uses a variety of techniques, including shot boundary detection, color histogram analysis, and audio analysis.
changedetection.io: A Python library for scene detection in videos using deep learning. It is trained on a large dataset of videos and can accurately detect scene changes even in complex videos.
video-scene-detection: A Python library for scene detection in videos using deep learning. It is based on the same technology that is used in Facebook's video recommendation system.
pyscene: A Python library for scene detection in videos using a variety of techniques, including color histogram analysis, edge detection, and motion analysis.
These scripts are all open-source and can be used to create custom video scene cut detection tools. They can be used to detect scene cuts in a variety of video formats, including MP4, AVI, and MOV.

* [PySceneDetect](https://github.com/Breakthrough/PySceneDetect)
* [SceneDetect](https://github.com/johmathe/SceneDetect)
* [changedetection.io](https://github.com/deepmind/changedetection.io)
* [video-scene-detection](https://github.com/facebookresearch/video-scene-detection)
* [pyscene](https://github.com/alalek/pyscene)

These scripts are all open-source and can be used to create custom video scene cut detection tools. They can be used to detect scene cuts in a variety of video formats, including MP4, AVI, and MOV.


- **Automatic Scene Detection**: Utilize advanced machine learning models to detect scene changes with high accuracy.
- **Analysis Reports**: Get detailed reports on scene durations, timestamps, and the number of cuts.
- **Customizability**: Adjust the sensitivity of the scene detection to match various video styles and genres.
- **Batch Processing**: Process multiple videos at once to save time and effort.
- **Thumbnail Generation**: Automatically generate thumbnails for each detected scene for easy preview.
- **Export Options**: Export scene data in various formats like CSV, JSON, or XML for further processing.

## Quick Start

To get started with Awesome Video Scene Cut Detection and Analysis Tool, follow these simple steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/awesome-videoscene-tool.git

# Navigate to the project directory
cd awesome-videoscene-tool

# Install the dependencies
pip install -r requirements.txt

# Run the tool
python scene_cut_detector.py --input your-video-file.mp4