# GLIGEN: Open-Set Grounded Text-to-Image Generation (CVPR 2023)

- Fork of the original GLIGEN repo for development purpose. Please read the original [repo](https://github.com/gligen/GLIGEN) to prepare the environments.

Here's what I've done.

1. Download and process all data according to their [instructions](./DATA/README.MD) at `/shared/patrickwu/GLIGEN`. This includes executing the `tsv_split_merge.py` program (which I've fixed a bug) and updated the path in `dataset/catalog.py`.

2. Download the pretrained sdv1.4 checkpoint at `/shared/patrickwu/GLIGEN/DATA/sd-v1-4.ckpt` (from) as GLIGEN needs it when running their code.

3. Run the code: `python main.py --name=trial_batch --yaml_file=configs/alldata_boxtext2img.yaml`
