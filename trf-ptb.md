# Understand this toolkit

* `run_baseline_ngram.py`: train ngram LMs and used to rescore n-best list. This need install SRILM toolkit first by 
```
cd tools
./install_srilm.sh
```
* `run_lstm.py`: train LSTM LM with standard softmax. The source code of LSTM is in `tfcode/lm/lstmlm.py`.
* `run_lstmlm_nce.py`: train LSTM LM using BNCE.
* `run_trf_<feat_type>_<train_method>.py': train TRF LMs with `<feat_type>` using `<train_method>`
  > * `<feat_type>` includes `discrete` (discrete features) and `neural` (neural network features)
