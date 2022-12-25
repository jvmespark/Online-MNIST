
# Online MNIST

An MNIST model deployed online


## Tech Stack

**Front End:** Javascript/HTML/CSS

**Backend:** Python: Flask, Pytorch


## Demo

Insert gif or link to demo


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

ML model data/stats. Param, optim, network breakdown.

![App Screenshot](MNIST_Results.png?raw=true)


## Usage

Clone the repo

```bash
    git clone https://github.com/d0ngeun/Online-MNIST.git
    cd Online-MNIST
```

Train the model
```bash
    cd ML_Model
    python3 model.py
```

Launch the Flask app
```bash
    cd..
    python -m flask --app server run
```    

## Acknowledgements

 - https://nextjournal.com/gkoehler/pytorch-mnist
 - https://papers.nips.cc/paper/1989/file/53c3bce66e43be4f209556518c2fcb54-Paper.pdf