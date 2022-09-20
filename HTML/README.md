~/full-stack-course/html$ docker build -t torvicvasil/nginx-html .
~/full-stack-course/html$ docker run --rm -d -p 8080:80 torvicvasil/nginx-html
4ba4b53787364282e5260e28eba6b92639eca2f793d4a1f64866ff8edfbec612
~/full-stack-course/html$ curl localhost:8080
~/full-stack-course/html$ curl localhost:8080/01-hello_world.html

Entrar no container: docker exec -it a1f411113e771b49598c91825ef3a487b438d56a43ea5050fab6a79f6d00df64 /bin/bash


https://devdocs.io/
https://www.w3schools.com/howto/howto_css_style_hr.asp
https://phase2.github.io/devtools/common-tasks/ssh-into-a-container/
https://techobservatory.com/how-to-launch-chrome-on-visual-studio-code/#:~:text=In%20the%20%E2%80%9CSearch%20Settings%E2%80%9D%20bar,from%20the%20Custom%20Browser%20settings.