# install and run face_recognition application

- install

```bash
pip install -r requirements.txt
```

- encoding faces

```bash
python encode_faces.py --dataset dataset --encodings encodings.pickle \
	--detection-method cnn
```

- run camera

```bash
python pi_face_recognition.py --cascade haarcascade_frontalface_default.xml \
	--encodings encodings.pickle
```
## Encoding Dataset
[You can click here to download encoding dataset](https://drive.google.com/file/d/1Dd-DvLjrEA7DuqyrPCCPsi9QrIyYTV9N/view?usp=sharing)
