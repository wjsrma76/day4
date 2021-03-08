 1.conda 이용한,파이썬 가상환경 설정방법
 a 만들기,실행하기,해제하기,파일로 내보내기,파일로 만들기,삭제하기 등
 아나콘다 프론트를 열어서 순서대로 쳐준다
 1.(base) >python --version
 2.(base) >conda info --envs
 3.(base) >conda create -n streamlit python=3.7.10 tensorflow numpy scipy matplotlib ipython scikit-learn pandas pillow jupyter seaborn
 4.(base) > conda activate streamlit
 위의 환경대로, 다른 컴에 똑같이 설치하고 싶을때, 아래 명령 실행하여, 파일을 이메일등으로 보내고
 5.(base) > conda list -e > requirements.txt
 집의 컴퓨터에서 아래 명령 실행해 준다.
 6.(base) > conda create -n streamlit --file requirements.txt
 이것은 파이썬 가상환경 설치해주는것이다.
 
