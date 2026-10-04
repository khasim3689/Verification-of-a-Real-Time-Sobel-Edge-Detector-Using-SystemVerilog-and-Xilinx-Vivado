Real-Time Sobel Edge Detector Using SystemVerilog and Xilinx Vivado
📌 Overview

A SystemVerilog-based real-time Sobel Edge Detector designed and verified using Xilinx Vivado. The project detects image edges by processing a 3×3 pixel window using horizontal and vertical Sobel filters.

⚙️ Working Principle
Input Pixel
     ↓
Pixel Storage
     ↓
3×3 Window
     ↓
Sobel Gx + Sobel Gy
     ↓
Gradient Magnitude
     ↓
Threshold
     ↓
Binary Edge Output

The gradient magnitude is calculated as:

$$ Magnitude = |G_x| + |G_y| $$

Pixels above the selected threshold are treated as edges.

🧩 Main Modules
pixel_bram.sv – Pixel storage
window_3x3.sv – 3×3 window generation
sobel_gx.sv – Gx calculation
sobel_gy.sv – Gy calculation
gradient_magnitude.sv – Gradient calculation
threshold.sv – Edge thresholding
sobel_top.sv – Top-level module
sobel_tb.sv – Testbench
🛠️ Tools & Technologies
SystemVerilog
Xilinx Vivado
RTL Design
Digital Image Processing
Sobel Edge Detection
📊 Applications
Computer Vision
Machine Vision
Robotics
Medical Image Processing
Industrial Inspection
Object Detection
🚀 Future Scope
Camera input integration
Real-time video processing
FPGA hardware implementation
Higher-resolution image support
Pipelined architecture for higher processing speed
👨‍💻 Project Outcome

Successfully designed and verified a modular Sobel Edge Detection RTL system using SystemVerilog and Xilinx Vivado.
