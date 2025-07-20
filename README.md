# fifo_sync_32bit

## 📊 Simulation Highlights
- FIFO is reset and written with 8 random 32-bit values.
- Attempts to write when full are safely ignored.
- Multiple read operations are performed, including underflow cases.
- `full` and `empty` flags behave as expected.
- Output waveforms confirm correct data flow and pointer updates.

## 💻 Usage
### Requirements:
- Xilinx Vivado 2024.2 or later
- GTKWave (optional, for `.vcd` viewing)
### Run Simulation:

1. Open `fifo_sync.xpr` in Vivado.
2. Run Behavioral Simulation.
3. Observe waveforms and status signals.

---
## 📌 Parameters
`DATA_WIDTH` - Width of data bus - `32` 
`FIFO_DEPTH` - Number of FIFO entries - `8` 

---

## 🧠 Applications
- UART/SPI receive/transmit buffering
- Inter-module data transfer
- Memory controller interfacing
- Producer-consumer synchronization

---

## ✍️ Author

- **SUBHAMRAJ** (Replace this with your actual name or GitHub username)
- www.linkedin.com/in/ksubhamrajpatra

---

## 📜 License
This project is open-source and free to use under the MIT License.



