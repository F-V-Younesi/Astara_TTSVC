# Heb_TTS + Voice Cloning
Text to Speech and voice conversion model in Astara language.


# Project tree
  * [HebTTS](./API)
    * [static](./API)
    * [templates](./API)
     * [index.html](./API)
    * [ttsvc.py](./API)
    * [requirements](./API)
    * [app.py](./API)


## For Inference:

1-install necessary packages:
```
!pip install -r requirements.txt
# or in conda: conda install --yes --file requirements.txt
!pip install git+https://github.com/lhotse-speech/lhotse
```
2- clone repo and download trained models in "HebTTS" folder:</br>
```
!git clone https://github.com/slp-rl/HebTTS.git
!gdown 11NoOJzMLRX9q1C_Q4sX0w2b9miiDjGrv
!gdown '10Vck4FopduHX__1mb-hxDMDInA3ImSbT'
!gdown '14hdAkBabktYG9z9KPsO3GDX9V8IdLbTd'
```
<br>

3- Move models to "HebTTS" folder and cd(change directory) to this folder </br>
```
!mv 'checkpoint.pt' '/HebTTS'
!mv 'G_743.pth' '/HebTTS'
!mv 'config.json' '/HebTTS'
%cd  /HebTTS
```
4- run HebTTS/app.py
