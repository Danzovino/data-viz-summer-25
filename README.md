# Data Visualization

This repository holds course materials for the Data Visualization course offered as part of the Johns Hopkins Bloomberg School of Public Health Graduate Summer Institute of Epidemiology and Biostatistics.

## Course Textbook

We will use Kieran Healy's **Data Visualization: A Practical Introduction**, [available for free at socviz.co](https://socviz.co/) and for purchase on [Amazon](https://www.amazon.com/gp/product/0691181624/ref=as_li_tl?ie=UTF8&tag=kieranhealysw-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=0691181624&linkId=16d53b3cc1ec3bc3aac60b27c29b92e8). 

## Repository Structure

```
├── assignments/       # Course assignments
├── data/              # Selected data sets
├── lectures/          # Course lecture materials and slides
├── examples/          # Worked examples and code samples
├── work/              # Student work and assignments (your work goes here)
├── scratch/           # Temporary files and experiments (.gitignored)
├── Syllabux.docx      # Copy of course syllabus
├── .gitignore         # Git ignore rules
└── README.md          # This document
```

## Getting Started

To get started with this using this repository for this course:

1. Click the "Fork" button in the top-right corner of this repository
2. This will create your own copy of the repository under your GitHub account
3. Clone your forked repository using one of these methods:

   **Option 1: Using RStudio Project Wizard**
   1. Open RStudio
   2. Go to File → New Project
   3. Select "Version Control"
   4. Choose "Git"
   5. In the "Repository URL" field, paste your forked repository URL:
      ```
      https://github.com/YOUR-USERNAME/data-viz-summer-25.git
      ```
   6. Choose where you want to store the project on your computer
   7. Click "Create Project"
   8. RStudio will automatically open the project for you

   **Option 2: Using Command Line**
   ```bash
   git clone https://github.com/YOUR-USERNAME/data-viz-summer-25.git
   ```
   Then open the project in RStudio:
   1. Open RStudio
   2. Go to File → Open Project
   3. Navigate to where you cloned the repository
   4. Select the `data-viz-course.Rproj` file

4. You can now work with the materials locally and push changes to your fork

Note: If you want to keep your fork up to date with the original repository, you can add it as a remote:
```bash
git remote add upstream https://github.com/original-owner/data-viz-summer-25.git
git fetch upstream
git merge upstream/main
```

## Working with the Repository

### Where to Put Your Work
- Place all your assignments and work in the `work/` directory
- Since you have your own fork of the repository, you can work directly in the `work/` directory
- The `work/` directory is specifically designed for student contributions and won't conflict with course materials

### Avoiding Conflicts
- Course materials in `lectures/` and `examples/` will be updated by the instructors
- By keeping your work in the `work/` directory, you can safely pull updates from the original repository without conflicts
- If you need to experiment or try things out, use the `scratch/` directory (it's gitignored)
- If you modify files outside the `work/` directory, you may encounter merge conflicts when trying to pull updates from the original repository.

## Author

The materials in this course were put together by [Erik Westlund](mailto:ewestlund@jhu.edu), Department of Biostatistics,  Johns Hopkins Bloomberg School of Public Health.