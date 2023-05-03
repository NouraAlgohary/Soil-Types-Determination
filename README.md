# Soil-Types
**A classification model to determine soil type by image.**
![Soil Types](https://user-images.githubusercontent.com/103903785/235557829-7580e7fd-95c1-4cc9-a203-b2b65c9991ac.png)

## Requirments

## Data
### Data Source
### Data
- **Input:** Image
- **Output:** Class 
    - Black Soil
    - Cinder Soil
    - Laterite Soil
    - Peat Soil
    - Yellow Soil

## Resource/Situational Constraints
- Lack of Data

## Process followed
- Data Augmentation
- Merge data from different srouces

## Code
1. Get the Data
2. Data Exploration
3. Data Preprocessing:
        - Shuffle
        - Resize
        - Rescale
        - RandomFlip
        - RandomRotation
4. Model Training (MobileNet)
5. Results (Accuracy = 99%)
5. Testing
