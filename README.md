# ImageClef-2020-DrawnUI
Detecting UI elements from hand drawn UI sketches.
Team Name : CudaMemError1

Article: http://ceur-ws.org/Vol-2696/paper_61.pdf

```
@article{narayanandeep,
  title={Deep Learning for UI Element Detection: DrawnUI 2020},
  author={Narayanan, Naveen and Balaji, Nitin Nikamanth Appiah and Jaganathan, Kavya}
}
```

- Challenge Details: https://www.imageclef.org/2020/drawnui
- Conference link: https://clef2020.clef-initiative.eu/
- Placed 2nd in this challenge: https://www.aicrowd.com/challenges/imageclef-2020-drawnui/leaderboards
 

## Instructions to run yolo:
- Run init in repos directory to clone the repo.
- Setup the config and data folders as instructed in the yolov4 repository
https://github.com/AlexeyAB/darknet#how-to-train-to-detect-your-custom-objects

- Get the data from clef challenge website:
https://www.aicrowd.com/clef_tasks/28/task_dataset_files?challenge_id=219

- Follow section 3 and 4 in notebooks to run and get results and converted submission files for the challenge.

## Scores
| Model  | Overall Precision |
| ------------- | ------------- |
| yolov4  | 0.937  |
| resnest  | 0.949  |
| fusion  | 0.950  |
