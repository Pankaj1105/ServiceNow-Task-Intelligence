# Task Intelligence in ServiceNow

## Overview

Task Intelligence in ServiceNow leverages advanced machine learning and predictive analytics to streamline task management. It automates repetitive processes, enhances decision-making, and improves service efficiency by providing insights into task assignment, categorization, and prioritization.

---

## Benefits

1. **Improved Efficiency** - Automates repetitive processes, saving time and resources  
2. **Enhanced Accuracy** - Reduces errors by ensuring consistent task assignment and categorization  
3. **Cost Savings** - Reduces operational costs through automation  
4. **Better User Experience** - Speeds up resolution times, leading to increased customer satisfaction  

---

## Use Case: Incident Management

- Automatically assigns incidents to the correct support group (Assignment Group).

---

## Implementation Steps

### Step 1: Install Plugin
- Install the **Task Intelligence for ITSM** plugin.
<img width="983" height="149" alt="image" src="https://github.com/user-attachments/assets/bde75526-a37b-4747-b2f7-41220b52b3f1" />


### Step 2: Navigate to Task Intelligence
- Go to **Task Intelligence for ITSM** in the navigator and click on **Setup**.
<img width="486" height="175" alt="image" src="https://github.com/user-attachments/assets/59a6e514-543b-41fe-ae8a-8ca1b4715e7d" />


### Step 3: Enable Prediction
- In the setup window, scroll down to the option **Predict incident field choices to reduce handle time**.
<img width="740" height="322" alt="image" src="https://github.com/user-attachments/assets/2abb23a3-7ef5-44d2-97f4-560748de9dbc" />

### Step 4: Set Up Model
- Click on **Set up model** to begin the process.
<img width="366" height="513" alt="image" src="https://github.com/user-attachments/assets/01c6f589-c4a6-4d8e-b328-78626875c2e1" />

### Step 5: Configure the Model
<img width="268" height="207" alt="image" src="https://github.com/user-attachments/assets/793fda0c-0e0a-4719-a0e2-5c37b630b741" />

### Step 6: Train your model
- Fill the form
<img width="972" height="170" alt="image" src="https://github.com/user-attachments/assets/a8496334-953b-4acd-a4f8-88c10dedb8ea" />
<img width="970" height="421" alt="image" src="https://github.com/user-attachments/assets/b27ec739-bf98-405a-8f59-6a0c706c3299" />


- **Output Field**: Specify the field for which predictions are needed (e.g., Assignment Group)  
- **Input Fields**: Add fields that will influence predictions (e.g., Short Description, Description, Location)
<img width="974" height="430" alt="image" src="https://github.com/user-attachments/assets/098c6b31-854b-4bc0-a5d4-f1d127244bb1" />

- Train the model by filling out the training form and clicking **Launch Training**

### Step 7: Assess Your Model
- (Recommendation is has accurate chance)  
- On the prediction preference select the option
<img width="972" height="424" alt="image" src="https://github.com/user-attachments/assets/976d1983-617c-4633-a830-5aa84c54a978" />

→ **Save and Continue**

### Step 8: Deploy the Model
- Deploy the trained model to make it live.
<img width="971" height="415" alt="image" src="https://github.com/user-attachments/assets/b4eeb919-b545-42e2-89eb-160fff3aebec" />

### Step 9: Test Predictions
- Navigate to ServiceNow Operation Workspace and create new incident.
<img width="530" height="98" alt="image" src="https://github.com/user-attachments/assets/2ceb66e6-368b-4ec9-9aac-bf864cf05404" />

### Step 10: Observe Recommendations
- Below is the incident record example
<img width="987" height="331" alt="image" src="https://github.com/user-attachments/assets/b96c18a9-4972-4eee-973b-b508d11462aa" />

- Fill in the required fields (e.g., Short Description, Description, Location) in workspace. The system will automatically recommend an Assignment Group based on the model’s prediction.
<img width="965" height="553" alt="image" src="https://github.com/user-attachments/assets/200be9e3-d37a-4d97-af8d-b6c89a097fdb" />

- **Example Output**: It is the same assignment group which was selected in the incident record.

---
<img width="763" height="233" alt="image" src="https://github.com/user-attachments/assets/3b49d9de-a943-4120-8e6f-2d8d50a0d5a6" />

## Conclusion

Task Intelligence in ServiceNow simplifies incident management by automating task routing and categorization. By following these steps, organizations can reduce handling times, improve efficiency, and ensure a better user experience.
