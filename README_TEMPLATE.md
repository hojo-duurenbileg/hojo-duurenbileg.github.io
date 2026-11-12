# Project name

One or two sentences: what this does and why it matters.

![Result](docs/result.png)

## Results
- The headline number, for example "Sub-0.1-pixel RMS precision on 14 test targets".
- What it was tested on (data size and conditions).

## Method
A short description of the approach: the model, the estimation method and any key design choices.
Link to the paper or a write-up if there is one.

## How to run

### C++
```bash
mkdir build && cd build
cmake ..
make
./project_name ../data/sample_input
```

### Python
```bash
pip install -r requirements.txt
python src/main.py --input data/sample_input
```

## Repository layout
```
src/        source code
include/    headers (C++)
data/       small sample data so the example runs
docs/       figures used in this README
```

## What I would improve next
- One or two honest next steps.

## License
MIT
