Getting Started with AI on Jetson Nano
# 젯슨나노
![jetson nano](https://github.com/user-attachments/assets/e69433e4-91dc-4567-bd6b-1426c5876316)

<b> getting started with Ai on Jetson Nano

'''
1. jetson nano setting 준비물
- jetson nano 4gb 

- c type power adapter
- 와이파이 동글
- 웹캠(usb camera), 또는 CSI Camera (라즈베리파이 V2)
- 64기가 이상 마이크로SD카드 
- 그 외 쿨링팬, 1cd, 또는 모니터. hdmi
'''

<b> 2. jetson nano에 대하여

<b>  welcome 부터 따라하기 
- 참고링크 : https://learn.nvidia.com/courses/course?course_id=course-v1:DLI+S-RX-02+V2&unit=block-v1:DLI+S-RX-02+V2+type@vertical+block@aba5104413ae454c8c63a6f301925337

<b> 3. jetpack download
 https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write

<b> 4. 이미지 굽기 위해 필요한 것
   4-1. sd card formatter  download
   4-2. balenaetcher download --->  이미지 굽기
   4-3. https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write
   ![26](https://github.com/user-attachments/assets/ee789bea-e004-4e73-8c10-92bdf2a3306c)
![30](https://github.com/user-attachments/assets/ca79b3ab-2b58-4b7f-aafe-61bee93bab23)


<b> 5. 우분투 설치를 진행하고 완료후 셋팅을 진행 
   5-1. ![스크린샷 2024-09-06 155044](https://github.com/user-attachments/assets/5ef6b160-8ae2-4be7-bdbb-85a560caf2ee)
   5-2. 와이파이 셋팅 ![37](https://github.com/user-attachments/assets/05964ce6-1a6f-4f84-9cbd-5704fe5178f0)
   5-3. 모든 절차를 완료후 녹색화면이 뜸![46](https://github.com/user-attachments/assets/bece2340-179f-4737-aaf9-07ced2c41815)

<b> 6. 쿨링팬 설치와 jtop 설치
 ``` bash


# crawling-data
데이터 크롤링
####  참고 링크 
```
https://keep-steady.tistory.com/29
```
#### 노트북에서 좌측 하단에 cmd 창을 열고 진행을 시작 

``` bash
C:\Users\user>cd ..

C:\Users>cd ..

C:\>mkdir project_ai
cd mkdir project_ai
```
```
git clone --depth 1 https://github.com/YoongiKim/AutoCrawler
```
<b>
  결과
  
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 12 (delta 0), reused 8 (delta 0), pack-reused 0
Receiving objects: 100% (12/12), 16.48 MiB | 2.30 MiB/s, done.

```
cd AutoCrawler

C:\project_ai\AutoCrawler>pip install -r requirements.txt
```
<b>
장원영
카리나
윈터 
김채원

를 내 컴퓨터 -> 로컬 디스크 C->projetcs-> AutoCroawler-> kewwords.txt 에 dog, cat 지우고 넣어준 후 저장
크롤링 실행
```
C:\project_ai\AutoCrawler>python main.py  --limit 20

```
<b>   EfficientNet-pytorch 설치
```
$pip install efficientnet_pytorch
$pip install scikit-learn
$git clone https://github.com/lukemelas/EfficientNet-PyTorch
$cd EfficientNet-Pytorch
$pip install -e .
```
![aa](https://github.com/user-attachments/assets/86482ef3-9988-44c5-9a4e-3747cc5b4a21)

![bb](https://github.com/user-attachments/assets/11714644-0dc9-43ed-b158-97658841f846)
![cc](https://github.com/user-attachments/assets/bd1f429b-8c5f-4a9a-bccb-9294219792ab)
![dd](https://github.com/user-attachments/assets/be247eba-3781-40f6-9460-353558726011)


