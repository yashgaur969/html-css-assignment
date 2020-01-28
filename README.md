# HUV17.0 HTML CSS Final Assignment

#Docker Image Build Command
docker build -t html_css_final_assignment .

#Docker Image Run Command
docker run -p 8000:80 html_css_final_assignment

#Push the docker image to Portus
1. Login to Portus - docker login portus.hashedin.com
2. Tag the image - docker tag html_css_final_assignment:latest portus.hashedin.com/<namespace>/html_css_final_assignment:latest 
3. Push the image - docker push portus.hashedin.com/<namespace>/html_css_final_assignment:latest