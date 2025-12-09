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


