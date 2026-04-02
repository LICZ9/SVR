# SVR Dataset

This repository contains the **SVR** dataset for Cross-Modal Image Retrieval Tasks.

## Download

- **Baidu Netdisk**: [SVR Dataset](https://pan.baidu.com/s/1h_p0FkLdifvhH9_AJdb-5A?pwd=47bq)
- **Extraction Code**: `47bq`

## Dataset Structure

```
SVR/
├── Images/
│   ├── auv/
│   ├── circle_cage/
│   ├── cube/
│   ├── pot/
│   ├── square_cage/
│   ├── steel_frame/
│   ├── steel_plate/
│   └── tire/
├── Splits/
│   ├── 20_Splits/
│   ├── 50_Splits/
│   └── Full_Splits/
```

## Categories

| ID | Category      |
|----|---------------|
| 0  | auv           |
| 1  | circle_cage   |
| 2  | cube          |
| 3  | pot           |
| 4  | square_cage   |
| 5  | steel_frame   |
| 6  | steel_plate   |
| 7  | tire          |

## Notes
In our cross-modal image retrieval task, the default setting takes sonar images as queries and visible images as the gallery. The dataset split only provides the division of training, validation, and test sets. In the dataset, sonar images are named starting with "son", while visible (optical) images are named starting with "opt". You can flexibly switch between query and gallery according to your own needs.
