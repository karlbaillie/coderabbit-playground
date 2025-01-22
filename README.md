# Streamlit Sample App To Test CodeRabbit

This is a simple test Streamlit application created solely to test CodeRabbit, a PR review tool. The actual functionality (data visualization with progress bars and charts) isn't important - it just provides something to make commits against.

## What it does

The app shows:

- A progress bar in the sidebar that fills from 0-100%
- A dynamic line chart that updates with random data
- A status text showing completion percentage
- A rerun button to restart the visualization

### How to run

1. Make sure you have Python installed on your system
2. Install the required dependencies:

   ```bash
   pip install streamlit numpy
   ```

3. Run the app with:

   ```bash
   streamlit run main.py
   ```
