```bash
# create venv for this project

python3 -m venv venv

# activate 
. venv/bin/activate 

# install dependencies 
pip install fastapi
pip install uvicorn

# for creating requirements
pip freeze > requirements.txt

# build image
docker build -t <name of image> . 

# run image with port configs 
docker run -p 8000:8000 <name of image>

```