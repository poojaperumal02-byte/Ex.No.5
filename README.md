
## NAME: POOJA P
## REG.NO: 212224100041

# EXP 5: Comparing Prompting Techniques Through Engineering Problem-Solving Scenarios


# Aim:
   To compare different prompting techniques and evaluate their effectiveness in solving real-world engineering problems by using a problem selected from a student's 3rd-year or final-year project work. 


## AI TOOL REQUIRED

* ChatGPT

## PROJECT TITLE

**Smart Food Freshness Detection Using YOLOv8 and Machine Learning**

## PROBLEM STATEMENT

Checking fruits and vegetables manually to determine their freshness can require considerable time and may lead to inconsistent judgments. The aim of this project is to create an automated system that uses computer vision and machine learning to identify food items from images or webcam input and categorize them as **fresh or spoiled**.

## SELECTED ENGINEERING SCENARIO

The chosen engineering application is the **automated identification and classification of fresh and spoiled fruits and vegetables using computer vision**.

The same engineering problem is provided to ChatGPT using multiple prompting approaches to examine the differences in the generated solutions.

---

# EXPERIMENT PROCEDURE

### Step 1 – Choose the Engineering Problem

The engineering problem selected for the experiment is the automated detection and classification of fresh and spoiled fruits and vegetables.

### Step 2 – Prepare the Basic Prompt

A simple prompt is first created without applying any advanced prompting strategy.

### Step 3 – Use Various Prompting Methods

The same engineering requirement is rewritten using different prompting techniques to observe how the responses change.

---

# 1. Naïve / Basic Prompt

**Prompt:**

> How can computer vision be used to determine whether fruits and vegetables are fresh or spoiled?

### ChatGPT Response

Computer vision can help determine the freshness of fruits and vegetables by examining their visual properties from images. Image processing techniques and machine learning or deep learning algorithms can be used for this purpose.

A camera can capture an image of the food item, after which features such as color, texture, shape and surface condition can be analyzed. A trained classification model can then predict whether the item is fresh or spoiled.

---

# 2. Direct Prompt

**Prompt:**

> Recommend a computer vision approach for identifying fresh and spoiled fruits and vegetables using YOLOv8 along with machine learning.

### ChatGPT Response

A practical solution is to combine **YOLOv8** for detecting food objects with a machine learning classifier for determining their freshness.

The main procedure can be:

1. Gather images containing fresh and spoiled fruits and vegetables.
2. Label the food objects using suitable annotations.
3. Train a YOLOv8 detection model.
4. Identify the food item in a new image.
5. Extract visual properties such as color, texture and shape.
6. Apply a machine learning classifier to determine freshness.
7. Present the prediction to the user.

---

# 3. Role-Oriented Prompt

**Prompt:**

> Assume the role of a computer vision engineer and develop a simple system using YOLOv8 and machine learning to identify fresh and spoiled fruits and vegetables. Describe the required dataset, training process, image processing methods and prediction procedure.

### ChatGPT Response

As a computer vision engineer, the system can be organized into the following pipeline:

**Input Image → YOLOv8 Detection → Feature Extraction → ML Classification → Fresh/Spoiled Prediction**

### Dataset

The dataset should include images of multiple types of fruits and vegetables in both fresh and spoiled states.

### YOLOv8 Detection

YOLOv8 can identify and locate the food objects within an image using bounding boxes.

### Feature Extraction

Useful visual characteristics can include:

* Color
* Texture
* Shape
* Surface condition

### Classification

A machine learning algorithm such as **Random Forest** can be used to categorize the detected food item as fresh or spoiled.

### Output

The application displays the identified food item together with its predicted freshness condition.

---

# 4. Few-Shot Prompting

**Prompt:**

> Example 1: A bright red tomato with smooth skin → Fresh
> Example 2: A tomato showing dark spots and wrinkles → Spoiled
> Example 3: A yellow banana with black patches → Spoiled
>
> Using these examples as a reference, develop a computer vision system using YOLOv8 and machine learning to classify fruits and vegetables as fresh or spoiled.

### ChatGPT Response

The examples demonstrate that characteristics such as color, spots, wrinkles and surface condition can provide useful information for freshness classification.

The proposed approach is:

1. Detect the fruit or vegetable using YOLOv8.
2. Crop the detected object.
3. Perform image preprocessing.
4. Extract important visual features.
5. Train a classifier using fresh and spoiled samples.
6. Classify a newly provided image.
7. Display the predicted result.

A sufficiently large and varied dataset should be used so that the model performs well on different input images.

---

# 5. Stepwise Prompting

**Prompt:**

> Create a step-by-step solution for an automated food quality inspection system. The system must accept an image or webcam feed, identify fruits and vegetables using YOLOv8, classify them as fresh or spoiled with machine learning, and present the final prediction. Include the necessary preprocessing, training and evaluation procedures.

### ChatGPT Response

### Step 1 – Collect Data

Gather images representing both fresh and spoiled fruits and vegetables.

### Step 2 – Annotate Images

Mark the food objects with bounding boxes and assign suitable class labels.

### Step 3 – Preprocess Images

Resize the images and perform appropriate preprocessing before model training.

### Step 4 – Train YOLOv8

Train the YOLOv8 model using the annotated dataset to recognize and locate fruits and vegetables.

### Step 5 – Detect Objects

When an image or webcam frame is received, YOLOv8 identifies the food object.

### Step 6 – Extract Features

Analyze the detected region for visual properties such as color and texture.

### Step 7 – Classify Freshness

Use a machine learning classifier, such as Random Forest, to determine whether the item is fresh or spoiled.

### Step 8 – Evaluate the Model

Measure system performance using metrics such as accuracy, precision, recall and F1-score.

### Step 9 – Display the Result

Show the detected food item and its predicted freshness status to the user.

---

# COMPARISON / EVALUATION

| Prompting Method     | Quality   | Accuracy  | Depth     | Clarity   | Usefulness |
| -------------------- | --------- | --------- | --------- | --------- | ---------- |
| Naïve / Basic Prompt | Medium    | Medium    | Low       | Medium    | Medium     |
| Direct Prompt        | Good      | Good      | Medium    | Good      | Good       |
| Role-Oriented Prompt | Very Good | Very Good | High      | Very Good | Very Good  |
| Few-Shot Prompting   | Very Good | Very Good | High      | Good      | Very Good  |
| Stepwise Prompting   | Excellent | Very Good | Very High | Excellent | Excellent  |

The source experiment uses these same evaluation dimensions to compare the prompting approaches.

---

# ANALYSIS AND OBSERVATIONS

The experiment indicates that the way an engineering problem is described to ChatGPT has a significant effect on the quality of the generated response.

The **Naïve Prompt** provides a basic conceptual explanation with relatively little technical detail.

The **Direct Prompt** produces a more focused response because specific technologies such as YOLOv8 and machine learning are mentioned.

The **Role-Oriented Prompt** gives a more organized engineering solution by assigning ChatGPT the role of a computer vision engineer.

The **Few-Shot Prompt** provides examples that help establish the expected relationship between visual characteristics and freshness categories.

The **Stepwise Prompt** provides a detailed workflow covering the major stages from data collection through final prediction.

### Key Observation

Providing clear requirements, technologies and sequential instructions generally results in more detailed and useful AI-generated engineering responses. A simple prompt, however, remains suitable when only a general explanation is required.

---

# FINAL SELECTED PROMPTING METHOD

**Stepwise Prompting** was selected for the engineering problem because it provides:

* Well-organized responses
* Greater technical detail
* Clearly defined implementation stages
* Relevant engineering information
* A workflow that can be translated into a practical project

---

# REFINED / FINAL PROMPT

> Act as a computer vision engineer and develop an automated food freshness inspection system using YOLOv8 and machine learning. The system should accept an image or webcam input, identify fruits and vegetables, and classify every detected item as fresh or spoiled. Explain the complete process step-by-step, covering dataset creation, image labeling, preprocessing, YOLOv8 training, feature extraction, machine learning classification, performance evaluation and result visualization. Make the approach practical and appropriate for an engineering project.

---

# ENGINEERING VALIDATION

The proposed approach is technically feasible because:

1. **YOLOv8** can identify and locate food objects.
2. Image-processing methods can be used to obtain visual characteristics.
3. A machine learning algorithm such as **Random Forest** can perform freshness classification.
4. Images can be collected from datasets, cameras or webcams.
5. Accuracy, precision, recall and F1-score can be used to evaluate performance.
6. The final prediction can be presented through a graphical interface.

The experiment demonstrates that prompts containing specific requirements, technical details and clearly ordered instructions can generate more useful engineering solutions.

---

# CONCLUSION

The experiment compared multiple prompting approaches for an engineering application involving automated food freshness analysis. The comparison demonstrates that modifying the prompt structure can change the level of detail, organization and practical usefulness of the generated response.

The **Stepwise Prompting** approach provides a structured, implementation-focused workflow covering the major stages of the proposed system.

Therefore, clearly specifying the engineering problem, required technologies, processing stages and expected output is important when using ChatGPT to develop engineering solutions.

# RESULT

The engineering problem was successfully processed using different prompting approaches, and the generated responses were compared according to quality, accuracy, depth, clarity and usefulness.
