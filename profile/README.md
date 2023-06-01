# [캡스톤4조]실행매뉴얼

## 📖Back-End: Spring Boot 실행 매뉴얼

1. 소스 코드 다운받기
`git clone https://github.com/2023Capstone-Team4/springboot_team4.git`
2. 해당 폴더로 이동하기
`cd springboot_team4`
3. 실행하기
`gradle bootRun`

</br>

## 📖OpenVidu 실행 매뉴얼

1. 소스 코드 다운받기
`git clone https://github.com/OpenVidu/openvidu-tutorials.git -b v2.27.0`
2. 도커 실행하기
`docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-dev:2.27.0`
3. 해당 폴더로 이동하기
`cd openvidu-tutorials/openvidu-basic-java`
4. man 설치하기
`npm install mvn`
5. 실행하기
`mvn spring-boot:run`

</br>

## 📖Front-End: React 실행 매뉴얼

1. 소스 코드 다운받기
    
    `git clone https://github.com/2023Capstone-Team4/react_team4.git`
    
2. 패키지 설치하기
    
    `npm install`
    
3. 실행파일 실행하기
    
    `npm run start`
    
</br>

## 📖자세 교정 모델 실행 매뉴얼

1. Openpose 파일 다운받기
    
    https://github.com/CMU-Perceptual-Computing-Lab/openpose
    
    위 링크에서 파일을 다운받는다.(Download ZIP)
    
    ![github_img](https://github.com/2023Capstone-Team4/.github/assets/74875490/188d83e9-3b3a-47a0-b722-f5c4157544c0)
    
2. 파일을 압축해제 후, models 폴더의 getModels 파일 실행한다. 파일이 실행되면서 모델들이 다운로드 된다.
    
    ![getmodel_img](https://github.com/2023Capstone-Team4/.github/assets/74875490/936ca6f4-ed83-47c2-9ebc-647622931700)
    
3. 다운로드된 모델 중 pose_deploy_linevec_faster_4_stages.prototxt, pose_iter_160000.caffemodel을 사용한다. 해당 파일들을 실행파일과 같은 위치로 이동시킨다.
4. 실행파일을 실행한다.
