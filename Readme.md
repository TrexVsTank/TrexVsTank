# Hi

# 헤더
## 헤더2
### 헤더3
#### 헤더4
##### 헤더5
###### 헤더6(최대 6개)
일반\
*기울*\
**굵게**\
***기굵***
# ordered 리스트 적기
1. tab을 눌러 보세요
   1. 하나
   2. 둘
2. 엔터를 두번 세번 눌러 보세요
5. 다섯?

# unordered 리스트
* 하나
* 둘
+ 하나
+ 둘
- 엔터를 여러번 눌러도 다시 돌아간다
- 다시 돌아가기 키는 쉬프트 + 탭

# 체크 리스트
- [ ] 쌀
- [X] 삼겹살
- [ ] 김치

# 코드블록 (`백틱 3번)
```python
a = int(3)
print(a)
```
```python
a, b, n = input(). split()
a = int(a)
b = int(b)
n = int(n)
c = int(0)
for i in range(n):
    c = c + a
    a = a + b
print(c)
```

# 링크 url 걸기
[네이버](https://www.naver.com)\
[네이버] (https://www.naver.com)

# 이미지 걸기
[삼겹살](https://ai.esmplus.com/foodjang01/images/221106957_b_1.jpg)
![삼겹살](https://ai.esmplus.com/foodjang01/images/221106957_b_1.jpg)

# *굵게 표현하기*
__언더바__\
**별 두번(글 중간에 는 별을 사용)**
# *기울이기*
_언더바_\
*별(마찬가지로 글 중간에 쓸 때는 별로)*
# ***굵게 기울기기***
___언더바___\
***별***
# ~~취소선~~
~~물결2개~~\
***~~물결2개~~***
# 수평선
---
---
---
하나둘셋


git config --global user.name 김민섭
git config --global user.email qwedsaszxc@naver.com
git config --global -l

touch a.txt
touch b.txt
touch c.txt
touch abs.css
touch abs.html
touch Readme.md

git init
git reset
git status
rm -rf .git

echo c.txt >> .gitignore

git add .
git commit -m 'first+pjt'
git log

git remote add origin https://github.com/TrexVsTank/1.git

git remote -v

git push origin +master

git pull origin master

git clone https://github.com/TrexVsTank/1.git
