# Reproducability Challenge COMP6248

## Group Members
- Anthony Scregg
- Edvin Piaulokas
- Jack Seabrook
- Harry Porter

## Link to Original Paper
[Data Augmentation in Training CNNs: Injecting Noise to Images](https://openreview.net/forum?id=)

## Notes About the Code
- None of the authors original code was used for this project
- There are a large number of models that are trained in the notebook and hence GPU acceleration is recommended if you wish to run the notebook, the recommended environment is Google Colab with a GPU runtime
- The total excecution time for the notebook is 8+ hours if none of the model weights are preloaded
  - set `load = False` in the `trainPipeline` function if you wish to train the models from scratch
