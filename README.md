### 설치
- pip install --upgrade pip
- pip install pyenv => pyenv가 없을 경우
- pyenv install 3.9.0
- pyenv virtualenv 3.9.0 fast-api
- pyenv activate fast-api
- 프로젝트 경로 이동 후 pyenv local(가상환경이 프로젝트 폴더에 fix됨)
- pip install --user poetry
- poetry install