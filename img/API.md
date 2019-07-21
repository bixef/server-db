# ERD (Entity-Relationship Diagram)

![ERD](C:\Users\phs45\Desktop\readme-md\ERD.png)



## API Reference for Developers

### food-basic-controller

##### GET )  /foodBasic/findAll

- Basic테이블의 모든 정보를 출력

##### GET)   /foodBasic/lessCalorle

-  칼로리 검색을 할 때 칼로리를 넣게되면 칼로리 값보다 작은 칼로리에 대해 basic 테이블의 정보를 출력

##### GET)  /foodBasic/lessMoreCalorie

- 최소 칼로리와 최대 칼로리를 이용하여 테이블 정보를 출력

##### GET)  /foodBasic/moreCalorle

- 최소 칼로리를 이용하여 칼로리 값보다 큰 값의 테이블 정보를 출력

##### GET)  /foodBasic/searchByMaterial

- 재료정보를 배열로 보내주어 재료가 material을 통해 basic 테이블을 정보를 출력 

##### GET)  /foodBasic/searchByRecipeId

- recipeId를 이용하여 테이블 정보 출력

##### GET)  /foodBasic/searchByRecipeName

- 레시피의 명을 통해 테이블 정보를 출력 (like)

### food-material-controller

##### GET)  /foodMaterial/findAll

- 모든 레시피별 재료정보를 출력

##### GET)  /foodMaterial/searchByRecipeId

- recipeId를 통해 레시피의 재료들을 출력

### food-process-controller

##### GET)  /foodProcess/findAll

- 모든 레시피별 과정 정보를 출력

##### GET)  /foodProcess/processSearchByRecipeId

- recipeId를 통해 레시피에 대한 과정 정보를 출력

### hits-controller

##### GET)  /hits/Insert

- 날짜, 레시피아이디, 유저주소를 받아와 조회 수를 증가

##### GET)  /hits/searchByRecipeId

- recipeId 를 이용하여 레시피에 대한 조회수 출력