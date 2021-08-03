The dataset in [```dataset_wmt/wmt21```](dataset_wmt/wmt21) is copied from https://github.com/sheffieldnlp/mlqe-pe/tree/master/data/catastrophic_errors/.

We merge together the different languages and prepare them as train and dev set in pickle format in ```data_construction.ipynb```.

The notebook ```backtranslation.ipynb``` is used to create backtranslations (to English) for every sentence pair.
