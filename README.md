# NeuralAmpModeler CI

**Quick start (no comments, copy lines)**

1. Create an empty GitHub repo.
2. Upload the `.github/workflows/build_nam_au.yml` file to the repo (already done in this repository).
3. Go to Actions and run the **Build NAM AU** workflow.
4. After it finishes, open the workflow run and download the **NeuralAmpModeler_AU** artifact.

This workflow builds the stock NeuralAmpModeler AU on a macOS runner and sets CMP0042 to NEW for compatibility.
