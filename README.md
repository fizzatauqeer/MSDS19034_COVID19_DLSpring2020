# MSDS19034_COVID19_DLSpring2020

Dataset Link: [a link](https://drive.google.com/drive/u/0/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR)

### Part 1

- For Task 1:-

  -> Confusion Matrices:-

    - VGG16: 
               
       | 475  | 140  |
       | ---- | ---- |
       | 14   | 871  |

    - RESNET18: 
    
       | 510  | 105  |
       | ---- | ---- |
       | 104  | 781  |


  -> Accuracies:-

    - VGG16: 0.95

    - RESNET18: 0.92
   
   
- For Task 2:-

  -> Confusion Matrices:-

    - VGG16:
               
       | 535  | 80   |
       | ---- | ---- |
       | 50   | 835  |


    - RESNET18:

       | 539  | 76   |
       | ---- | ---- |
       | 70   | 815  |


  -> Accuracies:-

    - VGG16: 0.94

    - RESNET18: 0.96
    
### Part 2

- Without Focal Loss:-

  -> Confusion Matrices:-

    - VGG16: 
               
       | 19  | 6   |
       | --- | --- |
       | 1   | 36  |
       
       | 36  | 1   |
       | --- | --- |
       | 6   | 19  |

    - RESNET18: 
    
       | 50  | 17  |
       | --- | --- |
       | 14  | 4   |
       
       | 4  | 14 |
       | -- | -- |
       | 11 | 31 |
       
  -> Accuracies:-

    - VGG16: 94%

    - RESNET18: 91%
    

  -> F1 Score:-

    - VGG16: 0.86

    - RESNET18: 0.81
    
    
 - With Focal Loss:-
 
   -> Confusion Matrices:-

    - VGG16: 
               
       | 19  | 6   |
       | --- | --- |
       | 1   | 36  |
       
       | 36  | 1   |
       | --- | --- |
       | 6   | 19  |

    - RESNET18: 
    
       | 3  | 1  |
       | -- | -- |
       | 0  | 4  |
       
       | 4  | 0  |
       | -- | -- |
       | 1  | 3  |
       
  -> Accuracies:-

    - VGG16: 89%

    - RESNET18: 87%
    

  -> F1 Score:-

    - VGG16: 0.95

    - RESNET18: 1.0
