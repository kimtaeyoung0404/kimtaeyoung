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
#### 7. 온도
 확인과 쿨링팬
***
jtop : system monitoring tool
terminal 열기
```
sudo apt install python3-pip
sudo -H pip3 install -U jetson-stats
```
만약 에러가 뜨면 sudo apt-get upgrade, sudo apt-get update해준다.
jetson-stats-4.2.3 가 써진 걸 확인.
이제 온도를 확인하자
```
reboot
jtop
```
이제 쿨링팬을 돌려보자
```
sudo sh -c 'echo 128 > /sys/devices/pwm-fan/target_pwm'
```
다시 온도를 확인해보자. 온도가 많이 떨어진다.


