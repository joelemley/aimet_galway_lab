Codespaces starting container code for the Professional Diploma in Practical AI for software developers labs and assignments related to Edge AI. 

Sadly, the docker image we used in class is too large for Codespaces (artifacts.codelinaro.org/codelinaro-aimet/aimet-dev:latest.onnx-cpu) but this is okay because the artifacts.codelinaro.org/codelinaro-aimet/aimet-dev:latest.torch-cpu version seems to have everything needed and is small enough. 

Do the following after you launch your codespace in your workspace folder:
python -m pip install -U pip
python -m pip install aimet-onnx
git clone https://github.com/quic/aimet.git


