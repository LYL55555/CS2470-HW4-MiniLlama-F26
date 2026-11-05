# CSCI 2470 HW4

## run

```bash
conda activate csci2470
python run_llama.py --option generate
```

## settings

- generation seed: 123
- classification seed: 1337
- fine-tuning epochs: 5
- learning rate: 2e-5
- fine-tuning batch size: SST 80, CFIMDB 10

## results

| Method | SST Dev | SST Test | CFIMDB Dev |
|---|---:|---:|---:|
| Prompting | 21.34% | 22.44% | 50.20% |
| Fine-tuning | 42.51% | 44.52% | 86.53% |
