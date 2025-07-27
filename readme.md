## Create python virtual environment 

```bash
python3 -m venv venv
source venv/bin/activate
```

## Install ggallery

```bash
pip install ggallery
```

## Generate gallery from gallery.yaml

```bash
ggallery
```

## Push updated docker image to Docker Hub

```bash
docker push creeston/photo-gallery:latest
```