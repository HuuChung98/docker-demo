# cài phần mềm => mặc định port 80
FROM nginx  

# đường dẫn làm việc ở container docker
WORKDIR /usr/share/nginx/html

# sao chép file từ máy local lên docker 
COPY . .

# docker build . -t img-html
# docker run -d -p 3000:80 --name cons-html img-html
# npm run build => gợi ý cho react 