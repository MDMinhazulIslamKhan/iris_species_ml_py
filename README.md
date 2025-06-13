# Iris Species Analysis

This project contains code and data for analyzing the Iris Species dataset.

## Getting Started

Follow these instructions to set up the project locally.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone ... ...
    cd iris_species_ml
    ```

2.  **Create a virtual environment:**

    It's recommended to use a virtual environment to manage project dependencies.

    ```bash
    python -m venv iris_env
    ```

3.  **Activate the virtual environment:**

    - **On Windows:**
      ```bash
      .\iris_env\Scripts\activate
      ```

4.  **Install dependencies:**

    Once the virtual environment is active, install the required packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

### Managing Dependencies

If you add new packages to your project, follow these steps to update your `requirements.txt` file:

1.  **Activate your virtual environment** (if not already active).

    - **On Windows:**
      ```bash
      .\iris_env\Scripts\activate
      ```
    - **On macOS/Linux:**
      ```bash
      source iris_env/bin/activate
      ```

2.  **Install the new package(s):**

    ```bash
    pip install new-package-name
    ```

    (Replace `new-package-name` with the actual package name you want to install.)

3.  **Update `requirements.txt`:**

    After installing new packages, update your `requirements.txt` file to reflect the changes:

    ```bash
    pip freeze > requirements.txt
    ```
