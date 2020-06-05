# Keyphrase Extraction using BERT

Deep Keyphrase extraction using BERT.

## Usage


1. From `bert` repo, untar the weights (rename their weight dump file to `pytorch_model.bin`) and vocab file into a new folder `model`.
2. Change the parameters accordingly in `experiments/base_model/params.json`. 
3. For training, run the command `python train.py --data_dir data/task1/ --bert_model_dir model/ --model_dir experiments/base_model`
4. For eval, run the command, `python evaluate.py --data_dir data/task1/ --bert_model_dir model/ --model_dir experiments/base_model --restore_file best`

## Credits

1. HuggingFace: https://github.com/huggingface/pytorch-pretrained-BERT
2. BERT: https://github.com/google-research/bert
