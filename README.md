# AiG
Combining ViG and AST Models

Clone the ast repo.
```
git clone https://github.com/YuanGongND/ast
cd ast
```
Install python dependencies from requirments.txt
```
pip install -r requirements.txt
```
Install SoX and few programs for audio processing
```
apt-get install sox libsndfile1 ffmpeg
```
Install flash linear attention 
```
pip install -U git+https://github.com/sustcsonglin/flash-linear-attention`
```

Now go to the file ast/src/models/ast_models.py

Repace the contents of that file with the ast_models.py file provided in this repo.

To run esc50 dataset. Go inside ast repo.
```
cd egs/esc50
chmod +x run_esc.sh
./run_esc.sh
