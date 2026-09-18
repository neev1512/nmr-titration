# NMR Titration

A web app for planning NMR titrations with the simulation-guided "swapping" strategy:

1. **Simulate binding curves** for a 1:1 complex (P + L ⇌ PL) in fast exchange
2. **Swapping strategy**: the volumes to swap between tubes A and B at each step
3. **Estimate K<sub>d</sub>** from the A<sub>0</sub>, A<sub>1</sub> and B<sub>0</sub> points
4. **Export** a PDF report or a ZIP of all plots (PNG) and data (CSV)

All calculations run in your browser. Nothing you type is sent anywhere. In Chrome or Edge you can install it as an app (**Install app** button, or the install icon in the address bar), and in Safari on macOS use **File → Add to Dock**. Once installed, it works offline.

Based on: Dcosta N, Black M, Huang R. *A simulation-guided "swapping" protocol for NMR titrations to study protein–protein interactions* (2024). Original notebook: [Google Colab (version 2)](https://colab.research.google.com/drive/1ibG-32ZzZIje11yDrjX1_1Ryd5j3H8_n).
