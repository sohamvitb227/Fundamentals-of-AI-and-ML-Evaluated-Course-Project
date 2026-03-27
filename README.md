🖼️ Image Morpher & PDF Creator
Image Morpher & PDF Creator is a versatile, GUI-based Python utility designed for batch image processing. Whether you need to shrink high-resolution photos for web use or compile multiple scans into a single, professional PDF document, this tool handles the heavy lifting with a clean, intuitive interface.
________________________________________
🚀 Key Features
•	Batch Selection: Import multiple images (.jpg, .jpeg, .png, .bmp, .webp) in one go.
•	Precision Scaling: Scale images from 10% (heavy compression) up to 200% (upscaling) using a smooth slider.
•	Dual Processing Modes:
o	Image Mode: Batch resize and save files individually with automated naming (COMPRESSED_ or EXPANDED_).
o	PDF Mode: Merge all selected images into a single, multi-page PDF document.
•	Smart Formatting: Automatically converts transparent RGBA or Palette images to RGB to ensure compatibility with JPEG and PDF standards.
•	High-Quality Resampling: Utilizes the LANCZOS algorithm for superior downscaling quality.
________________________________________
🛠️ Installation & Setup
1. Prerequisites
Ensure you have Python 3.x installed on your system.
2. Install Dependencies
This project relies on the Pillow library for image processing. Install it via terminal or command prompt:
Bash
pip install Pillow
3. Run the Application
Navigate to the project directory and run:
Bash
python image_morpher.py
________________________________________
📖 How to Use
Step	Action	Description
1	Select Images	Click the "Select Images" button and choose your source files.
2	Choose Mode	Select "Resize" for individual files or "PDF" for a merged document.
3	Set Scale	Adjust the slider. 100% keeps the original dimensions.
4	Process	Hit "START PROCESSING" and choose your destination folder or filename.
________________________________________
🔍 Technical Implementation Details
•	GUI Framework: Built using tkinter, Python’s standard high-level GUI library.
•	Image Engine: Powered by Pillow (PIL).
•	Optimization: Individual images are saved using quality=85 and optimize=True to significantly reduce file size without noticeable quality loss.
•	Error Handling: Includes built-in message boxes to alert users of missing files or processing errors.
________________________________________
🤝 Contributing
Contributions are welcome! If you have ideas for new features (like cropping, rotation, or custom watermarking), feel free to fork the repository and submit a pull request.
________________________________________
📜 License
This project is open-source and available under the MIT License.
