# Word2vec functionality in PyTorch

- Inspired by [this](https://github.com/Andras7/word2vec-pytorch)

- Compile the data by running the following script on FxFA (a Fractured Atlas application)
```ruby
Campaign.all.each do |campaign|
  File.write('corpus.txt', campaign.description, mode: 'a')
end
```


### Dependencies
`pip install tqdm`
`pip install torch`
`pip install numpy`

I am running Python 3.5 via Conda.

### Train the corpus
`python trainer.py`

- See the Jupyter Notebook for similar word results.
