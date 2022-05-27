# TelematicaPP
Tutorial de volumen : http://www.dailysmarty.com/posts/steps-for-deploying-a-static-html-site-with-docker-and-nginx #La pagina web es un noticieron deportivo y si se edita el codigo html, esto se vera reflejado en nuestro localhost # 
docker build -t z . 

                         La ruta donde esta la pagina web                                 : donde nginx guarda el index 
                         
docker run -d -p 80:80 -v C:\Users\Camilo\Downloads\TelematicaPP\FinalTelematica\business-1:/usr/share/nginx/html --hostname nginx-container z 
 
--hostname nombre_personalizado nombredelBuild 
