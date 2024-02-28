1. Python version: 3.8
2. Install package: pip install -r requirements.txt
3. Download dataset and unzip: https://drive.google.com/file/d/1sATVOQ-OnmN75r2EA1A1hGdK1TTyABe_/view?usp=sharing
4. Run script to create file qwenvl_format_train.json in vqadata: vqadata/process_data.py
5. Update DATA variable in finetune/finetune_lora_single_gpu.sh by the path of qwenvl_format_train.json
6. Run to finetuning: bash finetune/finetune_lora_single_gpu.sh