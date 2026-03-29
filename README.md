# 🧠 NeRF Model Project

This project implements a Neural Radiance Fields (NeRF) model for 3D scene reconstruction and novel view synthesis using deep learning.

---

## 🚀 Features

- 📸 Train NeRF model using multi-view images
- 🎥 Generate novel views as GIFs
- 🌐 Web-based interface for interaction
- 🧠 Deep learning-based rendering pipeline

---

## 🛠️ Tech Stack

- Python
- PyTorch
- FastAPI (Backend)
- HTML/CSS/JavaScript (Frontend)

---

## 📁 Project Structure
Model/
├── NeRF.py # Core NeRF model
├── generate_gif.py # GIF generation
Web App/
├── backend/ # API + database
├── static/ # Frontend files


---

## ⚙️ Installation

```bash
pip install -r requirements.txt
▶️ How to Run
Run Backend:
cd Web App/backend
python main.py
Run Model:
cd Model
python NeRF.py
📊 Output
Generates rendered views
Supports GIF visualization
⚠️ Note

Large files such as datasets and trained models are excluded from this repository. You can add your own dataset in the data/ folder and train the model.



## 🎥 Output

![sample](outputs/sample.gif)

