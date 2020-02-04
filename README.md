# pix2pix-tpu

## Train

Run:
```
python3 main.py --data-dir <gs://bucket/data> --mode train --output_dir <gs://bucket/results> --checkpoint <gs://bucket/checkpoints> --max_steps <int> --max_epochs <int> --summary_freq <int> --progress_fre
q <int> --save_freq <int> --no_flip --use-tpu --tpu <tpu-name> --tpu-zone <zone> --gcp-project <project-name> --model-dir gs://<bucket/checkpoints>
```
