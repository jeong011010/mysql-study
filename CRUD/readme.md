## MySQL CRUD
C: Create  
R: Read  
U: Update  
D: Delete  

------------
### insert
insert into topic (colums 이름들) values(각각 값(순서에 맞게));
![](https://user-images.githubusercontent.com/28985560/164399912-0706bb5f-e3b6-4d79-84c9-c044cb31ea72.JPG)

결과창 (select * from topic)
![](https://user-images.githubusercontent.com/28985560/164400463-24204a00-b37a-4163-ba44-bb5ca064ebab.JPG)

------------
### select
select (colums 이름들) from (table 이름) + (여러가지 구문)  
[프로그래머스 sql 고득점 키드](https://programmers.co.kr/learn/challenges?tab=sql_practice_kit)에서 배운 것들로 실습 가능!!

여러가지 문법은 따로 폴더 만들어서 정리하겠음!
```
select * from topic where author = 'egoing' order by id desc;  
```
![](https://user-images.githubusercontent.com/28985560/164627750-7fee44cc-480c-499e-a3bc-edd78c7ecbf7.JPG)

------------
### update
update (table 이름) set (colums 이름)='수정내용' + (수정 조건 (where id=2;))  

```
update topic set description='oracle is', title='Oracle' where id=2;  
```
![image](https://user-images.githubusercontent.com/28985560/164628821-1f2799cf-ec6a-4dfb-ab80-abe200e03c0a.png)
