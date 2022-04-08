# AVA-Challenge-Eval

## Install
conda create -n eval python=3.7
conda activate eval
pip install numpy
pip install matplotlib
make

## Run Evaluation
python main.py -g <ground_truth_path> -p <prediction_path>
