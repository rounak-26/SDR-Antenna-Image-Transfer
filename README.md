# Performance of Various Antennas for Wireless Image Transfer Using Software-Defined Radio

This project demonstrates the wireless transfer of images using Software Defined Radio (SDR) with different antenna configurations at 5.8 GHz. The system uses **USRP B210**, **LabVIEW** for real-time transmission and reception, and **Python** for image preparation and quality analysis.

> 📌 Accepted and presented at **IEEE MAPCON 2025**

---

## 📁 Project Files

- `niUSRP EX PSK Tx.vi` – LabVIEW transmitter VI  
- `niUSRP EX PSK Rx.vi` – LabVIEW receiver VI  
- `image_processing.ipynb` – Python notebook for:
  - Converting images to bitstreams
  - Reconstructing received images
  - Calculating quality metrics (PSNR, SSIM, RMSE, PCC, NCC)
- `demo_video.mp4` – Project demonstration video
- `SDR_Image_Transfer_Report.pdf` – Complete technical project report

---

## 🧠 Technologies Used

- **SDR Platform**: USRP B210
- **Software**:
  - LabVIEW (for SDR communication and signal processing)
  - Python (for image pre/post processing)
- **Frequency**: 5.8 GHz
- **Modulation**: QPSK
- **Error Correction**: Convolutional encoding and Viterbi decoding

---

## 📊 Image Quality Metrics

- PSNR – Peak Signal-to-Noise Ratio  
- SSIM – Structural Similarity Index  
- RMSE – Root Mean Squared Error  
- PCC – Pearson Correlation Coefficient  
- NCC – Normalized Cross-Correlation

---

## 📺 Demo Video

▶️ The full system demonstration is available here:  
[`demo_video.mp4`](./demo_video.mp4)

---

## 📄 Project Report

The complete technical report for this project is available here:  
[`SDR_Image_Transfer_Report.pdf`](./SDR_Image_Transfer_Report.pdf)

---

## 👨‍💻 Author

**Rounak Deb**  
M.Sc. Electronics (2023–2025)  
University of Delhi South Campus  
📧 rounakdeb262002@gmail.com

---

## 📄 License

This project is open for educational and research purposes.  
Feel free to fork or adapt with credit.
