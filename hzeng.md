# install
```bash
# https://github.com/vllm-project/vllm/issues/4201
# must using existing torch>=2.4
pip install torch==2.4.0 torchvision==0.19.0 torchaudio==2.4.0 --index-url https://download.pytorch.org/whl/cu121
cd vllm
python use_existing_torch.py
pip install -r requirements-build.txt
pip install -e . --no-build-isolation
```
# run
```bash
spack load cuda@12.1
......
```