## Demo1 : MRM CRUD Program
👉 만든 CRDU의 구조체, 함수, 기능 설명
#구조
title : char[30]
director : char[20]
genre : char[20]
distributor : char[20]
rating : float

int createMovie(Movie *p); // 제품을 추가하는 함수
void listMovie(Movie *p); // 전체 등록된 제품 리스트 출력
void readMovie(Movie p); // 하나의 제품 출력 함수
int updateMovie(Movie *p); //제품을 수정하는 함수 
int deleteMovie(Movie *p); //제품을 제거하는 함수
void saveData(Movie *p, int max); //제품을 저장하는 함수
void searchMovie(Movie *p, int max); // 제품이름 검색
int sortMovie(Movie *p, int max); // 정렬하기
int loadData(Movie *p);
int selectMenu(); //메뉴를 보여주는 함수
