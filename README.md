![image](https://github.com/user-attachments/assets/4a96a125-8cce-4935-98d8-d13e3caf73c0)


❓ **Viztector가 뭐예요?**  
**Viztector**는 그래프 이미지에서 발생할 수 있는 데이터 왜곡을 실시간으로 분석하고, 교정해주는 AI 기반 솔루션입니다. [ChartReader](https://github.com/zhiqic/ChartReader)와 [korean_ocr_using_pororo](https://github.com/black7375/korean_ocr_using_pororo)를 활용하여 그래프의 왜곡 문제를 탐지하고, 이를 자동으로 교정합니다. 이 프로젝트는 연구 및 데이터 시각화에서 정확하고 신뢰성 있는 그래프를 제공할 수 있도록 지원합니다.

🌐 **웹사이트**  
Viztector 공식 웹사이트는 준비 중입니다.

🙋‍♂️ **어떻게 사용하나요?**  
1. Conda 가상환경을 설정하세요.  
2. 필요한 패키지를 설치하고 Pororo를 설정하세요.  
3. 모델을 다운로드하고 테스트 이미지를 준비하세요.  
4. 왜곡된 그래프를 교정하는 테스트를 실행하세요.  

🛠 **주요 기능**  
- **그래프 왜곡 탐지**: 이미지에서 그래프 왜곡 여부를 자동으로 분석합니다.  
- **교정 기능**: 탐지된 왜곡된 그래프 데이터를 수정하고 교정합니다.  
- **OCR 기반 텍스트 분석**: Pororo를 활용하여 그래프 내 한글 텍스트도 인식합니다.  
- **크롬 익스텐션 지원**: 브라우저에서 그래프 이미지를 직접 분석할 수 있는 크롬 확장 프로그램을 제공합니다.  

💻 **설치 및 실행 방법**  

설치 절차:  
```bash
git clone https://github.com/your-repo/Viztector.git
cd Viztector
```

가상환경 설정:  
```bash
conda create -n Viztector python=3.7.13
conda activate Viztector
```

필수 패키지 설치 및 Pororo 설치:  
```bash
pip install -r requirements.txt
git clone https://github.com/kakaobrain/pororo.git
cp ./pororo_setup.py ./pororo/setup.py
cd pororo
pip install -e .
```

KPGrouping 모델 파일 다운로드:  
`cache/nnet/KPGrouping` 경로에 **KPGrouping_best.pkl** 파일을 추가하세요.  
[모델 파일 다운로드](https://drive.google.com/file/d/11Z6cNl-5dcpbuDq9N_ZrB7rPUoJvAH_u/view?usp=drive_link)

모델 테스트:  
테스트 이미지 파일을 `img/images/val` 폴더에 복사한 후,  
`detection_test.ipynb`를 실행하여 모델을 테스트하세요.


🛠 **기술 스택**  
- **프론트엔드**: **크롬 익스텐션** (HTML, CSS, JavaScript)  
- **백엔드**: 파이썬, Flask  
- **AI 모델**: Pororo, ChartReader  


📝 **개발자 소개**  


🐞 **버그 및 디버깅**  
- **버그 리포트**: GitHub 이슈 페이지를 통해 버그를 보고해 주세요.  
- **디버깅**: ESLint와 Prettier를 통해 코드 스타일을 유지하고 오류를 자동으로 수정합니다.

📄 **저작권 및 사용권 정보**  
이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자유롭게 수정 및 배포할 수 있으며, 저작권 고지를 유지해야 합니다.

📚 **참고 및 출처**  
- ChartReader Documentation  
- Pororo Documentation  
- Flask Documentation  

🔄 **버전 및 업데이트 정보**  
- 현재 버전: 1.0.0  
- 최신 업데이트: 2024년 6월  
- 다음 업데이트 예정 기능: 미정

❓ **FAQ**  
**Q1:

**Q2:
