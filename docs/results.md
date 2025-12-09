# Results & Visualizations

Below is a summary of my model performance.

| Model      | LR     | Batch | Aug | Val Acc |
|-----------|--------|-------|------|----------|
| AlexNet   | 0.0001 | 16    | Yes  | 90%      |
| AlexNet   | 0.0001 | 16    | No   | 90%      |
| AlexNet   | 0.001  | 16    | Yes  | 50%      |
| ResNet18  | 0.0001 | 16    | Yes  | 90%      |
| ResNet18  | 0.0001 | 64    | No   | 80%      |

## Key Takeaways
- Low learning rate (0.0001) performed the best  
- Both AlexNet and ResNet18 reached **90% accuracy**  
- High learning rates caused poor generalization  
- Augmentation helped slightly with consistency  

<img width="2528" height="1328" alt="W B Chart 1" src="https://github.com/user-attachments/assets/60a3e348-2de2-4530-a0a1-038421fd2c86" />


<img width="2528" height="1328" alt="W B Chart 2" src="https://github.com/user-attachments/assets/058897e5-c3dd-4195-9945-eb575e82e591" />
