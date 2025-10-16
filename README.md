git clone https://github.com/your-username/captcha-solver-002.git
    cd captcha-solver-002
    ```
2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Solver

The solver can typically be run by providing an image file containing the CAPTCHA.

```bash
python main.py --image_path path/to/your/captcha.png