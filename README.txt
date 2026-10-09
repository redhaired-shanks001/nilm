# ⚡ Smart Home NILM & Energy Disaggregation Dashboard

An interactive dashboard that simulates multi-appliance household electricity telemetry and runs a **Seq2Point Deep Convolutional Neural Network** to disaggregate the individual appliance loads from a single total household measurement.

## 🛠️ Tech Stack & Libraries
- **Deep Learning Layer**: TensorFlow 2.x & Keras (Seq2Point CNN architecture)
- **Data Engineering**: Pandas, NumPy
- **Interactive UI**: Gradio
- **Visualization**: Matplotlib

## 📊 Modeled Appliances
- **Air Conditioner (AC)**: High sustained load (1500W–2500W)
- **Fridge**: Cyclical periodic load (150W–300W)
- **Washing Machine**: Medium variable load (500W–1000W)
- **Kettle**: High-power, short spike (2000W–3000W)
- **Microwave Oven**: Medium-high short spike (1000W–1500W)

## 🚀 How to Run
1. Upload the `.ipynb` file to your Google Colab.
2. Run the notebook cells to train the Seq2Point neural network.
3. Launch the Gradio user interface directly inline to simulate consumption and view live disaggregation results!
