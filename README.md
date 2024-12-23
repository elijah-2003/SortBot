# SortBot: A Robotic Manipulator for Random Garbage Sorting
#### Efficient waste sorting with RGB-D perception, deep learning, and optimized motion planning
## Abstract
Waste management is a critical ecological and economic issue. Recycling is a possible solution but sorting of waste
prior sending the waste into the recycling plant is a big challenge. It has been shown in this project that autonomous robots can be used to tackle this challenge effectively. This paper reports on the successful development of an autonomous robotic system capable of detecting, classifying, and sorting waste from a conveyor belt into separate waste bins, in a recycling facility. Key challenges addressed in this project include accurate real-time pose prediction for moving objects, precise grasp estimation across varying object shapes, sizes, and materials, and seamless integration of object detection, classification, and trajectory planning for collision-free manipulation. The system leverages a RGB-D perception module for object detection, a deep neural network (DNN) for classification, antipodal grasp estimation for handling diverse object geometries, and optimized motion planning to enable accurate and efficient robotic manipulation in dynamic environments. Drake simulation results demonstrate the system’s potential to improve waste sorting processes in industrial recycling facilities, paving the way for a more sustainable and efficient waste management paradigm.
### Features
- Real-time object detection and classification using RGB-D perception.
- Antipodal grasp estimation for stable object handling.
- Optimized trajectory planning for dynamic environments.
- Seamless integration of object recognition, classification, and manipulation.

## **Demo Video**

[![SortBot in Action](https://img.youtube.com/vi/09qs1BsM_b8/0.jpg)](https://www.youtube.com/watch?v=09qs1BsM_b8)

Click the image above to watch SortBot in action!

## **Getting Started**

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/elijah-2003/SortBot.git
   cd SortBot
   ```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Open the main notebook:
```bash
jupyter notebook "[MERGE 4] Movement and static environment.ipynb"
```
### Future Work
- Expand the classifier to include more object types.
- Incorporate obstacle avoidance in trajectory planning.
- Test SortBot with different conveyor belt configurations.

### Full Paper
For a detailed description of the project, read the [research paper](https://drive.google.com/file/d/1IMicTLMNz9Z0NJ-SUjk_5lYFCx4S8WmN/view?usp=sharing).

#### License
This project is licensed under the MIT License.
