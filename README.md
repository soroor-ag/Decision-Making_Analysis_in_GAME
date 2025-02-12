# Decision-Making Analysis in Game Environments

This project explores the impact of cognitive biases on decision-making within a controlled game environment. By analyzing eye and eyebrow features extracted from 478 facial landmarks, we aimed to classify and predict individuals' risky decision-making behaviors.

## Project Overview

Participants engaged in a game consisting of five levels:
- **Levels 1-3:** No biases introduced; purely focused on gameplay.
- **Levels 4-5:** Participants were subjected to anchoring bias and overconfidence bias and Loss Aversion influe.

### Facial Landmark Analysis
We extracted eye and eyebrow features from 478 facial landmarks to study their changes during decision-making.
![image](https://github.com/user-attachments/assets/71ac46c2-5f92-491c-b452-29266f935b1d)
![image](https://github.com/user-attachments/assets/b1d0fc76-23fe-4035-bead-cbf2a6fd5b74)



## Objectives

1. **Classification and Prediction:** Determine if we can classify and predict individuals who make risky decisions based on facial features.
2. **Feature Analysis:** Identify common features that change during risky and safe decision-making.
3. **Bias Effects:** Examine how cognitive biases, such as Loss Aversion bias, affect decision-making.


## Key Findings

- **Eye Feature Changes:** Significant changes in eye features during decision-making.
- **Bias Impact:** Cognitive biases like Loss Aversion influence decision-making processes.
- target 0 for safe decisions and 1 for risky decisions and 2 for no decision
- you can see important features here:
- ![image](https://github.com/user-attachments/assets/3574cb8f-e7cf-463d-ab5f-5e2ea754c1ed)
- ![image](https://github.com/user-attachments/assets/d993ce87-b6f8-4f44-9ca7-546a646501d9)
In level 2, when the game expands from 2 options to 4, individuals tend to make riskier decisions. This increase in choices creates a false sense of control and confidence, leading players to believe they can better analyze and choose the best option. However, this often results in cognitive fatigue and quicker, more intuitive decisions, which are typically riskier. The fear of missing out on potential opportunities and the allure of higher rewards from risky options further drive players to take more risks when more choices are available. Consequently, individuals are more inclined to accept higher risks, even if these decisions don't always lead to desirable outcomes.
![image](https://github.com/user-attachments/assets/6aa81b3d-9661-438a-bddd-d9ac120d587c)




## Usage

To replicate our analysis, follow these steps:

1. Clone the repository:
    bash
    git clone https://github.com/soroor-ag/Game_Decision-Making_Analysis
    
2. Navigate to the project directory:
    ```bash
    cd decision-making-analysis-game
    
3. Install necessary dependencies:
    ```bash
    pip install python=3.12
    ```


## Conclusion

Our analysis provides insights into how cognitive biases and facial features correlate with decision-making behaviors. These findings can be expanded in future research to develop more accurate prediction models.
