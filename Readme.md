# SVR Dataset

This repository contains the **SVR** dataset for Cross-Modal Image Retrieval Tasks.

## Download

- **Baidu Netdisk**: [SVR Dataset](https://pan.baidu.com/s/1h_p0FkLdifvhH9_AJdb-5A?pwd=47bq)
- **Extraction Code**: `47bq`

## Dataset Structure

```
SVR/
├── Images/
│   ├── block/
│   ├── circle_cage/
│   ├── pot/
│   ├── square_cage/
│   ├── steel_frame/
│   ├── steel_plate/
│   ├── tire/
│   └── underwater_robot/
├── Splits/
│   ├── 20_Splits/
│   ├── 50_Splits/
│   └── Full_Splits/
```

## Categories

| ID | Category         |
|----|------------------|
| 0  | block            |
| 1  | circle_cage      |
| 2  | pot              |
| 3  | square_cage      |
| 4  | steel_frame      |
| 5  | steel_plate      |
| 6  | tire             |
| 7  | underwater_robot |

## Notes
In our cross-modal image retrieval task, the default setting takes sonar images as queries and visible images as the gallery. The dataset split only provides the division of training, validation, and test sets. In the dataset, sonar images are named starting with "son", while visible (optical) images are named starting with "opt". You can flexibly switch between query and gallery according to your own needs.
