chmod +x download-core.sh

./download-core.sh 661d4f6c7d7b1117587654941f5fcf91acb5f4eb 0365b081efa8b55ab9fd58594aa599f9630268f6

Chạy DB mongo
docker compose up -d


Lưu ý: dùng node 14
Di chuyển vào thư mục H5P-Nodejs-library\packages\h5p-server

Mở tệp h5p-server\assets\editorLanguages.json thêm "vi" vào cuối.

Mở thư mục h5p-server\assets\translations thêm vi.json vào các folder muốn Việt hóa.

Mở Git Bash
npm install
npm run build
npm pack

Copy tệp lumieducation-h5p-server-9.3.2.tgz vừa tạo được sang thư mục: C:\workspace\05_LMS\H5P-Nodejs-library\packages\h5p-rest-example-server
Gõ lệnh:
npm install lumieducation-h5p-server-9.3.2.tgz

Trong thư mục h5p-rest-example-server\h5p\editor\language phải có tệp vi.json
npm run build


npm install

npm run start
