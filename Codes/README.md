# Federated Learning using PHE

## Setup

The code was written and tested using -

-   Python 3.7.3
-   Pip 20.0.2

To setup the project and install its dependencies, you need to run the `requirements.txt`.

```bash
pip install -r requirements.txt
```

## How to run

To test the Federated Learning vs the Local training, go to the `src` folder and run the project. This can be done as

```bash
cd src/
python federatedlearning_phe.py
```

You can experiment with it using the following flags :

-   dataset choice between grad_school and breast_cancer (`--dataset`, default = breast_cancer)
-   number of clients (`--n_clients`, default = 3)
-   gradient descent learning rate (`--lr`, default = 0.05)
-   number of iterations (`--n_iter`, default = 15)
-   Pallier key length (`--key_length`, default = 1024)