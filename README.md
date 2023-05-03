# deep-learning-projects

## Emoji Classification

`emoji.ipynb`

Blog post: [emoji-tpu](https://nicovaras.github.io/posts/emoji-tpu/)

Here I try to classify which emoji should a tweet have. The project is intended to use TPUs.

### Usage

1. Choose an environment with TPU capabilities like Kaggle notebooks or Google Colab. 

If you are in Kaggle notebooks just import `rexhaif/emojifydata-en` dataset

If you are not in Kaggle notebooks:
  1. Install `kaggle` command: `pip install kaggle`
  2. Generate an API key in Kaggle and save it at `~/.kaggle/kaggle.json`
  3. Download the dataset `kaggle datasets download rexhaif/emojifydata-en`

Then, 

1. Run the notebook (adjusting the folder paths as needed)
2. (Optional) Remove the TPU code and check how long it takes for the GPU to process.

## VAE art

`VAE_art.ipynb`

Blog post: [VAE](https://nicovaras.github.io/posts/vae/)

In this project I try to generate landscapes using VAEs. The inputs to the model are landscapes from famous artists taken from the Wikiart project. 

### Usage
1. Run the notebook, it should be self contained.


## Music generation

`music_generation.ipynb`

This project aims to generate MIDI files using a GRU architecture. The inputs to the model are several tracks from one instrument, and in the case of the generated MIDIs in the `midi_output` folder, drums from Megadeth were used. However, this architecture can also work well for generating guitar and bass tracks.

### Usage
Blog post: [music-generation-gru](https://nicovaras.github.io/posts/music-generation-gru/)

To use this project, follow these steps:

1. Upload at least 30 MIDI files from a single instrument into your Google Drive account (or the Google Colab environment). The more MIDI files you upload, the better the model will be able to learn from the data.

2. Open the notebook `music_generation.ipynb` in Google Colab.

3. Mount your Google Drive account in the notebook and specify the path in the code.

4. Run the notebook.

5. The generated MIDI files will be saved to `output_midi_file.mid` file.


