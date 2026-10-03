# CodeSnap

A coding workspace by Jacqualine Pruett with a scratch pad, seven built-in Python examples, and editable tabs for multiple programming languages.

## Use the Jupyter notebook

1. Download `CodeSnap.ipynb` to your computer.
2. Open Jupyter Notebook through Anaconda Navigator or your Jupyter shortcut.
3. Upload the notebook with Jupyter's **Upload** button, or open it from its saved folder.
4. Select **Run → Run All Cells**.
5. Enter a supported prompt, choose **Generate example**, edit the code, and choose **Save / Run Python**.

GitHub displays a static notebook preview. Interactive buttons run in Jupyter, not in the GitHub preview.

The notebook requires Python, `ipywidgets`, and IPython. If needed, run `%pip install ipywidgets` in a notebook cell and restart the kernel.

## Web workspace

The web version generates the same Python examples and runs Python inside your browser using Pyodide. The first run needs internet access to download Python. Each run uses fresh Python globals; execution stops after ten seconds, excluding loading time. Other language tabs support editing and downloading only. History is stored locally in your browser; exported code downloads to your device. Clearing browser storage removes history.

## Supported examples

Prime checking, FizzBuzz, sorting, largest value, factorial, Fibonacci, and a simple calculator. These use fixed sample inputs you can edit. This is a template-based prototype, not a general AI translator. C++, C, Java, JavaScript, C#, Go, Kotlin, and Rust tabs are editable placeholders.

Only run code you understand and trust. The local notebook's Python runs on your computer with your account's file permissions.

## Files

- `CodeSnap.ipynb`: downloadable Jupyter notebook
- `index.html`, `style.css`, `app.js`: browser interface
- `python-worker.js`: Python execution worker
- `examples.json`: example templates

Python runtime: https://pyodide.org/
