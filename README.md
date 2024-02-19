# BigBrother

## Gun Detection

We use YOLOv5 to detect guns in the video. Since a dataset that meets our needs was not found, few frames of videos of CCTV footage of gun point robbery were annotated. Since the size of dataset was not large enough, model performs only fairly accurately. This can be improved by training it on more number of annotated images.

## Action detection/trigger

1 indicates no activity of interest.
0 indicates an activity of interest is occuring in the video.

Currently, the action it detects is hostages raising their hands. This can be changed by training the model to detect other actions.
