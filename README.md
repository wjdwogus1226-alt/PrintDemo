## 1️⃣ main_print_v1.py

이 파일은 **Python의 `print()` 함수 기본 사용법**을 학습하기 위한 예제입니다.

주요 내용:
- **변수 선언**  
  `name`, `age`, `score` 같은 변수를 만들어서 출력 예제에 활용
- **기본 출력**  
  `print("Hello, Python!")` 형태의 단순 출력
- **여러 값 출력**  
  `print()`에서 콤마(`,`)를 이용한 다중 값 출력 (자동 띄어쓰기)
- **f-string 사용**  
  최신 Python에서 가장 많이 쓰는 포맷팅 방식 (`f"My name is {name}"`)
- **`format()` 함수**  
  `.format()` 메서드 활용, 인덱스 기반/순서 기반 출력 가능
- **C 스타일 포맷팅**  
  `%s`, `%d`, `%f` 같은 포맷 코드 사용
- **줄바꿈과 end 옵션**  
  `\n`을 이용한 줄바꿈, `end=" "`로 줄바꿈 없이 이어서 출력
- **sep 옵션**  
  `sep="-"`로 값 사이 구분자 지정
- **딕셔너리 출력**  
  `print()`로 dict 출력
- **f-string 내 계산/함수**  
  `age + 1`, `round(score)` 같은 연산 가능
- **멀티라인 출력**  
  `""" ... """` 또는 `''' ... '''` 를 이용한 여러 줄 출력

이 파일은 **Python 초보자가 print()를 완벽히 익히기 위한 실습 코드**로 적합합니다.

실행 방법:
```bash
python main_print_v1.py

## 2️⃣ main_print_v2.py

이 파일은 [**rich**](https://github.com/Textualize/rich) 라이브러리를 활용해  
**터미널에서 컬러풀하고 시각적으로 보기 좋은 출력**을 만드는 예제입니다.

주요 내용:
- **라이브러리 사용**  
  `pip install rich` 필요
- **컬러 + 스타일 출력**  
  `[bold green]`, `[cyan]` 같은 스타일 태그로 색상과 굵기 적용
- **Panel (박스 출력)**  
  `Panel()`을 활용해 멀티라인 텍스트를 테두리 박스로 감싸 출력
- **Table (표 출력)**  
  `Table()`을 이용해 키-값 형태의 데이터를 깔끔하게 정렬해서 표시
- **sep, end 옵션 활용**  
  기본 `print()` 함수와 동일하게 `sep`, `end` 사용 가능

이 파일은 **터미널 출력 결과를 보기 좋게 꾸미고 싶은 경우** 활용할 수 있는 예제입니다.

실행 방법:
```bash
pip install rich
python main_print_v2.py
yaml
코드 복사


## 3️⃣ main_print_v1.ipynb

이 파일은 `main_print_v1.py`의 내용을 **Jupyter Notebook**에서 단계별로 실행할 수 있도록 만든 버전입니다.

주요 특징:
- **셀 단위 실행**  
  한 줄씩 / 한 섹션씩 실행해보면서 결과를 바로 확인할 수 있음
- **인터랙티브 학습**  
  변수 값을 수정하고 다시 실행하면서 실험 가능
- **학습 및 시연용**  
  print() 함수의 다양한 사용법을 실습할 때 유용

실행 방법:
```bash
jupyter notebook main_print_v1.ipynb


## 4️⃣ requirements.txt

이 파일은 프로젝트 실행에 필요한 **패키지 의존성 목록**입니다.

주요 패키지:
- **rich** – 터미널 출력에 컬러/스타일 적용
- **ipykernel, jupyter_client, jupyter_core** – Jupyter Notebook 실행 환경
- **Pygments, markdown-it-py** – 코드/마크다운 렌더링
- **psutil, tornado** – Notebook 서버 실행에 필요한 내부 모듈

사용 방법:
```bash
pip install -r requirements.txt