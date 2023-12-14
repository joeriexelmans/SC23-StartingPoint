Starting point for the Statecharts assignment of MoSIS in the academic year 2023-2024.

TIP: Clone this repository inside your ITEMIS workspace, and import it (without copying the files). This way, you can still do a `git pull` in case of a bug fix in the Python code.

Files related to the exercises:
  - **`exercises/`**: (DO NOT EDIT) directory that contains the exercises. Each exercise is a Statechart model that you can run/debug in ITEMIS.
  - **`exercises_test.py`**: (FEEL FREE TO EDIT) runs automated tests on the exercise models. Feel free to edit and run this file to understand the exercises better.


Files related to the assignment:
  - **`Statechart.ysc`**: (EDIT THIS) this is the Statechart model.
  - **`trafficlight_test.py`**: (ADD ONE TEST) runs automated tests on your Statechart. It already includes 3 test scenarios, which your solution **must pass**! You are not allowed to modify the existing tests. You must however **add one test** to it.
  - **`trafficlight_gui.py`**: (DO NOT EDIT) this script runs a TkInter GUI that allows you to interact with your Statechart


Common stuff:
  - **`PythonGenerator.sgen`**: (DO NOT EDIT) specifies how ITEMIS should generate Python code from the models.
  - **`src/`**: (DO NOT EDIT) Python sources authored by ITEMIS, needed to run generated Python code.
  - **`srcgen/`**: (DO NOT EDIT) This directory will be created to contain Python code generated from the models.
  - **`lib/`**: (DO NOT EDIT) Additional Python sources needed to run the GUI and the tests.


### Python dependencies

To run the Python scripts, you need the following:

  - **Python 3.x** (tested with 3.10) + **TkInter** (included in most Python distributions)
  - ITEMIS-**generated code** from the models (to force code generation, in ITEMIS right-click on `PythonGenerator.sgen`, and select "Generate Code Artifacts")
