# deep-learning-projects

## Music generation

`music_generation.ipynb`

This project aims to generate MIDI files using a GRU architecture. The inputs to the model are several tracks from one instrument, and in the case of the generated MIDIs in the `midi_output` folder, drums from Megadeth were used. However, this architecture can also work well for generating guitar and bass tracks.

### Usage
To use this project, follow these steps:

1. Upload at least 30 MIDI files from a single instrument into your Google Drive account (or the Google Colab environment). The more MIDI files you upload, the better the model will be able to learn from the data.

2. Open the notebook `music_generation.ipynb` in Google Colab.

3. Mount your Google Drive account in the notebook and specify the path in the code.

4. Run the notebook.

5. The generated MIDI files will be saved to `output_midi_file.mid` file.
