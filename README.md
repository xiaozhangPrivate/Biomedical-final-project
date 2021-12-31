# Biomedical-final-project           [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xiaozhangPrivate/Biomedical-final-project/HEAD)
    # Using this reponsitory to realize 3 functions:
    1. Generate a MODEL to evaluate stereochemical quality of a given protein structure (with coordinates);
    2. Using interacted plot to view distribution of phi and psi of a single protein, a chain even a residue, or more;
    3. 3D structure of the choosed .pdb file
    
## Pre-processing
    See details in 合并df.zip
    data cleaning and merge.
    Verify the data with Biopython output.
    ![image](gallery/verify.png)
    
## RAMAplot model
    See details in code_for_RAMA_plot.ipynb
    References: Morris AL, MacArthur MW, Hutchinson EG, Thornton JM. Stereochemical quality of protein structure coordinates. Proteins. 1992;12(4):345-364.

    TOTAL WORKFLOW
    Data process 1:
    ![image](gallery/process1.png)

    Data process 2 (improved methods):
    ![image](/process2.png)
    
## Interacted plot
    The plot show the phi and psi based on above total dataframe from pre-processing
    ![image](gallery/verify.png)
    
    
## Using NGLview
    see details at https://github.com/nglviewer/nglview![image](https://user-images.githubusercontent.com/96851523/147740570-556d9e6c-b1a5-45f3-b674-7cb19329062f.png)
    ![image](gallery/3D_structure.png)
