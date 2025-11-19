🛰️ Aapda-Predict: GeoAI Disaster Command Center

SkyHack 2025 - Round 2 Submission | Team: RockGame

"Saving lives when the sky goes dark."

🚨 The Problem: Flying Blind

During monsoon floods (like the 2024 Assam Crisis), disaster response teams face a critical failure point: Zero Visibility.

Optical Satellites (Sentinel-2) are completely blocked by heavy cloud cover.

Ground Sensors are often destroyed or submerged.

Result: Rescue teams operate reactively, unable to see where the water actually is or where it is going next.

💡 The Solution: X-Ray Vision for Disasters

Aapda-Predict is a real-time GeoAI Simulation & Command Center that fuses Sentinel-1 Synthetic Aperture Radar (SAR) data with advanced Computer Vision to "pierce" through the clouds.

We don't just map the present; we predict the future.

🌟 Key Features (Built & Deployed)

👁️ Live SAR Fusion: Real-time integration of Sentinel-1 Radar data to see through 100% cloud cover.

🤖 GeoAI Segmentation: An automated Computer Vision pipeline (OpenCV) that dynamically detects flood waters with adjustable sensitivity thresholds.

🌊 Depth Heatmap: Advanced distance-transformation algorithms to estimate flood depth, identifying the most dangerous "deep zones" for boat deployment.

📈 Predictive Analytics: Time-series forecasting of water levels for a 12-hour tactical window.

📄 Automated Mission Reports: One-click generation of PDF Situation Reports for field commanders.

🛠️ Tech Stack

Core Engine: Python 3.13

Interface: Streamlit (High-performance web dashboard)

Computer Vision: OpenCV (Headless), NumPy

Data Visualization: Altair (Interactive charts), Streamlit-Image-Comparison

Data Source: Copernicus Sentinel-1 (IW Mode SAR), Sentinel-2 (Optical)

🚀 How to Run Locally

Follow these steps to launch the Command Center on your machine:

Clone the Repository

git clone [https://github.com/](https://github.com/rock64728)/Aapda-Predict-SkyHack.git
cd Aapda-Predict-SkyHack


Install Dependencies

pip install streamlit opencv-python-headless pandas altair fpdf streamlit-image-comparison


Launch the Dashboard

streamlit run app.py


📸 System Capabilities

1. The "X-Ray" Reveal

Our slider interface proves the difference between optical blindness (left) and Radar clarity (right).
<img width="2553" height="1196" alt="image" src="https://github.com/user-attachments/assets/c51feacf-2c08-40b5-a486-9ae1bd39ff7f" />


2. Depth Heatmap & Analytics

Strategic depth estimation to prioritize rescue zones.
<img width="2506" height="1166" alt="image" src="https://github.com/user-attachments/assets/4800b91b-a10d-40af-866c-209daac59178" />


🔮 Future Roadmap

Phase 1 (Current): Prototype validation on historical Assam 2024 data.

Phase 2 (6 Months): Live API integration with ISRO's Bhuvan portal for real-time feed.

Phase 3 (1 Year): Deploy on edge devices for NDRF boats with offline capabilities.

👨‍💻 Team RockGame

Jenil Prajapati - Lead Developer & AI Engineer

Built with ❤️ for SkyHack 2025
