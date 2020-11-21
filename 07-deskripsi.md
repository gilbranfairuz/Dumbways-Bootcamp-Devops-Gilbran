1. clone repository todo-app
    - git clone https://github.com/sgnd/todo-app
2. pindah ke direktori todo-app
    - cd todo-app/
3. pindah ke branch master
    - git checkout master
4. inisiasi project (membuat project)
    - npm init -y ; -y digunakan agar disetting mengikuti todo-app
5. install depedencies
    - npm install
6. login heroku
    - heroku login
7. init dan remote
    - git init
    - heroku git:remote -a implement-test
8. menandai seluruh file untuk di-commit
    - git add .
9. commit
    - git commit -am "make it better"
10. push ke heroku
    - git push heroku master
11. cek di browser

12. Catatan:
    terjadi error ketika membuka app
    https://implement-test.herokuapp.com/