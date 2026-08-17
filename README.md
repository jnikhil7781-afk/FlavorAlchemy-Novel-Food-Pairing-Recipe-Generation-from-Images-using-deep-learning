# FlavorAlchemy: Novel Food Pairing & Recipe Generation from Images

## 📌 Project Overview

**FlavorAlchemy** is an AI-powered food analysis and recipe generation project that identifies food ingredients from images and generates creative recipe ideas based on the detected ingredients.

The system combines **Computer Vision, Deep Learning, and Natural Language Processing (NLP)** to transform a food image into useful recipe suggestions.

Users can upload an image containing food ingredients, and the system analyzes the image, identifies possible ingredients, and generates suitable recipe combinations.

---

## 👨‍💻 Author

**Nikhil Jorepalli**
Artificial Intelligence and Data Science Student

---

## 🎯 Objectives

* Identify food ingredients from images.
* Discover interesting and compatible food combinations.
* Generate creative recipes automatically.
* Reduce the effort required to decide what to cook.
* Demonstrate the practical use of AI in food technology.
* Build an interactive AI-based recipe recommendation system.

---

## 🧠 Technologies Used

* **Python**
* **Deep Learning**
* **Computer Vision**
* **Convolutional Neural Networks (CNN)**
* **Transfer Learning**
* **Natural Language Processing (NLP)**
* **TensorFlow / Keras**
* **OpenCV**
* **NumPy**
* **Pandas**
* **Streamlit**
* **Jupyter Notebook / Google Colab**

---

## 🔄 System Workflow

```text
Food Image
    ↓
Image Preprocessing
    ↓
Ingredient Detection
    ↓
Food Classification Model
    ↓
Detected Ingredients
    ↓
Food Pairing Analysis
    ↓
Recipe Generation
    ↓
Suggested Recipe
```

---

## 📷 Image-Based Ingredient Detection

The system accepts an image as input and uses a computer vision model to identify visible food ingredients.

For example:

```text
Input Image
     ↓
Detected Ingredients:
• Tomato
• Onion
• Capsicum
• Cheese
```

These ingredients are then passed to the recipe generation component.

---

## 🧪 Food Pairing

FlavorAlchemy analyzes the detected ingredients and identifies combinations that can work well together.

For example:

```text
Tomato + Onion + Cheese
            ↓
    Compatible Combination
            ↓
      Recipe Generation
```

The system can suggest both familiar combinations and creative recipe ideas.

---

## 🤖 AI-Based Recipe Generation

After identifying ingredients, the system generates a recipe containing:

* Recipe name
* Ingredients
* Quantity suggestions
* Preparation steps
* Cooking instructions
* Optional substitutions

### Example

```text
Detected Ingredients:
Tomato, Onion, Cheese, Bread

Suggested Recipe:
Cheesy Tomato Toast

Ingredients:
- Bread
- Tomato
- Onion
- Cheese
- Salt
- Pepper

Steps:
1. Chop the tomato and onion.
2. Place the vegetables on the bread.
3. Add cheese and seasoning.
4. Toast until the cheese melts.
5. Serve hot.
```

---

## 🏗️ System Architecture

```text
                 ┌─────────────────┐
                 │   Food Image    │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Image Processing│
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Ingredient      │
                 │ Detection Model │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Detected        │
                 │ Ingredients     │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Food Pairing    │
                 │ Engine          │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Recipe          │
                 │ Generation      │
                 └────────┬────────┘
                          ↓
                 ┌─────────────────┐
                 │ Final Recipe    │
                 └─────────────────┘
```

---

## 📁 Project Structure

```text
FlavorAlchemy/
│
├── dataset/
│   └── food_images/
│
├── model/
│   └── ingredient_detection_model.h5
│
├── notebooks/
│   └── food_analysis.ipynb
│
├── src/
│   ├── image_processing.py
│   ├── ingredient_detection.py
│   ├── food_pairing.py
│   └── recipe_generation.py
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/FlavorAlchemy.git
```

### 2. Open the Project Directory

```bash
cd FlavorAlchemy
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Example dependencies:

```text
tensorflow
keras
opencv-python
numpy
pandas
pillow
scikit-learn
matplotlib
streamlit
```

---

## 🚀 How to Run

### Step 1: Start the Application

```bash
streamlit run app.py
```

### Step 2: Upload a Food Image

Upload an image containing one or more food ingredients.

### Step 3: Detect Ingredients

The AI model analyzes the image and identifies possible ingredients.

### Step 4: Generate Recipe

The detected ingredients are processed by the food pairing and recipe generation modules.

### Step 5: View the Result

The application displays the suggested recipe along with its ingredients and preparation instructions.

---

## 🖥️ Example Output

```text
Input:
Food Image

Detected Ingredients:
✓ Tomato
✓ Onion
✓ Cheese
✓ Bread

Recommended Recipe:
Cheesy Tomato Toast

Preparation Time:
15 minutes

Difficulty:
Easy
```

---

## 📊 Model Evaluation

The image classification component can be evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**

Recipe generation can be evaluated based on:

* Ingredient relevance
* Recipe diversity
* Food compatibility
* User feedback
* Overall recipe quality

---

## 💡 Applications

FlavorAlchemy can be useful for:

* Home cooking
* Recipe recommendation
* Food discovery
* Smart kitchen applications
* Food blogging
* Cooking assistance
* Personalized recipe generation
* AI-powered food applications

---

## 🔮 Future Enhancements

* Add real-time camera-based ingredient detection.
* Support a larger number of ingredients.
* Add dietary preferences such as vegetarian or vegan.
* Generate recipes based on available ingredients only.
* Add calorie and nutritional information.
* Add regional and international cuisines.
* Provide personalized recipes based on user preferences.
* Deploy the application as a mobile app.
* Improve ingredient detection using advanced vision models.

---

## ⚠️ Limitations

* Ingredient detection depends on image quality.
* Some ingredients may be hidden or difficult to identify.
* Visually similar ingredients can be confused.
* Generated recipes should be reviewed before cooking, especially for allergies or dietary restrictions.

---

## 🎓 Project Purpose

**FlavorAlchemy** demonstrates how **Computer Vision, Deep Learning, and Natural Language Processing** can work together to create an intelligent food recommendation system.

The project transforms a simple food image into ingredient information, creative food pairings, and practical recipe suggestions.

---

## 👨‍💻 Developed By

**Nikhil Jorepalli**
**Artificial Intelligence and Data Science**

> *Turning ingredients into ideas, and images into flavors.*
