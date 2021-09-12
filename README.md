# LFHC-GCDF-RPE
Code for paper "Explore Better Relative Position Embeddings from Encoding Perspective for Transformer Models" (Accepted by EMNLP 2021)

## ```init_code``` vs ```pretrain_code```
We released two versions of the code. The first version is the code corresponding to all the experiments in the original paper. The second version is the pre-training of five RPEs and the experimental results on the GLUE Benchmark. 

- init_code:
- pretrain_code:

## Environment
- python == 3.7
- torch == 1.7
- transformers == 4
- stanfordcorenlp == 4


## Reference
```bib
@inproceedings{qu2021better-rpe,
   title={Explore Better Relative Position Embeddings from Encoding Perspective for Transformer Models},
   author={Qu, Anlin and Niu, Jianwei and Mo, Shasha},
   journal={Empirical Methods in Natural Language Processing (EMNLP)},
   year={2021}
}
```