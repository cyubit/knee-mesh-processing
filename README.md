# Automatic Generation of Patient-Specific Knee Models for Musculoskeletal Simulation

## Setup
1. Clone repository 
2. Open main.ipynb using your editor of choice (ex. Jupyter, Colab, etc)
3. Modify mesh paths to match your file structure
4. Make any desired tweaks
5. Run all cells

## Notes 
1. Updating mesh file paths may require an absolute path 
2. All PLOTTING code blocks can be excluded to improve processing speed, but should be included if you want to make tweaks and view how the mesh changes
3. [Meshes](/meshes/) contains the initial meshes extracted from MRI scans used in this project. These are all parts of a single knee
4. [MeanMesh](/MeanMesh/) contains the ideal manually processed meshes made using Autodesk Meshmixer
5. [MRImeshes](/MRImeshes/) contains more mesh files from a different knee that can be used for testing
6. [Processing steps](/PatientSpecificModelSteps.docx) contains some guidance that was used for this project
7. [Processed Mesh](/processed_femur_cartilage.stl) is the final processed output of the project code
