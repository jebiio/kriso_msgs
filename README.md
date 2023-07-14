# kriso_msgs
## How to build
```bash
cd <워크스페이스 경로>/src
git clone https://github.com/jebiio/kriso_msgs.git
cd <워크스페이스 경로>
catkin build
```

## 사용
* kriso_msgs에 의존성이 있는 패키지의 CMakelists.txt 수정
  * find_package()에 kriso_msgs 추가
    * ![](https://github.com/jebiio/kriso_msgs/blob/main/materials/2307141.png)
  * catkin_package()에 kriso_msgs 추가
    * ![](https://github.com/jebiio/kriso_msgs/blob/main/materials/2307142.png)
* package.xml 수정
  * build_depend 추가
    * ![](https://github.com/jebiio/kriso_msgs/blob/main/materials/2307143.png)
  * run_depend 추가
    * ![](https://github.com/jebiio/kriso_msgs/blob/main/materials/2307144.png)
