

# EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios

# Aim:To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using a problem selected from a student's 3rd-year or final-year project work. 

### AI Tools Required: 

# EXPERIMENT OVERVIEW

In this experiment, each student/team selects a genuine problem from their ongoing or completed 3rd-year or final-year engineering project.
The same engineering problem is given to an AI system using different prompting techniques. Students then compare the responses based on relevance, accuracy, completeness, clarity, feasibility and usefulness.
The purpose is not simply to obtain an AI-generated answer. Students must analyse how changing the prompting technique changes the quality of the solution.

EXPERIMENT PROCEDURE
Step 1 – Select the Engineering Problem
Choose one genuine problem from the student's 3rd-year or final-year project.
Step 2 – Write the Base Prompt
Write a simple prompt describing the engineering problem without using advanced prompting techniques.
Step 3 – Apply Different Prompting Techniques
Rewrite the same problem using at least four different prompting techniques.
For example:
Technique 1 – Straightforward Prompt
Suggest a method to detect crop diseases using computer vision.structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

**STUDENT SUBMISSION FORMAT**
Each student/team should submit:
Project title and problem statement
Selected engineering scenario
Base prompt
Minimum four improved prompts using different techniques
AI-generated outputs
Comparison/evaluation table
Analysis and observations
Final selected prompting technique
Refined/final prompt
Engineering validation


# OUTPUT

## 2. AI TOOLS REQUIRED

- ChatGPT (OpenAI)
- Python
- TensorFlow / Keras
- OpenCV

## 3. PROJECT TITLE

**AI-Based Crop Disease Detection and Advisory System Using Deep Learning**

## 4. SELECTED ENGINEERING SCENARIO

### Problem Statement

Agriculture is an important sector, but crop diseases significantly affect agricultural productivity and food quality. Farmers often identify plant diseases through manual observation, which requires agricultural knowledge and experience.

Early identification of crop diseases is difficult because different diseases may produce similar symptoms on plant leaves. Delayed detection can result in crop damage and reduced agricultural production.

Therefore, an intelligent system is required to automatically identify crop diseases using leaf images and provide suitable recommendations to farmers.

### Proposed Solution

Develop an AI-based Crop Disease Detection System using Computer Vision and Deep Learning.

The system allows farmers to upload or capture an image of a crop leaf. A trained Convolutional Neural Network (CNN) analyses the image and identifies whether the leaf is healthy or affected by a disease.

The system provides:
1. Leaf image uploading through a user interface.
2. Image preprocessing using OpenCV.
3. Disease classification using a CNN model.
4. Identification of healthy and diseased leaves.
5. Disease name and prediction confidence.
6. Basic preventive measures and agricultural recommendations.

### Technologies Used

- Frontend: HTML, CSS and JavaScript.
- Backend: Python and Flask.
- Image Processing: OpenCV.
- Deep Learning: TensorFlow and Keras.
- Model: Convolutional Neural Network (CNN).
- Dataset: PlantVillage dataset.

## 5. BASE PROMPT (NAÏVE PROMPT)

A simple prompt is given to ChatGPT without providing detailed instructions or constraints.

### Prompt 1 – Naïve Prompt

"Develop an AI system to detect crop diseases using computer vision."

### AI-Generated Output

An AI-based crop disease detection system can be developed using image processing and deep learning techniques.

The system accepts images of plant leaves and analyses them using a trained CNN model. It identifies whether the plant is healthy or affected by a disease.

The system can use Python, OpenCV and TensorFlow for image processing and classification. A dataset containing healthy and diseased plant images can be used to train the model.

The final system can display the detected disease and provide recommendations to farmers.

## 6. IMPROVED PROMPTS USING DIFFERENT PROMPTING TECHNIQUES

### TECHNIQUE 1: ROLE-BASED PROMPTING

**Prompt 2:**

Act as an experienced AI and Machine Learning engineer specializing in computer vision and agricultural technology.

Design an AI-based crop disease detection system that identifies plant diseases from leaf images.

Explain the system architecture, image preprocessing methods, CNN model selection, training process and suitable technologies.

Also explain how the system can help farmers identify diseases early and improve agricultural productivity.

### AI-Generated Output

An AI-based crop disease detection system can be developed using a Convolutional Neural Network.

The system consists of the following modules:

1. Image Acquisition: Collect leaf images using a mobile camera or upload facility.
2. Image Preprocessing: Resize images, normalize pixel values and remove unnecessary variations using OpenCV.
3. Feature Extraction: CNN automatically extracts important visual features such as spots, discoloration and leaf patterns.
4. Disease Classification: The trained CNN classifies the leaf into healthy or disease categories.
5. Result Generation: Display the predicted disease name and confidence score.
6. Recommendation Module: Provide general preventive measures based on the predicted disease.

Suitable technologies include Python, OpenCV, TensorFlow, Keras and Flask.

A dataset such as PlantVillage can be used for model training and evaluation.

The system can help farmers identify potential diseases earlier and reduce dependence on manual identification.

### TECHNIQUE 2: ZERO-SHOT PROMPTING

**Prompt 3:**

Design a complete AI-based crop disease detection system using deep learning without providing any examples.

Explain how the system can process plant leaf images, identify diseases, classify healthy and infected leaves and generate agricultural recommendations.

Include the architecture, workflow, algorithms, technologies and expected outcomes.

### AI-Generated Output

A crop disease detection system can be developed using a pretrained or custom-trained CNN model.

The system follows these steps:

1. Collect plant leaf images.
2. Preprocess the images by resizing and normalization.
3. Divide the dataset into training, validation and testing sets.
4. Train the CNN model using labelled images.
5. Extract image features through convolution and pooling layers.
6. Classify the images using fully connected layers and a Softmax output layer.
7. Display the predicted disease and confidence score.
8. Provide relevant preventive recommendations.

Transfer learning using models such as MobileNetV2 or ResNet50 can also be considered to improve development efficiency.

The expected outcome is an automated system that classifies selected plant diseases from leaf images.

### TECHNIQUE 3: FEW-SHOT PROMPTING

**Prompt 4:**

Develop an AI-based crop disease detection system using CNN.

Follow the examples below to understand the expected classification output.

Example 1:

Input: Tomato leaf image showing yellow and brown concentric spots.

Expected Output:
- Crop: Tomato
- Predicted Disease: Early Blight
- Condition: Diseased
- Recommendation: Remove severely affected leaves and follow appropriate crop protection practices.

Example 2:

Input: Green tomato leaf without visible disease symptoms.

Expected Output:
- Crop: Tomato
- Predicted Disease: Healthy
- Condition: Healthy
- Recommendation: Continue regular crop monitoring.

Now design a system that can classify different crop diseases using leaf images.

Explain the model architecture, training process, dataset requirements and output generation.

### AI-Generated Output

The proposed system uses few-shot prompting to understand the expected classification format through sample inputs and outputs.

A CNN model can be trained using labelled plant leaf images.

The classification process includes:

1. Input leaf image.
2. Image resizing and normalization.
3. CNN feature extraction.
4. Disease classification.
5. Prediction result generation.

The output can contain:

- Crop name.
- Predicted disease.
- Healthy or diseased condition.
- Prediction confidence.
- Preventive recommendations.

The examples help establish a consistent result format. However, the actual disease prediction depends on the trained model and image quality, not on the examples in the prompt alone.

### TECHNIQUE 4: STEP-BY-STEP PROMPTING

**Prompt 5:**

Analyse the crop disease detection problem step by step.

Design an AI-based crop disease detection system using computer vision and deep learning.

Explain the solution in the following stages:

1. Identify the major agricultural problem.
2. Explain dataset collection.
3. Describe image preprocessing.
4. Explain CNN architecture and working.
5. Describe model training and testing.
6. Explain disease classification.
7. Suggest suitable technologies.
8. Identify possible limitations and improvements.

Provide a detailed and structured engineering solution.

### AI-Generated Output

The crop disease detection problem can be solved using a systematic deep learning workflow.

**Step 1 – Problem Identification:**

Farmers face difficulties in identifying crop diseases at an early stage through manual observation.

**Step 2 – Dataset Collection:**

Collect labelled images of healthy and diseased plant leaves using datasets such as PlantVillage.

**Step 3 – Image Preprocessing:**

Resize images into a fixed dimension, normalize pixel values and apply data augmentation techniques such as rotation and flipping.

**Step 4 – CNN Architecture:**

Use convolutional layers for feature extraction, pooling layers for dimensionality reduction and fully connected layers for classification.

**Step 5 – Model Training:**

Train the CNN using labelled images and evaluate its performance using validation data.

**Step 6 – Disease Classification:**

The model predicts the disease category using a Softmax classification layer.

**Step 7 – Result Generation:**

Display the disease name, confidence score and general preventive recommendations.

**Step 8 – Limitations:**

Lighting conditions, blurred images, similar disease symptoms and insufficient training data may affect prediction accuracy.

These limitations can be reduced through data augmentation, diverse datasets, transfer learning and real-world field testing.

### TECHNIQUE 5: CONSTRAINT-BASED PROMPTING

**Prompt 6:**

Design an AI-based crop disease detection system under the following engineering constraints:

1. The system must identify diseases using plant leaf images.
2. Use a CNN or lightweight deep learning model.
3. The system should work with limited computational resources.
4. Use Python and OpenCV for image processing.
5. Use TensorFlow or Keras for model development.
6. The system should support a simple web interface.
7. The prediction should include disease name and confidence score.
8. The system should provide basic preventive recommendations.
9. The system should be suitable for small-scale farmers.
10. Consider practical limitations such as poor lighting, image quality and dataset imbalance.

Provide a technically feasible architecture, model selection, implementation workflow and expected results.

### AI-Generated Output

A lightweight crop disease detection system can be developed using MobileNetV2 or a small CNN architecture.

The proposed system includes:

- Frontend: HTML, CSS and JavaScript.
- Backend: Python and Flask.
- Image Processing: OpenCV.
- Deep Learning: TensorFlow and Keras.
- Dataset: PlantVillage.
- Model: MobileNetV2 with transfer learning.

The workflow is:

1. Farmer uploads a leaf image.
2. OpenCV preprocesses the image.
3. The trained model analyses the image.
4. The model predicts the disease category.
5. The application displays the disease name and confidence score.
6. A recommendation module provides general preventive measures.

A lightweight model can reduce computational requirements and improve suitability for resource-constrained devices.

The system should be tested using images captured under real agricultural conditions before deployment. It should also include a provision for uncertain predictions instead of forcing an unreliable disease classification.

## 7. COMPARISON OF AI-GENERATED RESPONSES

The responses generated using different prompting techniques are compared based on quality, accuracy, depth, feasibility and usefulness.

| Prompting Technique | Quality | Accuracy | Depth | Feasibility |
|---|---|---|---|---|
| Naïve Prompt | Medium | Medium | Low | Medium |
| Role-Based Prompt | High | High | High | High |
| Zero-Shot Prompt | High | High | High | High |
| Few-Shot Prompt | High | High | Medium | High |
| Step-by-Step Prompt | Very High | High | Very High | High |
| Constraint-Based Prompt | Very High | High | Very High | Very High |

## 8. ANALYSIS AND OBSERVATIONS

The experiment demonstrates that different prompting techniques produce different levels of response quality.

**1. Naïve Prompting:**

The naïve prompt provides a basic overview of crop disease detection. However, it does not explain the complete architecture, model training or implementation requirements.

**2. Role-Based Prompting:**

Assigning the role of an AI engineer generates a more technical response. It provides suitable algorithms, technologies and system components.

**3. Zero-Shot Prompting:**

The system generates a solution without examples. It successfully identifies the important stages of image processing and disease classification.

**4. Few-Shot Prompting:**

Providing sample inputs and outputs helps ChatGPT understand the expected classification format. It improves the consistency and organization of the generated response.

**5. Step-by-Step Prompting:**

Dividing the problem into smaller stages produces a detailed and systematic explanation. It covers dataset collection, preprocessing, training, testing and classification.

**6. Constraint-Based Prompting:**

Adding practical engineering constraints produces a more realistic solution. It considers hardware limitations, lightweight models and usability for farmers.

### Overall Observation

- Clear prompts generate more relevant answers.
- Providing context improves technical depth.
- Examples improve output consistency.
- Step-by-step instructions improve completeness.
- Engineering constraints improve practical feasibility.
- Simple prompts are useful for basic questions, while complex engineering problems require structured prompting.

## 9. FINAL SELECTED PROMPTING TECHNIQUE

**Selected Technique: Constraint-Based Prompting Combined with Step-by-Step Prompting.**

This combination is selected because the crop disease detection project requires a technically feasible solution that considers model selection, image processing, dataset quality, computational limitations and real-world agricultural conditions.

Constraint-based prompting ensures that the proposed system follows the engineering requirements, while step-by-step prompting provides a systematic development approach.

## 10. REFINED / FINAL PROMPT

Act as a senior AI and Machine Learning engineer specializing in computer vision and agricultural technology.

I am developing a project titled "AI-Based Crop Disease Detection and Advisory System Using Deep Learning."

The objective is to develop an intelligent system that identifies crop diseases from plant leaf images and provides suitable recommendations to farmers.

Design a complete and technically feasible solution by following these requirements:

1. Use a CNN-based deep learning architecture for disease classification.
2. Use OpenCV for image preprocessing.
3. Use TensorFlow or Keras for model development.
4. Use a suitable labelled dataset such as PlantVillage.
5. Consider MobileNetV2 or another lightweight model for limited computational resources.
6. Develop a simple web interface using HTML, CSS and JavaScript.
7. Use Python and Flask for backend integration.
8. Display the predicted disease name and confidence score.
9. Provide basic preventive recommendations.
10. Consider real-world limitations such as lighting conditions, image quality and similar disease symptoms.

Explain the solution step by step, covering:

- Problem identification.
- System architecture.
- Dataset collection.
- Image preprocessing.
- CNN model architecture.
- Model training and evaluation.
- Disease classification.
- Frontend and backend integration.
- Expected results.
- Limitations and future improvements.

Present the solution in a structured engineering format. Ensure that the proposed implementation is technically feasible and distinguish expected performance from experimentally verified results.

## 11. ENGINEERING VALIDATION

The proposed solution is evaluated against the engineering requirements.

| Engineering Requirement | Validation |
|---|---|
| Plant leaf image input | Supported through image upload |
| Image preprocessing | OpenCV can perform resizing and normalization |
| Disease classification | Supported through CNN |
| Dataset availability | PlantVillage provides labelled leaf images |
| Lightweight model | MobileNetV2 can be considered |
| Web application | Can be developed using Flask |
| Disease identification | Model generates predicted disease classes |
| Prediction confidence | Can be displayed using classification probabilities |
| Farmer recommendations | Can be generated using a verified recommendation database |
| Real-world usability | Requires field testing with actual crop images |

The proposed architecture is technically feasible for a prototype. However, actual classification accuracy, response time and performance must be measured after implementation using independent test images.

## PROMPT

```
Act as an AI and Machine Learning expert. Develop an AI-based crop disease detection system using plant leaf images. Explain how the system identifies crop diseases and suggests suitable preventive measures. Provide the solution with a brief explanation of the technologies and working process.
```
## 12. CONCLUSION

This experiment demonstrated the importance of prompt engineering in solving real-world engineering problems using Generative AI.

Different prompting techniques produced different levels of response quality, technical depth and completeness.

Naïve prompting generated a basic solution, whereas role-based, zero-shot, few-shot, step-by-step and constraint-based prompting improved the structure and usefulness of the generated responses.

Among the evaluated techniques, constraint-based prompting combined with step-by-step prompting provided the most suitable engineering solution because it considered both technical requirements and practical implementation limitations.

Thus, selecting an appropriate prompting technique helps engineers obtain more relevant, accurate, complete and feasible solutions from AI systems.

# RESULT: The prompt for the above said problem executed successfully
