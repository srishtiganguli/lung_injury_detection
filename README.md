# lung_injury_detection

git clone https://github.com/srishtiganguli/LungCTseg.git

# Navigate to the project directory
cd LungCTseg


# Process All Gradient Images
python code/process_all_gradient_images.py

# Compute ROI Gradient Matrix
python code/ROI_gradient_matrix.py

# Repair Contours Using Convex Hull
python code/repair_contours_convex_hull.py
