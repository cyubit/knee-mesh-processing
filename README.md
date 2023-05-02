# Automatic Generation of Patient-Specific Knee Models for Musculoskeletal Simulation

## Setup
1. Clone repository 
2. Open main.ipynb using your editor of choice (ex. Jupyter, Colab, etc)
3. Modify mesh paths to match your file structure
4. Make any desired tweaks
5. Run all cells

## Notes 
1. All PLOTTING code blocks can be excluded to improve processing speed, but should be included if you want to make tweaks and view how the mesh changes
2. [Meshes](/meshes/) contains the initial meshes extracted from MRI scans used in this project. These are all parts of a single knee
3. [MeanMesh](/MeanMesh/) contains the ideal manually processed meshes made using Autodesk Meshmixer
4. [MRImeshes](/MRImeshes/) contains more mesh files from a different knee that can be used for testing
5. [Processing steps](/PatientSpecificModelSteps.docx) contains some guidance that was used for this project
6. [Processed Mesh](/processed_femur_cartilage.stl) is the final processed output of the project code
