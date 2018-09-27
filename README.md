# tensorflow-estimator-serving

Example of how to use tensorflow serving with an estimator.
The notebook in the `notebooks` folder implement a basic model for text classification using TensorFlow high-level API.
It covers the steps from data feeding to model deployment using `tensorflow-serving`.

## requirements:
- `curl`
- `python>=3.4`
- `docker`

## set-up the environment

Create a `venv`:

```sh
python3 -m venv venv
```

Activate it:

```sh
source venv/bin/activate
```

Install dependencies:

```sh
pip3 install -r requirements.txt
```

Install a python kernel for the project:

```sh
ipython kernel install --user --name=tensorflow-estimator-serving
```

### Run notebooks

Run `jupyter`:

```sh
jupyter-notebook
```
