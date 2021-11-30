# drone-detection

### Application Setup

1. Clone the repo: `git clone https://github.com/slapbot/drone-detection`
2. Cd into the directory: `cd drone-detection`
3. Create a virtual-env for python: `python -m venv drone-detection-env`
4. Activate the virtual-env: `source drone-detection-env/bin/activate`
5. Upgrade your pip to latest version: `pip install --upgrade pip`
6. Install numpy: `pip install numpy==1.17.0`
7. Install the application dependencies: `pip install -r requirements.txt`
	- This will install Tensorflow CPU, if you want to install GPU version, swap out tensorflow with tensorflow-gpu in `requirements.txt`
8. Run `python evaluate.py` to detect drones from one of the test image saved in the `Dataset` folder.
