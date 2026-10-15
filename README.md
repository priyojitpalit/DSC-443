# DSC 443 midterm Binder environment

Upload the files in this folder to the root of a **public** GitHub repository. **Do not upload the solved notebook or Canvas answer key.**

Open https://mybinder.org and enter the repository URL. Choose `HEAD` as the branch/ref and the notebook file as the path, or use a link of the form:

`https://mybinder.org/v2/gh/USERNAME/REPOSITORY/HEAD?urlpath=lab/tree/DSC443_Midterm_Penguins_20261015_Student.ipynb`

When JupyterLab opens, run the first cell to check that TensorFlow imports and the local `penguins.csv` loads. Then check `Kernel -> Restart Kernel and Run All Cells` only in an instructor copy with the solutions filled in.

Run the full exam inside Respondus LockDown Browser with a student account before publishing the quiz. Place the Binder URL as a hyperlink in Question 1 (not only in quiz instructions), configured to open a new tab. In Respondus Advanced Settings allow specific external domains and add the actual domains revealed by your launched Binder instance, then confirm that the Jupyter kernel connects and executes. Redirects may be to `2i2c.mybinder.org`, `hub.2i2c.mybinder.org`, `bids.mybinder.org`, and other federation hubs; verify live domains rather than assuming this is complete. Do not add Google Colab to the allowlist.

Binder sessions are temporary. Students must submit answers in the Canvas quiz; notebook edits do not persist. TensorFlow installation is done when Binder builds the repository. It does not require `pip install` inside the exam.
