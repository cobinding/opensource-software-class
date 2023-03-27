# 2023 OSS 수업
-----
### 3주차 git


### 이미지
![로고](https://github.com/cobinding/OpenSource-Software-Class/blob/main/w3/%E1%84%85%E1%85%A9%E1%84%80%E1%85%A9.png)

### 링크
[LMS](https://lms.kau.ac.kr/)

### Progit 링크
[Progit](https://git-scm.com/book/ko/v2)

#### 주요 git 명령어
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
  * 예) git add
* commit
* git reset HEAD : stage된 파일을 unstaged로 변경
* git checkout -- : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림
* branch
* merge
* status
* log
  * 예) git log --oneline --decorate --graph --all
-----
### 2주차 숙제
```bash
echo "-----------"
echo "name :"
echo "추세빈"
echo
echo "----------"
echo "student id :"
echo "2020126109"
echo "----------"
echo
echo "file path :"
FILE_PATH=$(find /home/kau2  -name "w2_homework.txt")
echo "$FILE_PATH"
echo
echo "----------"
LINE_COUNT=$(wc -l < "$FILE_PATH")
echo "line number :"
echo "$LINE_COUNT"
echo
echo "----------"
echo "last line :"
tail -n 1 /home/kau2/k/w2_homework.txt
```
## 마크다운
### 목록


#### 번호 있는 목록 : 내림차순 정렬
1. 첫번째
2. 세번째
3. 두번째

#### 번호 없는 목록 : *,-,+
* 첫번째 
* 세번째
* 두번째
------
* 빨강
  * 녹색
    * 파랑


### 강조
*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~    
  
