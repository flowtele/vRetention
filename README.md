# YouTube/Bilibili Audience Retention Dataset

## Python libraries used in analysis
```
$ pip install -r requirements.txt
```

## Format

|__Parameter__|__Description__|
|-------------|---------------|
|__id__|_string_. The video ID.|
|__publishedAt__|_datetime_. The published date of the video.|
|__title__|_string_. Title of the video.|
|__categoryId__|_string_. The category of the video.|
|__duration__|_long_. The length of the video.|
|__viewCount__|_long_. The number of times the video has been viewed.|
|__countryCode__|_string_. The country of the video.|
|__date__|_datetime_. The query date of the video.|
|__retentionCurve__|_string_. SVG Path of audience retention curve.|

## Directory
* `analysis`: the analysis used in this paper
* `dataset`
  * `bilibili.csv`: audience retention curves of Bilibili videos
  * `youtube_video_age.csv`: records of how long a video exists in the popular list
  * `youtube.csv`: audience retention curves of YouTube videos
