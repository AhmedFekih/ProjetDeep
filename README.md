# Image Captioning — CNNs, Attention and Caption Refinement

Academic Deep Learning project exploring image-to-text generation, visual attention and caption refinement across Flickr8k, Flickr30k and MS COCO notebooks.

**Original team repository:** [hamdikbel/ProjetDeep](https://github.com/hamdikbel/ProjetDeep).

## Experiments

- CNN feature extraction and sequence decoding for image captioning.
- Google NIC and Log-Bilinear baselines in the Flickr8k notebook.
- Soft and hard attention, including a REINFORCE training workflow in the Flickr30k notebook.
- Caption-quality evaluation with BLEU and METEOR.
- Error analysis and refinement experiments using object detection, language models and image/text similarity.

## Notebooks

| Notebook | Contents |
| --- | --- |
| `Dataset_Flickr8k_Google NIC_et_Log_Bilinear_Ahmed_Fekih.ipynb` | Ahmed Fekih's named Flickr8k notebook: VGG features, NIC/Log-Bilinear models, evaluation and error/refinement analysis |
| `Dataset30k_Soft_Hard.ipynb` | Flickr30k soft/hard attention experiments and refinement workflows |
| `partie-coco-samar.ipynb` | MS COCO experiments, attention and multi-module caption processing |

## Technologies

Python, PyTorch, torchvision, Pandas, NumPy, Pillow, Matplotlib, NLTK, Transformers, spaCy and Ultralytics. Some experimental cells also import CLIP.

## Running the notebooks

1. Open the required notebook in Jupyter, Kaggle or a compatible notebook environment.
2. Install the dependencies imported by that notebook. A single validated dependency lockfile is not provided.
3. Obtain the corresponding dataset through its authorized distribution.
4. Adjust dataset paths and checkpoint locations to your environment.
5. Run preparation, training and evaluation cells in order. GPU support is recommended for training.

Datasets, downloaded pretrained weights and a fully reproducible execution environment are not bundled. Some paths are environment-specific. Training was not rerun for this documentation update, and no new performance claim is made.

## Attribution

This is a team project. The notebook filenames identify distinct workstreams; the named Flickr8k notebook provides a direct entry point into Ahmed Fekih's work. The original repository and Git authorship remain credited.
