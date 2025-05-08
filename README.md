# New_York_Noise_Lib: Urban Sound Classification Dataset

This dataset is curated for the classification of common environmental and urban noise disturbances. It contains **100 labeled audio samples** organized into **10 categories**, based on the ten most frequently reported noise complaints from the NYC 311 dataset, and each with **10 recordings**. All audio files are **5 seconds long** and sampled at **44.1 kHz**.

---

## 📁 Dataset Structure

<img width="701" alt="Screenshot 2025-05-08 at 18 35 18" src="https://github.com/user-attachments/assets/1fee8af3-b624-4855-88c0-03ad16339b51" />


- Each category is stored in its own folder named after the sound label.
- The `metadata.csv` file provides additional metadata for each audio sample.

---

## 🧾 Metadata Fields

The `metadata.csv` includes the following columns:

| Column        | Description                                                   |
|---------------|---------------------------------------------------------------|
| `filename`    | Relative path to the audio file (e.g., `Loud Music (Party)/1-1.wav`) |
| `label`       | Human-readable label for the sound category                   |
| `duration_s`  | Duration of the clip in seconds (always 5)                    |
| `sample_rate` | Audio sampling rate (always 44100 Hz)                         |
<img width="701" alt="Screenshot 2025-05-08 at 18 35 18" src="https://github.com/user-attachments/assets/49d028b2-eca3-4738-9f4f-f30fdaf3fa3f" />

---

## 🔉 Sound Categories

Each of the following categories contains 20 samples:

1. **Loud Music (Party)**
2. **Jackhammering**
3. **Loud Talking*<img width="701" alt="Screenshot 2025-05-08 at 18 35 18" src="https://github.com/user-attachments/assets/95a69a70-8157-41c5-8887-2711409a1213" />
*<img width="701" alt="Screenshot 2025-05-08 at 18 35 18" src="https://github.com/user-attachments/assets/fb897eae-2bf4-40f9-b5c4-55c5244d1e37" />

4. **Car (Truck) Music**
5. **Barking Dog**
6. **Engine Idling**
7. **Air Condition (Ventilation Equipment)**
8. **Banging (Pounding)**
9. **Car (Truck) Horn**
10. **Alarms**

---

## 🛠️ Use Cases

This dataset can be used for:

- Sound event detection
- Audio classification
- Urban noise pollution analysis
- Real-time environmental monitoring
- Ideal for testing models like CNNs or transfer learning with pretrained audio embeddings (e.g., PANNs, YAMNet).

---

## 📜 License

Please contact me for usage rights.

---

